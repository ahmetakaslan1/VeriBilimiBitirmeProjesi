# Veri Bilimi Bitirme Projesi

Bu repository, iki ayrı veri bilimi ödevini içeren bir "Bitirme Projesi" çalışmasını sunmaktadır. Projenin amacı, veri işleme (filtreleme, sıralama) ve veri görselleştirme becerilerini pratik uygulamalarla pekiştirmektir. Her bir ödev, farklı bir veri seti üzerinde belirli analiz ve görselleştirme hedefleri taşımaktadır.

---

## Ödev 1: Veri Filtreleme ve Sıralama Projesi

Bu ödev, veri setlerini belirli kriterlere göre filtreleme ve sıralama yeteneklerini geliştirmeye odaklanmıştır.

### 1.1 Veri Seti: `country.csv`

Bu veri seti, çeşitli ülkelerle ilgili geniş bir demografik, ekonomik ve coğrafi bilgi yelpazesi sunmaktadır. Temel sütunlar ve içerdikleri bilgiler şunlardır:

*   **Country:** Ülkenin adı.
*   **Region:** Ülkenin bulunduğu coğrafi bölge.
*   **Population:** Ülkenin toplam nüfusu.
*   **Area (sq. mi.):** Ülkenin yüzölçümü (mil kare cinsinden).
*   **Pop. Density (per sq. mi.):** Nüfus yoğunluğu.
*   **GDP ($ per capita):** Kişi başına düşen Gayri Safi Yurtiçi Hasıla (GSYİH).
*   **Literacy (%):** Okur-yazarlık oranı.
*   Diğer birçok ekonomik ve sosyal gösterge.

### 1.2 Amaç ve Gerçekleştirilen İşlemler

Bu ödevde, `country.csv` veri seti üzerinde aşağıdaki veri manipülasyonu ve analiz görevleri gerçekleştirilmiştir:

*   Nüfusa göre ülkeleri azalan sırada sıralama.
*   Kişi başına düşen GSYİH'ye göre ülkeleri artan sırada sıralama.
*   Nüfusu belirli bir eşiğin (10 milyon) üzerinde olan ülkeleri filtreleme.
*   Okur-yazarlık oranına göre en yüksek ilk 5 ülkeyi belirleme.
*   Kişi başına düşen GSYİH'si belirli bir eşiğin (10.000 $) üzerinde olan ülkeleri filtreleme.
*   Nüfus yoğunluğuna göre en yüksek ilk 10 ülkeyi belirleme.

Bu işlemler, veri setinden belirli bilgileri çekmek, karşılaştırmalar yapmak ve genel eğilimleri keşfetmek için temel veri analizi becerilerini kullanmayı sağlamıştır.

---

## Ödev 2: Veri Görselleştirme Ödevi

Bu ödev, finansal verilerin etkili görselleştirme teknikleri kullanarak analiz edilmesine odaklanmıştır.

### 2.1 Veri Seti: `50_Startups.csv`

Bu veri seti, 50 farklı startup şirketinin çeşitli harcamalarını ve kârlılıklarını içeren finansal verileri barındırmaktadır. Temel sütunlar ve içerdikleri bilgiler şunlardır:

*   **R&D Spend:** Şirketin araştırma ve geliştirme (Ar-Ge) harcamaları.
*   **Administration:** Yönetim giderleri.
*   **Marketing Spend:** Pazarlama harcamaları.
*   **State:** Şirketin faaliyet gösterdiği eyalet.
*   **Profit:** Şirketin elde ettiği toplam kâr.

### 2.2 Amaç ve Gerçekleştirilen İşlemler

Bu ödevde, `50_Startups.csv` veri seti üzerinde aşağıdaki veri görselleştirme görevleri gerçekleştirilmiştir:

*   **R&D Harcaması ve Kâr Arasındaki İlişki (Dağılım Grafiği - Scatter Plot):** Ar-Ge harcamalarının kâr üzerindeki etkisini görsel olarak analiz etmek.
*   **Yönetim Harcamaları ve Kâr Arasındaki İlişki (Dağılım Grafiği - Scatter Plot):** Yönetim giderlerinin kâr üzerindeki potansiyel etkisini incelemek.
*   **Eyaletlere Göre Ortalama Kâr (Çubuk Grafik - Bar Chart):** Farklı eyaletlerdeki startup'ların ortalama kârlılıklarını karşılaştırmak.
*   **Harcama Türlerinin Karşılaştırması (Kutu Grafiği - Boxplot):** Ar-Ge, yönetim ve pazarlama harcamalarının dağılımlarını ve merkezi eğilimlerini karşılaştırmak.

Bu görselleştirmeler, veri setindeki ilişkileri, eğilimleri ve farklı kategoriler arasındaki varyasyonları daha anlaşılır bir şekilde sunarak, iş kararları için değerli içgörüler sağlamayı amaçlamıştır.
