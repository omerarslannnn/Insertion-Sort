Proje 1

[22,27,16,2,18,6]

1.Insertion Sort olarak yazmak için ilk önce bu altı sayıdan en küçüğü(2) bulunur ve en baştaki sayıyla yer değiştirir.[2,27,16,22,18,6]
  Daha sonra kalan beş sayının en küçüğü(6) bulunup soldan ikinci sayı ile yer değiştirir. [2,6,16,22,18,27]
  Bunlardan sonra kalan dört sayının en küçüğü(16) bulunur, üçüncü sayı olduğu için yer değiştirmesi gerekmez. [2,6,16,22,18,27]
  Geriye kalan üç sayının en küçüğü(18) bulunur, ve dördüncü sıradaki ile yer değiştirir. [2,6,16,18,22,27]
  Son kalan iki sayının küçüğü bulunup beşinci sıraya yazılır. [2,6,16,18,22,27]
  En son kalan sayı da yerinde kalır. [2,6,16,18,22,27]

2.Big-O Gösterimi
  n*(n+1)/2'den O(n²) gösterimi elde edilir.

3.Time Complexity
  Best Case: [2,6,16,18,22,27]
  Worst Case: [27,22,18,16,6,2]
  Average Case: [6,16,27,2,22,18]

4.18 Sayısı Hangi Case
  18 sasıyı case sıralandıktan sonra [2,6,16,18,22,27] en ortada olur yani "Average Case".

5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

  İlk adım dokuz sayıdan en küçüğü(2) bulunur ve baştaki ile yer değiştirir. [2,3,5,8,7,9,4,15,6]
  İkinci adım olarak geriye kalan sekiz sayının en küçüğü(3) bulunur ve ikinci ile yer değiştirir ancak burda zaten ikinci yerde olduğu için değişmez. [2,3,5,8,7,9,4,15,6]
  Üçüncü adım olarak geriye kalan yedi sayyının en küçüğü(4) bulunur ve üçüncü ile yer değiştirir. [2,3,4,8,7,9,5,15,6]
  Dördüncü adımda ise geriye kalan altı sayının en küçüğü(5) bulunur ve dördüncü ile yer değiştirir. [2,3,4,5,7,9,8,15,6]