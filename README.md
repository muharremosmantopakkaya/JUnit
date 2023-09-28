# JUnitNumberUtilitiesLibrary

Bu kütüphane, çeşitli sayısal işlemleri kolaylaştırmak için bir dizi yardımcı fonksiyon içermektedir. 
Bu işlevler, asal sayıların tespiti, faktöriyel hesaplama, rakam toplamları ve daha pek çok sayısal işlemi içerir.

## Özellikler

- Asal sayıların tespiti (`isPrime`).
- n'inci asal sayıyı bulma (`getPrime`).
- Bir sayının faktöriyelini hesaplama (`factorial`).
- Bir sayının rakamlarının toplamını bulma (`digitsSum`).
- Bir sayının rakamlarını bir dizi olarak alma (`getDigits`).
- Sayının tersini alma (`reversed`).
- Asal çarpanları yazdırma (`printPrimeFactors`).


## Testler

Projede bir dizi JUnit testi bulunmaktadır. Bu testler, kütüphanenin doğru bir şekilde çalıştığını doğrulamak için tasarlanmıştır.

- `Test_digitsSum`
- `Test_factorial`
- `Test_getDigits`
- `Test_getPrime`
- `Test_getPrime_exception`
- `Test_isPrime`
- `Test_isPrime_false`
- `Test_isPrime_true`

## Kurulum ve Kullanım

1. Projeyi Klonlama
Yerel makinenize projeyi klonlamak için aşağıdaki komutu kullanın:

bash
Copy code
git clone https://github.com/muharremosmantopakkaya/JUnitNumberUtilitiesLibrary.git
2. Bağımlılıkları Yükleme
Eğer Maven kullanıyorsanız, projedeki bağımlılıkları yüklemek için:

bash
Copy code
mvn install
Eğer Gradle kullanıyorsanız, aşağıdaki komutla bağımlılıkları yükleyin (bu adımı projenizde Gradle kullanılıyorsa ekleyin):

bash
Copy code
gradle build

3. Belgeler ve Örnekler
Projeyi en iyi şekilde kullanabilmek için belgelere ve örnek kodlara göz atın.
