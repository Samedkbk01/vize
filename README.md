Yapay Zeka Destekli El Tespiti ve Ekran Parlaklık Ayarlama Projesi
Bu proje, MediaPipe kütüphanesini kullanarak elleri tespit eder ve parmaklar arasındaki mesafeye göre ekran parlaklığını ayarlar. Proje, aynı zamanda sağ ve sol elleri tanıyıp, tespit edilen elle ilgili bilgileri ekranda gösterir.

Gereksinimler
Projenin çalışabilmesi için aşağıdaki yazılım ve kütüphanelerin bilgisayarınızda yüklü olması gerekmektedir:

Python (versiyon 3.6 ve üzeri)

OpenCV: Görüntü işleme için

MediaPipe: El tespiti için

Screen Brightness Control (sbc): Ekran parlaklığını kontrol etmek için

Kütüphanelerin Kurulumu
Aşağıdaki komutları kullanarak gerekli Python kütüphanelerini kurabilirsiniz:
pip install opencv-python mediapipe screen-brightness-control numpy

Proje Dosyaları
main.py: El tespiti ve parlaklık ayarlamaları yapan ana Python dosyası.

hand_landmarker.task: MediaPipe model dosyası (el tespiti için).

README.md: Projenin kurulumu ve kullanımı hakkında bilgi.

requirements.txt: Gerekli Python paketlerini içeren dosya (isteğe bağlı).

Projenin Çalıştırılması
Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz.

1. Proje Klasörüne Git
Proje dosyalarını içeren klasöre gidin.

2. Model Dosyasını İndirin
Projede kullanılan hand_landmarker.task model dosyasını buradan indir veya MediaPipe'in resmi GitHub sayfasından erişebilirsiniz. Model dosyasını projenin ana dizinine koyduğunuzdan emin olun.

3. Kamerayı ve Ekran Parlaklığını Kontrol Etme
Proje, bilgisayarınızdaki kamera ve ekran parlaklığını kullanacaktır. Kamera ve parlaklık kontrolü için uygun izinlerin verilmiş olması gerekmektedir.

4. Projenin Başlatılması
proje başlatılır ve bilgisayarınızın kamerasından canlı görüntü alır. Görüntü üzerinde el tespiti yapılır ve parmaklar arasındaki mesafe ile ekran parlaklığı ayarlanır.

5. Programdan Çıkmak
Programdan çıkmak için herhangi bir tuşa basın veya Q tuşuna basarak çıkabilirsiniz.
