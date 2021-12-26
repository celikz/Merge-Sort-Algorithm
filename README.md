# Merge-Sort-Algorithm
You can show to how applied the merge sort algorithm and how much efficient this algorithm

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

1- Merge Sort Algoritması diziyi parçalara bölerek arama yapmaktadır. Böylece aranan alan her defasında yarıya bölüneceği için zamandan kazanç oldukça fazla olacaktır.

İlk adımda diziyi ortadan ikiye bölüyoruz. Diğer adımda da bölünen dizileri tekrar ikiye bölüyoruz. 3 elemanlı bir dizide istediğiniz gibi bölme yapabilirsiniz. Bu bölme işlemi her eleman ayrılana kadar devam edecektir. Her elemanın kendisi bir dizi olduktan sonra birleştirme işlemi başlar, bu sefer elemanlar birleşirken küçükten büyüğe dizilerek dizileceklerdir. Böylece bütün elemanlar küçükten büyüğe sıralanmış olurlar. 

![image](https://user-images.githubusercontent.com/67806354/147416310-60f20632-ea92-45c2-875d-906ac6ab0e4e.png)

2- Big-O Notation:

Big-O gösterimi için dizide kaç kere işlem yapıldığını saymak gerekir.

Taradığımız alan her seferinde yarıya indiği için n elemanlı bir dizi için 2^x kadar işlem yapılır.

2^x = n

logn = x kere işlem yaparım ve her işlemde n eleman olduğu için toplam işlem sayımız n*logn şeklinde olacaktır.

O(nlogn)
