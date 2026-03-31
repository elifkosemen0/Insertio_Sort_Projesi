#1.Proje 1: Insertion Sort

Dizi: [22, 27, 16, 2, 18, 6]
Sıralama Aşamaları
-[22, 27, 16, 2, 18, 6] -> 27, 22'den büyüktür, yerinde kalır.
- [16, 22, 27, 2, 18, 6] -> 16, 22 ve 27'den küçük olduğu için en başa yerleşir.
- [2, 16, 22, 27, 18, 6] -> 2, tüm sayılardan küçük olduğu için en başa yerleşir.
- [2, 16, 18, 22, 27, 6] -> 18, 16 ile 22 arasına yerleşir.
- [2, 6, 16, 18, 22, 27] -> 6, 2 ile 16 arasına yerleşir ve sıralama biter.
 
 #2. Big-O Gösterimi
- Average Case: O(n^2)
- Worst Case: O(n^2)
- Best Case: O(n)

#3. Time Complexity Analizi
Dizi sıralandıktan sonra [2, 6, 16, 18, 22, 27] halini alır. 18 sayısı dizinin ortasında bulunduğu için bu senaryo Average Case'dir.


#[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
-[2, 3, 5, 8, 7, 9, 4, 15, 6] En küçük sayı 2'dir. 7 ile 2 yer değiştirir.
-[2, 3, 4, 8, 7, 9, 5, 15, 6]İlk iki eleman (2, 3) sıralıdır.Sonraki en küçük sayı 4'tür.4, 5 ile yer değiştirir
-[2, 3, 4, 5, 7, 9, 8, 15, 6] Sonraki en küçük sayı 5'tir. 5, 8 ile yer değiştirir.
