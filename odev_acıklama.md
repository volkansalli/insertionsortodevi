# Insertion Sort Odevi Cozum
- ana dizi [22,27,16,2,18,6] -> Insertion Sort

# Soru ve Cevaplar

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap1: Insertion sort için= Dizinin ilk elemanından itibaren sorgulamaya başlanılır, her karşılaştırmada küçük-büyük sorgulaması yapılır. Sonuca göre küçük eleman ile büyük olan küçük solda olacak şekilde başa yazılır.

2. Big-O gösterimini yazınız.

Cevap2: O(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Cevap3: (sıralama değil arama yapıyorsak, dizinin hangi elemanı 18'e eşitse oraya kadar sorgularım. Dizinin ilk elemanı 18 ise 1. adımda bulurum, sonuncu eleman 18 ise n tane dizi elemanına bakarım yani 6, ortada ise 4. ya da 3. olabilir )

Average Case : O(n)=3 veya 4

Worst Case : o(n)=6

Best Case : O(n)=1 

Eğer sıralama için konuşuyorsak;

Dizi tamamen yanlış sıralı ise sıralı ise;

Worst Case: (n*(n+1)/2)

Sadece 1 elemanın yeri yanlış ise;

Best Case: n

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 sıralama sonrası orta gruba düşer, bu yüzden average case olur. sıralı hal=[2,6,16,18,22,27]

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Adım1:  [2,3,5,8,7,9,4,15,6]

Adım2:  [2,3,5,8,7,9,4,15,6]

Adım3:  [2,3,4,8,7,9,5,15,6]

Adım4:  [2,3,4,6,7,9,5,15,8]