# Binary Search Tree

Bu veri yapısı node'lardan oluşuyor. Her node da iki 'child node'dan oluşuyor. En üstte bulunan node root adlandırılıyor. Sol tarafta root'dan küçük, sağ tarafta ise büyük birimler yerleştiriliyor. 

## **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

Burada 7 root olarak seçilir. Ondan sonra gelen 5 birimi 7'den küçük olduğu için sol tarafa yazılır:

<img src="https://github.com/sebuhif/Binary-Search-Tree-Projesi/blob/main/Untitled1.png" alt="Untitled1" style="zoom:75%;" />

Daha sonra gelen 1 birimi 7'den küçük olduğu için sol tarafa gider. Aynı zamanda 5'ten de küçük olduğu için onun soluna gider:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled2.png" alt="Untitled2" style="zoom:75%;" />

Sonra gelen 8 root olan 7'den büyük olduğu için sağa yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled3.png" alt="Untitled3" style="zoom:75%;" />

3 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled4.png" alt="Untitled4" style="zoom:75%;" />

6  7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır:

![Untitled5](C:\Users\sebuh\OneDrive\Desktop\Untitled5.png)

0 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled6.png" alt="Untitled6" style="zoom:75%;" />

9 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled7.png" alt="Untitled7" style="zoom:75%;" />

4 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled8.png" alt="Untitled8" style="zoom:75%;" />

2 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır:

<img src="C:\Users\sebuh\OneDrive\Desktop\Untitled9.png" alt="Untitled9" style="zoom:75%;" />
