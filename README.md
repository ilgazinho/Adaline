# Adaline (Ünitesi Öğrenme Kuralı) Örnek Çalışması

## Adaline Ünitesi Nedir?
Adaline ünitesi en küçük kareler yönetimini kullanarak öğrenme gerçekleştirir. Perseptron algoritmasına çok benzemektedir.
Bu algoritmanın performansı Zeidler tarafından incelenmiştir.
## Örnek Kullanımı

```c#
public void Hesaplamalar()
```
Ağ tarafından doğru sınıflandırma oluşana kadar çalışan NetHesaplama fonksiyonun tetiklendiği fonksiyondur.

```c#
public void RandomOlustur()
```
Random olarak Ağırlıkları oluşturma fonksiyonudur.

```c#
        public int NetHesaplama(int ornekNo, int iterasyon, double x1, double x2, double w1, double w2, double esik, double ogrenme, double beklenen)
```
Net değerinin hesaplandıktan sonra çıktı ve beklenen değer eşleşmesi olmaması durumunda ağırlık değerlerinde değişimlerin yapıldığı fonksiyondur.
