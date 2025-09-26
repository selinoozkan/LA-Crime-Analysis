# 📊 LA Crime Analysis (2020–2023)

Bu proje, **Los Angeles suç verilerinin (2020–2023)** zamansal ve mekânsal dağılımlarını analiz etmeyi amaçlamaktadır.  
Veri seti Kaggle’dan alınmıştır: [Los Angeles Crime Data (2020–2023)](https://www.kaggle.com/datasets/venkatsairo4899/los-angeles-crime-data-2020-2023)

---

## 🎯 Proje Hedefleri
- En sık işlenen suçların belirlenmesi  
- Suçların zamana göre dağılımı (yıl, ay, gün, saat)  
- Mekânsal suç yoğunluklarının incelenmesi  
- Mağdur profili analizi  
- **Anomali Tespiti:** Isolation Forest  
- **Tahminleme:** Lineer Regresyon  
- **Sınıflandırma:** Random Forest Classifier  

---

## 🛠️ Kullanılan Araçlar
- **Python** → Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Folium** → Harita tabanlı analiz  
- **Jupyter Notebook** → Kodlama ve görselleştirme  
- **PowerPoint / Word** → Sunum ve raporlama  

---

## 📊 Bulgular
- **En sık suçlar:** Araç hırsızlığı, basit saldırı, kimlik hırsızlığı  
- **Zaman analizi:**  
  - 2022’de suç sayısı zirve yaptı, 2023’te düşüş gözlendi  
  - Cuma ve Cumartesi günleri yoğun  
  - Öğle ve akşam saatleri suçların arttığı zaman dilimleri  
- **Mekânsal bulgular:** Central ve 77th Street bölgeleri riskli  
- **Modelleme:**  
  - Lineer regresyon düşük başarı (R² ≈ 0.08)  
  - Random Forest sınıflandırma ≈ %64 doğruluk  

---

## 📂 Proje Dosyaları
- `crime_analysis.ipynb` → Python analiz dosyası  
- `Crime_Data_from_2020_to_Present.csv` → Suç verisi (CSV, 180+ MB, `.gitignore` ile hariç tutuldu)  
- `LA_Crime_sunum.pptx` → Sunum dosyası  
- `VERİ MADENCİLİĞİNE GİRİŞ DÖNEM ÖDEVİ.docx` → Ödev raporu  
- `EKLER/` → Haritalar ve grafikler  

---

## 📌 Sonuç ve Öneriler
- **Suç analizi**, zamansal ve mekânsal boyutlarıyla önemli içgörüler sağlamaktadır.  
- Görsel analizler güçlü desenler ortaya koymuştur.  
- Makine öğrenmesi yöntemleri:  
  - Regresyon → düşük performans  
  - Random Forest → daha başarılı sınıflandırma  
- İlerleyen çalışmalarda **sosyoekonomik faktörler** ve **daha güçlü ML algoritmaları** dahil edilebilir.  

---

👩‍🎓 **Hazırlayanlar**  
- Selin Özkan – 24023652  
- Şükrü Kaan Özcan – 24023650  

📚 **Dersi Veren:** Prof. Dr. Ali Hakan Büyüklü  
📍 Yıldız Teknik Üniversitesi – İstatistik Bölümü (2024–2025)  
