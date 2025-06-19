# Altın Vadeli Fiyatları Analizi (2024–2025)

Bu proje, 19 Haziran 2024 - 19 Haziran 2025 tarihleri arasındaki **gerçek altın vadeli işlem verilerini** kullanarak altın fiyatlarındaki trendleri analiz etmektedir.

## Projenin Amacı

- Altın fiyatlarının zaman içindeki değişimini gözlemlemek  
- Teknik analizde kullanılan **hareketli ortalama** yöntemini uygulamak  
- Fiyat grafiklerini etkili bir şekilde görselleştirerek eğilimleri belirlemek

## Kullanılan Veriler

- Kaynak: [Investing.com](https://www.investing.com)
- Veriler `.csv` dosyası olarak alınmıştır.
- Sütunlar: `Date`, `Price`, `Open`, `High`, `Low`, `Vol.`, `Change %`

## Kullanılan Yöntemler

- **Pandas** ile veri işleme  
- **Matplotlib** ile çizgi grafiği  
- 20 günlük ve 50 günlük hareketli ortalama hesaplamaları  
- Grafik renklendirme ve çizgi kalınlığı ayarlamaları  

## Çıktılar

- Günlük fiyat trendi (pembe çizgi)
- 20 günlük hareketli ortalama (mor çizgi)
- 50 günlük hareketli ortalama (mavi çizgi)

## Kullanılan Teknolojiler

- Python  
- Jupyter Notebook  
- pandas, matplotlib

## Nasıl Çalıştırılır?

```bash
pip install pandas matplotlib
