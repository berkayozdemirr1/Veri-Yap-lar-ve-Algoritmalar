## Insertion Sort
----
# Proje I

**1)** **[22,27,16,2,18,6]** dizisinin insertion sort türüne göre aşamalarını yazınız.*

- **[22 27|16 2 18 6]**  => **1. Adım**

Birinci adımda birinci ve ikinci indexleri karşılaştırır. 27 22'den büyük olduğu için hiç bir işlem yapılmaz.

----

- **[16 22 27|2 18 6]**  => **2. Adım**

İkinci adımda üçüncü indexi önce ikinciyle daha sonra ilk indexle karşılaştırıp swapler.

----

- **[2 16 22 27|18 6]**  => **3. Adım**

Bu adımda dördüncü indeksi üçüncüyle kıyaslar daha sonra sıralı dizi ile kıyaslar ve swapler.

----


- **[2 16 18 22 27|6]**  => **4. Adım**

Bu adımda beşinci index bir öncekiyle kıyaslanır daha sonra sıralı diziyle kıyaslanıp doğru yere konuşlanır.

----

- **[2 6 16 18 22 27]**  => **5. Adım**


Bu adımda son index bir önceki indeksle ve sonrasında sıralı diziyle kıyaslanarak doğru yere varır.

----
**2)** Big-O gösterimini yazınız.
- O(n^2)
----
**3)**  Time Complexity
- Best Case : **(n)** Bütün dizinin sıralı olduğunu varsayarsak hiç yer değiştirme işlemi yapmadan sadece listeyi tarar.
- Average Case : Worst case ile best case'in ortalamasını alırsak (n^2.n)/2=n^2
----
**4)** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

- *[2,6,16,18,22,27]* 18 sayısı dizinin ortasında olduğu için Average Case kapsamına girer.

----
**5)** *[7,3,5,8,2,9,4,15,6]* dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- *[7 3 5 8 2 9 4 15 6]* => **Array**
- *[3 7 | 5 8 2 9 4 15 6]* => **1.Adım**
- *[3 5 7 | 8 2 9 4 15 6]* => **2.Adım**
- *[3 5 7 8 | 2 9 4 15 6]* => **3.Adım**
- *[2 3 5 7 8 | 9 4 15 6]* => **4.Adım**