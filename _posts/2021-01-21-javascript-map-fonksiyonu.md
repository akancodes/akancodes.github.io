---
published: true
---
# JavaScript .map() Fonksiyonu
Bugün sizlere JavaScript'in bence en güzel fonksiyonlarından biri olan .map() fonksiyonunu anlatacağım. 
### Ne işe yarıyor bu .map()?
.map() fonksiyonu bizim dizilerimizi bir döngü içerisine soktuktan sonra, bu dizideki her eleman için istediğimiz işlemi yapmamızı sağlıyor. İstersek sadece sade bir şekilde dizilerimizi bir döngüye sokabiliriz ve üzerinde bir işlem yapmayız. Genellikle üzerinde belirli eklemeler yapılıyor. Biraz örnek vermem gerekirse:

    let numbers = [4,  9,  16,  25];

**numbers** adında bir dizi tanımlıyoruz.

     const result = numbers.map(number  =>  Math.sqrt(number)) 

.map() fonksiyonu ile **numbers** dizimizin her bir elemanını dönüyoruz ve her bir elemana **number** adını veriyoruz, dönmüş olduğumuz elemanların her birisini **Math.sqrt()** fonksiyonu ile karekökünü alıyoruz ve bunu **result** değişkenine atıyoruz.

    console.log(result);
**result** değişkenine atamış olduğumuz yeni dizimizi konsola yazdırıyoruz,

    $ [ 2, 3, 4, 5 ]
 sonuç olarak ise **numbers** dizimizdeki değerlerin karekökü alınmış bir şekilde olduğunu görüyoruz.
 - - -
 Konuyu özetleyecek olursam, .map() fonksiyonunu diziler üzerinde sıklıkla kullanıyoruz. Bu örnekleri farklı şekilde yapmak mümkün fakat .map() fonksiyonu bize daha hızlı ve az kod yazmamızı sağlıyor. Bu yüzden JavaScript'in yeni özelliklerini takip etmek gerekiyor.
