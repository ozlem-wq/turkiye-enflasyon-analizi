# 📈 Türkiye Politika Faizi vs. Yıllık Enflasyon Analizi (2005 - 2025)

Bu proje, Türkiye Cumhuriyeti Merkez Bankası (TCMB) politika faiz oranları ile Türkiye İstatistik Kurumu (TÜİK) tarafından açıklanan Tüketici Fiyat Endeksi (TÜFE) yıllık değişim oranları arasındaki tarihsel ilişkiyi inceleyen bir zaman serisi analizidir.

Amacı, para politikasının (Faiz) fiyat istikrarı (Enflasyon) üzerindeki etkisini görselleştirmek ve reel faiz durumunu analiz etmektir.

---

## 🔍 Temel Bulgular

Projenin analizi, zaman serisi grafiği üzerinden aşağıdaki temel ekonomik bulguları ortaya koymaktadır:

* **Denge Dönemi (2005-2015):** Bu dönemde faiz oranları genellikle enflasyonun üzerinde tutularak piyasada **pozitif reel faiz** sağlanmış ve enflasyon kontrol altında kalmıştır.
* **Volatilite ve Negatif Reel Faiz (2018 Sonrası):** Faiz ve enflasyon çizgileri arasında büyük bir makas açılmıştır. Politika Faizi'nin enflasyonun çok altında kaldığı (Negatif Reel Faiz) uzun dönemler gözlemlenmiştir.
* **Korelasyon:** İki değişken arasında pozitif bir trend korelasyonu mevcuttur; ancak faiz kararlarının sıklıkla enflasyon zirvelerini **gecikmeli olarak takip etme** eğilimi gösterdiği görülmüştür.

---

## 🛠️ Proje Yapısı ve Metodoloji

### Veri Kaynakları

| Veri Seti | Kaynak | Veri Tipi |
| :--- | :--- | :--- |
| Politika Faizi | TCMB Veri Dağıtım Sistemi | Günlük Zaman Serisi |
| Yıllık Enflasyon (TÜFE) | TÜİK/TCMB | Aylık Zaman Serisi |

### Analiz Metodolojisi

Proje, temel olarak Python ve Pandas kütüphaneleri kullanılarak tek bir Jupyter Notebook'ta yürütülmüştür. Tüm kodlar, temizlenmiş ve tek tuşla çalışır hale getirilmiştir.

---

## 🚀 Çalıştırma Talimatları

Projeyi yerel bilgisayarınızda çalıştırmak için:

1.  Bu depoyu klonlayın (`git clone [REPO_LINK]`).
2.  Gerekli kütüphaneleri kurun: `pip install pandas numpy matplotlib seaborn`
3.  `notebooks/01_veri_toplama_ve_duzenleme.ipynb` dosyasını Jupyter Notebook ile açın ve **tüm hücreleri çalıştırın.**

Grafik çıktısı, **`figures/faiz_enflasyon_karsilastirma.png`** yolunda otomatik olarak oluşacaktır.

