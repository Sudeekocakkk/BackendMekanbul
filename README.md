# Mekanbul Backend

*Demo:*https://backend-mekanbul-a719.vercel.app/

Bu repo mekanbul—backend uygulamasının basit Node.js + Express + Mongoose backend'idir.

## Kısa Açıklama

- API, mekan (venue) verilerini yönetir: listeleme, ekleme, görüntüleme, güncelleme ve silme.
- MongoDB Cloud kullanır. Bağlantı bilgisi için app_api/models/db.js dosyasına bakın.

## Kurulum
bash
cd /path/to/backend
npm install


## Uygulamayı Çalıştırma
bash
npm start



## API Endpoints

- *Tüm mekanları listele:* GET /api/venues
- *Yeni mekan ekle:* POST /api/venues
- *Mekan detayını getir:* GET /api/venues/:venueid
- *Mekanı güncelle:* PUT /api/venues/:venueid
- *Mekanı sil:* DELETE /api/venues/:venueid
- *Yorum ekle (mekana):* POST /api/venues/:venueid/comments
- *Yorum getir:* GET /api/venues/:venueid/comments/:commentid
- *Yorum güncelle:* PUT /api/venues/:venueid/comments/:commentid
- *Yorum sil:* DELETE /api/venues/:venueid/comments/:commentid

---

## Postman Test Sonuçları

Aşağıda Postman ile alınmış test sonuçlarının ekran görüntüleri bulunmaktadır:

![Açıklama](./tests/AddComment.png)
![Açıklama](./tests/AddVenue.png)
![Açıklama](./tests/DeleteComment.png)
![Açıklama](./tests/DeleteVenue.png)
![Açıklama](./tests/GetComment.png)
![Açıklama](./tests/GetVenue.png)
![Açıklama](./tests/ListNearbyVenues.png)
![Açıklama](./tests/UpdateComment.png)
![Açıklama](./tests/UpdateVenue.png)
