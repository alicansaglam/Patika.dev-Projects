# Proje 3 (Binary Search Tree)

[7,5,1,8,3,6,0,9,4,2]

## Yukarıda verilen dizinin Binary Search Tree aşamalarını yazınız.

            7
        5       8
      1   6       9
    0   3
      2  4  

## Açıklamalar

- Rootumuz 7'dir.
- 5, 7'den küçüktür, root'un soluna geçer.
- 1, 7 ve 5'ten küçüktür, 5'in soluna geçer.
- 8, 7'den büyüktür, 7'nin sağına geçer.
- 3, 7'den ve 5'ten küçük ve 1'den büyüktür bu yüzden 1'in sağına geçer.
- 6, 7'den küçük 5'den büyüktür, 5'in sağına geçer.
- 0, hepsinden küçüktür, 1'in soluna geçer.
- 9, hepsinden büyüktür, 8'in sağına geçer.
- 4, 7 ve 5'ten küçük ve 1 ve 3'ten büyüktür. 3'ün sağına geçer.
- 2, 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçüktür. 3'ün soluna geçer.
