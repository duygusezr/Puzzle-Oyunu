# **Puzzle Oyunu (Sliding Puzzle)**

Bu proje, klasik **15-Puzzle (Kaydırmalı Bulmaca)** oyununu temel alarak geliştirilmiştir. Oyunda, **5x5** boyutunda toplam **24 düğme (buton)** bulunmaktadır ve bunlar çalışma alanını kaplayacak şekilde rastgele dizilmiştir. **Oyuncunun amacı**, düğmeleri **1'den 24'e kadar sıralı hale** getirmek ve boş alanı en **altta sağ köşeye** getirmektir.

## **Özellikler**

- **Dinamik Kare Izgara**: 5x5 düzeninde 24 düğme ve bir boş alan içerir.  
- **Rastgele Başlangıç Dizilimi**: Oyun başladığında düğmeler rastgele karıştırılır.  
- **Geçerli Hareketler**: Yalnızca boş alanın **üst, alt, sol veya sağındaki** düğmeler hareket edebilir.  
- **Otomatik Kazanma Kontrolü**: Oyuncu, düğmeleri sıralı hale getirdiğinde oyunun tamamlandığını belirten bir mesaj görüntülenir.  
- **Dinamik Pencere Boyutlandırma (2. Versiyon)**:  
  - Pencere boyutlandırıldığında butonlar otomatik olarak yeniden ölçeklenir.  
  - Çalışma alanı kare olmak zorunda değildir, her boyutta uyum sağlar.  

## **Kullanım**

1. **Oyunu Başlatın**: Program çalıştırıldığında düğmeler rastgele sıralanmış şekilde başlar.  
2. **Düğmeleri Hareket Ettirin**: Bir düğmeye tıklayarak boş alanın olduğu yere taşıyabilirsiniz (yalnızca boş alanın komşularını).  
3. **Oyunu Tamamlayın**: Tüm düğmeleri 1'den 24'e doğru sıralayıp boş alanı en sağ alt köşeye getirerek oyunu kazanın.  

## **Ekran Görüntüleri**  
![puzzle](https://github.com/user-attachments/assets/0bb79867-167a-4f09-8c66-48c0facc713e)


## **Kurulum ve Çalıştırma**

Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **Depoyu Klonlayın**  
   ```bash
   git clone https://github.com/kullaniciadi/projeadi.git
   cd projeadi
   ```
2. **Projeyi Çalıştırın**  
   - Eğer **Python ve Tkinter** kullanıldıysa:  
     ```bash
     python main.py
     ```
   - Eğer **JavaFX** kullanıldıysa:  
     ```bash
     mvn clean javafx:run
     ```

## **Geliştirme ve Katkı**

Bu projeye katkıda bulunmak isterseniz:

1. **Fork** yapın.  
2. Yeni bir **branch** oluşturun:  
   ```bash
   git checkout -b yeni-ozellik
   ```
3. Değişiklikleri yapıp **commit** atın:  
   ```bash
   git commit -m "Yeni özellik eklendi"
   ```
4. **Push** edip **Pull Request (PR)** gönderin.  

---

