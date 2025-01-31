# KLU Campus

KLU Campus, Kırklareli Üniversitesi öğrencileri için geliştirilmiş bir mobil uygulamadır.

## Özellikler

- 📱 Mesajlaşma ve Sosyal Etkileşim
- 📚 İkinci El Kitap Alışverişi
- 👤 Profil Yönetimi
- 🍽️ Yemek Listesi ve Değerlendirme

## Teknolojiler

- React Native
- Expo
- Node.js
- MySQL
- Express.js

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/[kullanıcı-adınız]/kluCampus.git
```

2. Proje dizinine gidin:
```bash
cd kluCampus
```

3. Gerekli paketleri yükleyin:
```bash
npm install
```

4. Backend için gerekli paketleri yükleyin:
```bash
cd backend
npm install
```

5. MySQL veritabanını kurun:
- MySQL Server'ı yükleyin
- `backend/config/database.sql` dosyasındaki SQL komutlarını çalıştırın

6. Backend için .env dosyasını oluşturun:
```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=klucampus
```

7. Uygulamayı başlatın:
```bash
# Ana dizinde
npm start

# Backend için (farklı bir terminal)
cd backend
npm start
```

## Katkıda Bulunma

1. Bu depoyu fork edin
2. Feature branch'i oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add some amazing feature'`)
4. Branch'inize push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.
