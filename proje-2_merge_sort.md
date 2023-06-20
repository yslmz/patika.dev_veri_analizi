# patika.dev_veri_analizi
Proje Ödevler

# PROJE-2
## Merge Sort

----------------------------------------------------------------------------------------------------

SORU-1 : [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

CEVAP-1 :

[16,21,11]-[8,12,22]

{[16,21]-[11]}-{[8,12]-[22]}

{[16]-[21]-[11]}-{[8]-[12]-[22]} => BU AŞAMAYA KADAR TÜM ELEMANLARI ADIM ADIM TEK PARÇAYA AYIRDIK.

{[16][11,21]}-{[8][12,22]} => BU AŞAMADAN SONRA TÜM ELEMANLARI "KÜÇÜK ELEMAN SOLDA, BÜYÜK ELEMAN SAĞDA" OLACAK ŞEKİLDE ADIM ADIM BİRLEŞTİRDİK.

[11,16,21]-[8,12,22]

[8,11,12,16,21,22] 

----------------------------------------------------------------------------------------------------------

SORU-2 : Big-O gösterimini yazınız.

CEVAP-2 : O(n.Log(n))
