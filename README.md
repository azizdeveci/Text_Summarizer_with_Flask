# Metin Özetleyici Uygulaması

Bu uygulama, uzun metinleri otomatik olarak özetleyen bir web uygulamasıdır. Hem metin girişi hem de dosya yükleme özellikleri sunar.

## Özellikler

- Metin girişi ile özetleme
- Dosya yükleme ile özetleme
- Modern ve kullanıcı dostu arayüz
- Hızlı ve etkili özetleme

## Kurulum

1. Python'u bilgisayarınıza yükleyin (Python 3.7 veya üstü)
2. Gerekli paketleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

## Kullanım

1. Uygulamayı başlatın:
   ```bash
   python app.py
   ```
2. Tarayıcınızda `http://localhost:5000` adresine gidin
3. Metni doğrudan girebilir veya bir metin dosyası yükleyebilirsiniz
4. "Özetle" butonuna tıklayın
5. Özetlenmiş metin ekranda görüntülenecektir

## Teknik Detaylar

- Flask web framework'ü kullanılmıştır
- Metin özetleme için BART modeli kullanılmıştır
- Bootstrap ile modern bir arayüz tasarlanmıştır
- Asenkron JavaScript ile kullanıcı deneyimi iyileştirilmiştir

## Notlar

- İlk çalıştırmada model indirilecektir, bu biraz zaman alabilir
- Çok uzun metinler için işlem süresi artabilir
- En iyi sonuçlar için İngilizce metinler önerilir 