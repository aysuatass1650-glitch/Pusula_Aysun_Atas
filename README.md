# Pusula_Aysun_Atas
# Talent Proje - Veri Bilimi

## Proje Açıklaması
Bu proje, hastalara ait verilerin analizi ve ön işlenmesi üzerine hazırlanmıştır. 
Amaç, veri temizleme, eksik değerleri doldurma, sayısal ve kategorik değişkenlerin işlenmesi
ve makine öğrenmesi modelleri için hazır veri seti oluşturulmasıdır.

## Veri Seti
- Toplam kayıt sayısı: 2235
- Sütunlar: HastaNo, Yas, Cinsiyet, KanGrubu, Uyruk, KronikHastalik, Bolum, Alerji, Tanilar, TedaviAdi, TedaviSuresi_SEANS, UygulamaYerleri, UygulamaSuresi_DK

## Veri Ön İşleme
- Eksik değerler uygun stratejilerle dolduruldu
- Kategorik değişkenler encoding ile işlenmiştir
- Sayısal değişkenler standartlaştırılmıştır

## Kullanılan Teknolojiler
- Python 3.x
- Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- Jupyter Notebook

## Çıktılar
- Temizlenmiş ve modellemeye hazır veri seti
- Görselleştirmeler: Histogram, Bar Plot, Yoğunluk Grafiği

## Kullanım
```bash
# Gerekli kütüphaneleri yükle
pip install -r requirements.txt

# Jupyter Notebook'u çalıştır
jupyter notebook notebooks/EDA_case_study.ipynb 
