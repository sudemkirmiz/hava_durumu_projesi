##  Proje 2: Hava Durumu Veri Analizi

Bu depo, veri analizi öğrenim serisinin ikinci projesi olan Hava Durumu Veri Analizi projesine ait tüm kodları, veri setlerini, görselleri ve nihai rapor özetini içermektedir.

## Proje Amacı

Belirli bir şehrin (Münih) günlük hava durumu verilerini analiz ederek; iklimsel trendleri, mevsimsel kalıpları ve aykırı hava olaylarını tespit etmek amaçlanmıştır.

## Kullanılan Teknolojiler

* **Programlama Dili:** Python
* **Temel Kütüphaneler:** Pandas, Numpy, Matplotlib
* **Sürüm Kontrolü:** Git & GitHub

## Analiz Özeti ve Temel Çıktılar

Analiz sırasında veri temizliği, Keşifsel Veri Analizi (EDA) ve görselleştirme adımları uygulanmıştır.

### Öne Çıkan Bulgular:

1.  **En Yağışlı Dönem:** Günlük ortalama 5.83 mm yağış ile **Mayıs ayı** en yüksek ortalamaya sahiptir. Yağışlar bu dönemde zirveye ulaşmaktadır.
2.  **Aykırı Olay Tespiti:** Tek bir günde kaydedilen maksimum yağış miktarı **78.4 mm** olarak tespit edilmiştir (2024-06-01). Bu değer, altyapı planlaması için kritik bir üst limit olmalıdır.
3.  **Mevsimsel Trend:** Kar yağışı riski, **Nisan ayından sonra tamamen kesilmiştir**.
4.  **Veri Temizliği:** Eksik günlük yağış/kar yağışı değerleri, ölçüm yapılmadığı varsayımıyla sıfır (`0`) ile doldurulmuştur.

### Proje Dosyaları:

| Dosya Adı | Açıklama |
| :--- | :--- |
| `weather_analysis.ipynb` | Veri yükleme, temizlik, EDA ve görselleştirme adımlarının uygulandığı ana Python Notebook dosyası. |
| `weather_report.md` | Yönetime sunulan, bulguları ve önerileri özetleyen nihai rapor. |
| `aylik_yagis_trend.png` | Aylık ortalama yağış ve kar yağışı trendini gösteren çizgi grafiği. |
| `aykiri_yagis_olayi.png` | En yüksek günlük yağış miktarını vurgulayan çubuk grafik. |
| `munich.csv` | Analiz için kullanılan ham veri seti. |

##  Projeyi Yerel Bilgisayarınıza Kopyalama (Clone)

Bu adımlar, projeyi kullanmaya başlamanız için gerekli olan tüm dosyaları bilgisayarınıza indirmenizi sağlar.

### Gereksinimler

Projemizi kopyalamak ve çalıştırmak için bilgisayarınızda **Git** programının kurulu olması gerekmektedir.

### Adım Adım Kopyalama (Cloning)

Projeyi bilgisayarınıza indirmek sadece tek bir komut gerektirir.

#### Adım 1: Komut Satırını Açın

Bilgisayarınızda bir **Terminal** (macOS/Linux) veya **Git Bash** / **Komut İstemi (CMD)** (Windows) uygulamasını açın.

#### Adım 2: Kopyalama Komutunu Çalıştırın

Açtığınız komut satırı penceresine aşağıdaki komutu aynen yapıştırın ve **Enter** tuşuna basın:

```bash
gh repo clone sudemkirmiz/hava_durumu_projesi
