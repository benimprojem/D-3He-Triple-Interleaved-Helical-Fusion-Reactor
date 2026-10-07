# D–³He ÜÇLÜ İÇ İÇE HELİSEL FÜZYON REAKTÖRÜ
## Ön Tasarım ve Fizibilite Raporu v1.0

**Doküman türü:** Teknik Ön Fizibilite  
**Tasarım durumu:** Konsept / Ön Mühendislik  
**Yakıt çevrimi:** D–³He  
**Plazma mimarisi:** Üç bağımsız, kapalı, iç içe geçmiş helisel plazma hattı  
**Referans tasarım:** 3 × 20 tur helis  
**Durum:** Ön hesaplama ve doğrulama aşaması

---

# 0. RAPORUN AMACI VE KAPSAMI

Bu rapor, kapalı çevrimli D–³He füzyon plazmasının üç adet bağımsız helisel kanalda dolaştırıldığı, her heliste iki adet lokal daralma/füzyon boğazı bulunan yeni nesil bir füzyon reaktörü konseptinin ön fizibilitesini tanımlar.

Tasarımın temel yaklaşımı:

- Üç ayrı kapalı plazma hattı kullanmak,
- Hatları aynı eksen etrafında 120° faz farkıyla yerleştirmek,
- Normal plazma hattını yaklaşık 10 cm çapında tutmak,
- Belirli bölgelerde hattı 5 cm çapa kadar kontrollü olarak daraltmak,
- Daralma bölgesinde daha yüksek RF elektromanyetik güç ve alan kontrolü kullanmak,
- Harici manyetik alan ile plazmayı duvarlardan uzak tutmak,
- RF, manyetik ve geometrik etkileri birlikte kullanarak plazma yoğunluğu ve enerjisinde lokal artış oluşturmak,
- Plazmayı kapalı çevrim içinde sürekli dolaştırmak.

Bu belge **çalışan bir füzyon reaktörünün kanıtı değildir**.

Özellikle;

- plazma kararlılığı,
- RF-plazma kuplajı,
- gerçek sıkıştırma oranı,
- enerji kayıpları,
- manyetik alan gereksinimi,
- füzyon güç yoğunluğu,
- net enerji kazancı

henüz deneysel veya yüksek doğruluklu sayısal modelleme ile doğrulanmamıştır.

Bu nedenle rapordaki geometrik sonuçlar **ön tasarım değerleri** olarak değerlendirilmelidir.

---

# 1. GEOMETRİK MİMARİ

## 1.1 Üçlü helis yapısı

Reaktörün temel plazma yapısı üç adet aynı geometrik özelliklere sahip helisel plazma hattından oluşur.

Her hat:

- içi boş bir plazma tüpüdür,
- yaklaşık 10 cm nominal çapa sahiptir,
- aynı eksen etrafında sarılır,
- 20 tam tur içerir,
- kendi başlangıç ve bitiş noktaları birleştirilerek kapalı çevrim oluşturur.

Üç helis:

$$\[
\phi_A=0^\circ
\]$$

$$\[
\phi_B=120^\circ
\]$$

$$\[
\phi_C=240^\circ
\]$$

fazlarıyla yerleştirilir.

Böylece herhangi bir enine kesitte üç helisin merkezleri yaklaşık eşkenar üçgen oluşturur.

---

## 1.2 Merkez bölgesi

Tasarımın önemli bir geometrik kuralı:

> **Merkezde hiçbir fiziksel silindir, çekirdek, plazma hattı veya taşıyıcı mandrel bulunmaz.**

Merkez bölgesi boş uzaydır.

Dolayısıyla yapı:

```text
             Helis A
                ●
               / \
              /   \
             /     \
        ●---/-------\---●
     Helis B           Helis C

        Merkez = BOŞ
```

şeklinde düşünülmelidir.

Bu üç helis birbirinin çevresinde dolaşan üç ayrı hat oluşturur.

---

## 1.3 Tüp çapı

Referans plazma tüpü çapı:

$$\[
D_t=10\text{ cm}
\]$$

Dolayısıyla yarıçap:

$$\[
r_t=5\text{ cm}
\]$$

Kesit alanı:

$$\[
A_{10}=\pi(0.05)^2
\]$$

$$\[
A_{10}\approx7.854\times10^{-3}\text{ m}^2
\]$$

---

# 2. ÜÇ HELİS OPTİMİZASYONU

Üç helisin birbirinden uzaklığı yeni tasarımın önemli avantajlarından biridir.

Önceki tek helis yaklaşımındaki yaklaşık 10 cm komşu boşluk yerine:

$$\[
60-70\text{ cm}
\]$$

net boşluk hedeflenmektedir.

Tüp çapı 10 cm olduğundan merkezden merkeze mesafe:

$$\[
d_c=70-80\text{ cm}
\]$$

olur.

Üç merkez eşkenar üçgen oluşturduğu için:

$$\[
d_c=\sqrt3R
\]$$

Buradan:

$$\[
R=\frac{d_c}{\sqrt3}
\]$$

elde edilir.

### Geometrik aralık

| Net boşluk | Merkezler arası | Helis yarıçapı | Helis çapı |
|---:|---:|---:|---:|
| 60 cm | 70 cm | 40.4 cm | 80.8 cm |
| 65 cm | 75 cm | 43.3 cm | 86.6 cm |
| 70 cm | 80 cm | 46.2 cm | 92.4 cm |

### Referans değer

Ön tasarım için:

$$\[
\boxed{R=43.3\text{ cm}}
\]$$

ve

$$\[
\boxed{d_c=75\text{ cm}}
\]$$

alınabilir.

Böylece net tüp boşluğu:

$$\[
75-10=65\text{ cm}
\]$$

olur.

Bu değer 60–70 cm hedef aralığının tam ortasına yakındır.

---

# 3. PITCH / YARIÇAP / TÜP ARALIĞI OPTİMİZASYONU

Helisin geometrisini belirleyen temel parametreler:

- Helis yarıçapı \(R\)
- Pitch \(p\)
- Tur sayısı \(N\)
- Tüp çapı
- Komşu helisler arasındaki boşluk

Bir helis turunun merkez çizgisi uzunluğu:

$$\[
L_1=
\sqrt{(2\pi R)^2+p^2}
\]$$

Referans değer:

$$\[
R=0.433\text{ m}
\]$$

$$\[
p=0.30\text{ m}
\]$$

olduğunda:

$$\[
L_1\approx2.74\text{ m}
\]$$

20 tur için:

$$\[
L_{20}\approx54.8\text{ m}
\]$$

olur.

Üç helisin toplam plazma yolu:

$$\[
L_{total}=3L_{20}
\]$$

$$\[
L_{total}\approx164.4\text{ m}
\]$$

---

## 3.1 Fiziksel reaktör uzunluğu

Pitch:

$$\[
p=30\text{ cm}
\]$$

ve tur sayısı:

$$\[
N=20
\]$$

olduğundan eksenel yükseklik:

$$\[
H=Np
\]$$

$$\[
H=20(0.30)
\]$$

$$\[
\boxed{H=6.0\text{ m}}
\]$$

Burada önemli ayrım:

**6 m**, reaktörün yaklaşık eksenel fiziksel boyudur.

**54.8 m**, bir helisin plazma yoludur.

**164.4 m**, üç helisin toplam plazma yoludur.

Dolayısıyla üçlü sistem fiziksel olarak yaklaşık 6 m yüksekliğinde olabilirken toplam plazma yolu 164 m seviyesine çıkabilir.

Bu iki uzunluk birbirine karıştırılmamalıdır.

---

## 3.2 Pitch taraması

Aşağıdaki pitch değerleri ayrı ayrı incelenmelidir:

$$\[
p=20,\ 25,\ 30,\ 35,\ 40\text{ cm}
\]$$

Optimizasyon kriterleri:

1. Fiziksel boyut
2. Helis eğim açısı
3. Manyetik alan geometrisi
4. RF kuplajı
5. Komşu tur etkileşimi
6. Boğaz yerleşimi
7. Termal yük dağılımı
8. İmalat toleransı
9. Plazma kararlılığı

Bu nedenle 30 cm pitch şimdilik **referans değer** olup nihai değer değildir.

---

# 4. MANYETİK ALAN ETKİLEŞİMİ

Plazmanın reaktör duvarlarına temas etmemesi temel tasarım koşuludur.

Manyetik sistem:

- plazmayı kapalı yörüngede tutmalı,
- radyal kaçışı azaltmalı,
- boğaz bölgelerinde kararlılığı korumalı,
- helisel geometrinin oluşturduğu alan bileşenleriyle uyumlu çalışmalıdır.

---

## 4.1 Boğaz alan ölçeği

10 cm çap:

$$\[
A_{10}=\pi(5\text{ cm})^2
\]$$

5 cm çap:

$$\[
A_5=\pi(2.5\text{ cm})^2
\]$$

Dolayısıyla:

$$\[
\frac{A_{10}}{A_5}=4
\]$$

İdeal manyetik akı korunumu varsayılırsa:

$$\[
BA=\text{const.}
\]$$

olduğundan:

$$\[
\frac{B_5}{B_{10}}\approx4
\]$$

Bu yalnızca **ideal ölçekleme** olarak kullanılmalıdır.

Gerçek plazmada:

- basınç,
- sıcaklık,
- beta,
- manyetik geometri,
- parçacık yörüngeleri,
- MHD kararsızlıkları

nedeniyle gerçek oran farklı olabilir.

---

# 5. 5 CM BOĞAZ YERLEŞİMİ

Her heliste iki adet lokal daralma bölgesi bulunacaktır.

Geometri:

$$\[
10\text{ cm}\rightarrow5\text{ cm}\rightarrow10\text{ cm}
\]$$

şeklindedir.

Keskin bir geometrik basamak kullanılmamalıdır.

---

## 5.1 Referans boğaz geometrisi

Yaklaşık:

- 20 cm giriş geçişi
- 40 cm düz 5 cm bölüm
- 20 cm çıkış geçişi

alınabilir.

Toplam:

$$\[
L_{throat}\approx80\text{ cm}
\]$$

Bu değer başlangıç tasarımıdır.

Gerçek geçiş profili daha sonra MHD ve plazma kayıplarına göre optimize edilmelidir.

---

## 5.2 Boğaz sayısı

Her heliste:

$$\[
2
\]$$

boğaz.

Üç heliste:

$$\[
3\times2=6
\]$$

boğaz.

Dolayısıyla tüm reaktörde toplam:

$$\[
\boxed{6\text{ boğaz}}
\]$$

bulunur.

---

# 6. NORMAL BÖLGELERDE RF — 6 KANAL

Her helisin normal 10 cm bölgesinde:

$$\[
2
\]$$

RF kanalı bulunur.

Üç helis için:

$$\[
3\times2=6
\]$$

RF kanalı.

Dolayısıyla normal bölgelerde toplam:

$$\[
\boxed{6\text{ RF kanalı}}
\]$$

bulunur.

Her kanal:

- bağımsız güç kontrolü,
- bağımsız faz kontrolü,
- frekans kontrolü,
- ileri güç ölçümü,
- geri/yansıyan güç ölçümü

yapabilmelidir.

---

# 7. BOĞAZ BÖLGELERİNDE RF — 12 KANAL

Her 5 cm boğaz bölgesinde:

$$\[
4
\]$$

RF kanalı bulunur.

Üç helis:

$$\[
3\times4=12
\]$$

Dolayısıyla boğaz bölgelerinde toplam:

$$\[
\boxed{12\text{ RF kanalı}}
\]$$

bulunur.

---

## 7.1 Dört RF kanalının anlamı

Dört RF kanalı:

> otomatik olarak dört kat sıkıştırma kuvveti anlamına gelmez.

Dört kanalın avantajları:

- daha yüksek toplam RF gücü,
- daha simetrik elektromanyetik alan,
- daha fazla faz kontrolü,
- farklı modların denenebilmesi,
- plazma-RF kuplajının optimize edilebilmesi.

Örneğin her normal kanal \(P_0\) gücünde ise:

Normal:

$$\[
P_N=2P_0
\]$$

Boğaz:

$$\[
P_T=4P_0
\]$$

olur.

Bu durumda boğazdaki toplam RF gücü normal bölgenin:

$$\[
\frac{4P_0}{2P_0}=2
\]$$

katıdır.

Ancak gerçek plazma sıkıştırması, yalnızca RF kanal sayısından hesaplanamaz.

---

# 8. RF FAZ SENKRONİZASYONU

RF sisteminin en kritik noktalarından biri faz kontrolüdür.

Tüm RF kaynakları ortak bir referans saatine kilitlenmelidir.

Her kanal için:

$$\[
P_i
\]$$

$$\[
f_i
\]$$

$$\[
\phi_i
\]$$

bağımsız olarak kontrol edilebilmelidir.

Ölçülmesi gerekenler:

- ileri RF gücü,
- yansıyan RF gücü,
- faz,
- empedans,
- plazma yoğunluğu,
- plazma sıcaklığı.

---

## 8.1 RF eşleştirme

Plazma empedansı çalışma sırasında değişeceğinden sabit RF ayarı yeterli olmayabilir.

Bu nedenle:

- directional coupler,
- aktif matching,
- otomatik empedans ayarı

kullanılması önerilir.

Amaç:

$$\[
P_{absorbed}=P_{forward}-P_{reflected}
\]$$

büyüklüğünü maksimum ve kontrollü hale getirmektir.

---

# 9. PLAZMA AKIŞI VE HATLARIN BAĞIMSIZLIĞI

İlk tasarımda üç helis:

$$\[
A,\ B,\ C
\]$$

olarak ayrı plazma çevrimleri şeklinde değerlendirilmelidir.

Her biri kendi içinde kapalıdır.

Bu yaklaşımın avantajları:

- bağımsız kontrol,
- arıza izolasyonu,
- ayrı teşhis,
- farklı RF ayarlarının denenebilmesi,
- üç hattın deneysel karşılaştırılması.

Üç hat arasında fiziksel plazma bağlantısı bulunmaz.

Bununla birlikte elektromanyetik çapraz etkileşim olabilir.

Bu nedenle:

$$\[
\text{Helis A}\leftrightarrow\text{Helis B}\leftrightarrow\text{Helis C}
\]$$

alan etkileşimleri 3B modelde hesaplanmalıdır.

---

# 10. TERMAL SİSTEM

Reaktörün en kritik mühendislik sorunlarından biri ısı uzaklaştırmadır.

Isı kaynakları:

1. RF kayıpları
2. Plazma-duvar etkileşimi
3. Elektromanyetik kayıplar
4. Boğaz bölgesindeki lokal güç yoğunluğu
5. Yapısal iletim kayıpları
6. Füzyon ürünlerinden gelen enerji

olarak ayrı ayrı hesaplanmalıdır.

---

## 10.1 Boğaz termal yükü

5 cm bölgesinde:

- daha yüksek yoğunluk,
- daha yüksek RF gücü,
- daha yüksek manyetik alan,
- daha yüksek füzyon reaksiyon olasılığı

beklenmektedir.

Bu nedenle boğaz:

> termal açıdan reaktörün en kritik bölgelerinden biridir.

Duvar sıcaklığı sürekli ölçülmelidir.

---

# 11. SIVI METAL SİSTEMİ

Dış yapıda sıvı bizmut kullanılması konsept dahilinde değerlendirilebilir.

Sıvı bizmut:

- termal taşıyıcı,
- elektromanyetik çevre,
- radyasyon soğurucu/taşıyıcı yapı

olarak araştırılabilir.

Ancak:

$$\[
T_{melt,Bi}\approx271^\circ C
\]$$

olduğu için sistemin çalışma sıcaklığı dikkatle kontrol edilmelidir.

---

## 11.1 Plazma ile temas

Sıvı metal:

$$\[
\boxed{\text{plazma ile doğrudan temas etmemelidir}}
\]$$

Arada:

- seramik,
- vakum bölgesi,
- yapısal katman,
- elektromanyetik izolasyon

gibi uygun bariyerler bulunmalıdır.

---

## 11.2 MHD etkisi

Sıvı metal elektriksel olarak iletken olduğundan manyetik alan altında:

$$\[
\mathbf{J}\times\mathbf{B}
\]$$

kuvvetleri oluşabilir.

Bu nedenle sıvı metal akışı yalnızca termal CFD ile değil:

$$\[
\boxed{\text{MHD + termal akış}}
\]$$

olarak modellenmelidir.

---

# 12. MALZEMELER VE DİELEKTRİK SEÇİMİ

RF kanalları ile plazma arasında yüksek sıcaklığa dayanıklı dielektrik/seramik yapı gereklidir.

Malzeme seçim kriterleri:

- yüksek sıcaklık dayanımı,
- düşük RF kaybı,
- yüksek dielektrik kırılma alanı,
- düşük termal genleşme,
- yüksek termal iletkenlik,
- vakum uyumluluğu,
- radyasyon dayanımı,
- mekanik dayanım.

Özellikle boğaz bölgelerinde malzemenin RF alanı ve sıcaklık altında davranışı ayrıca test edilmelidir.

---

## 12.1 Sıvı altın

Sıvı altın RF iletkeni konsept olarak araştırılabilir.

Ancak:

- çok yüksek çalışma sıcaklığı,
- akışkan geometrinin kontrolü,
- RF empedansı,
- sızdırmazlık,
- pompalama,
- malzeme uyumluluğu

nedeniyle ilk prototip için tercih edilmesi zorunlu değildir.

Bu sistem sonraki deneysel aşamaya bırakılmalıdır.

---

# 13. TEŞHİS VE ÖLÇÜM SİSTEMİ

Reaktörün çalışıp çalışmadığını belirlemek için yalnızca toplam RF gücü ölçmek yeterli değildir.

Temel ölçümler:

### Plazma

- elektron sıcaklığı \(T_e\)
- iyon sıcaklığı \(T_i\)
- elektron yoğunluğu \(n_e\)
- iyon yoğunluğu
- plazma basıncı

### Manyetik alan

$$\[
B(x,y,z)
\]$$

### RF

- ileri güç
- yansıyan güç
- absorbe edilen güç
- faz
- frekans
- empedans

### Termal

- duvar sıcaklığı
- boğaz sıcaklığı
- sıvı metal sıcaklığı
- RF elemanı sıcaklığı

### Nükleer

D–³He reaksiyonuna ek olarak D-D yan reaksiyonları nedeniyle:

- nötron
- gama

ölçümleri de yapılmalıdır.

---

## 13.1 Temel doğrulama oranları

Boğazın çalıştığını göstermek için:

$$\[
R_n=\frac{n_5}{n_{10}}
\]$$

ve

$$\[
R_T=\frac{T_5}{T_{10}}
\]$$

tanımlanabilir.

İlk hedef:

$$\[
R_n>1
\]$$

ve:

$$\[
R_T>1
\]$$

olmasıdır.

İdeal geometrik sınır:

$$\[
R_n\approx4
\]$$

olarak referans alınabilir.

Ancak:

$$\[
R_n=4
\]$$

olması deneysel olarak zorunlu değildir.

---

# 14. PROTOTİP AŞAMALARI

Tam 20 turluk sistem doğrudan inşa edilmemelidir.

## Aşama 1 — Boğaz prototipi

Geometri:

$$\[
10\rightarrow5\rightarrow10\text{ cm}
\]$$

RF:

$$\[
4\text{ kanal}
\]$$

Amaç:

- RF kuplajı,
- plazma yoğunluğu,
- sıcaklık değişimi,
- boğaz kararlılığı.

---

## Aşama 2 — Manyetik sistem

Aşama 1 kontrollü manyetik alan altında tekrarlanır.

Ölçümler:

$$\[
n(x)
\]$$

$$\[
T(x)
\]$$

$$\[
B(x)
\]$$

---

## Aşama 3 — 1–2 tur

Kapalı helisel plazma çevrimi test edilir.

Amaç:

- plazmanın kapalı yolda dolaşımı,
- parçacık kayıpları,
- enerji kayıpları,
- RF senkronizasyonu.

---

## Aşama 4 — 5–10 tur

Çoklu RF kanalları devreye alınır.

Üçlü helis mimarisinin daha küçük ölçekli versiyonu test edilir.

---

## Aşama 5 — 20 tur

Ancak önceki aşamalar başarılı olursa:

$$\[
N=20
\]$$

tam geometriye geçilir.

---

# 15. FMEA / RİSK MATRİSİ

| Risk | Seviye | Ana neden | Önlem |
|---|---|---|---|
| Boğaz plazma kararsızlığı | Çok yüksek | Yoğunluk/alan gradyanı | MHD + deney |
| Plazma-duvar teması | Çok yüksek | Manyetik kaçış | Manyetik topoloji optimizasyonu |
| Kapalı çevrim taşınımı | Çok yüksek | Parçacık/enerji kaybı | Kısa çevrim prototipi |
| Isı uzaklaştırma | Çok yüksek | Lokal güç yoğunluğu | Ayrı termal çevrim |
| RF-plazma kuplajı | Yüksek | Empedans değişimi | Matching + ölçüm |
| RF arkı | Yüksek | Yüksek alan | Seramik izolasyon |
| RF yansıması | Yüksek | Empedans uyumsuzluğu | Directional coupler |
| Faz hatası | Yüksek | Kanal senkronizasyonu | Ortak referans |
| Boğaz duvar ısınması | Yüksek | Güç yoğunluğu | Termal model |
| Sıvı metal MHD | Orta/Yüksek | \(J\times B\) | MHD CFD |
| Termal genleşme | Orta | Sıcaklık farkları | Genleşme hesabı |
| Malzeme uyumsuzluğu | Orta | RF/ısı/radyasyon | Malzeme testi |

---

# 16. BAŞARI KRİTERLERİ

İlk başarı kriteri:

$$\[
\boxed{\text{Net füzyon gücü değildir}}
\]$$

İlk aşamada aşağıdaki sonuçlar gösterilmelidir.

### 16.1 Yoğunluk

$$\[
\boxed{\frac{n_5}{n_{10}}>1}
\]$$

### 16.2 Sıcaklık

$$\[
\boxed{\frac{T_5}{T_{10}}>1}
\]$$

### 16.3 RF

RF gücünün ölçülebilir ve tekrarlanabilir biçimde plazmaya aktarılması.

### 16.4 Faz kontrolü

RF faz değişikliğinin:

- yoğunluk,
- sıcaklık,
- RF soğurumu

üzerinde ölçülebilir etkisinin bulunması.

### 16.5 Boğazdan çıkış

5 cm bölgesinden çıkan plazmanın tekrar 10 cm kesite geçerken kararlı kalması.

### 16.6 Çoklu tur

Plazmanın tek geçiş yerine çoklu tur boyunca kabul edilebilir kayıplarla dolaşabilmesi.

---

# 17. NİHAİ 3B TASARIM PARAMETRELERİ

## 17.1 Referans parametre seti

| Parametre | Değer |
|---|---:|
| Helis sayısı | 3 |
| Helis fazları | 0° / 120° / 240° |
| Nominal tüp çapı | 10 cm |
| Net tüp boşluğu | 65 cm |
| Merkezler arası uzaklık | 75 cm |
| Helis yarıçapı | ≈43.3 cm |
| Helis çapı | ≈86.6 cm |
| Pitch | 30 cm |
| Tur sayısı | 20 |
| Eksenel yükseklik | 6.0 m |
| Bir tur yolu | ≈2.74 m |
| Tek helis yolu | ≈54.8 m |
| Üç helis toplam yolu | ≈164.4 m |
| Boğaz sayısı / helis | 2 |
| Toplam boğaz | 6 |
| Normal RF / helis | 2 |
| Toplam normal RF | 6 |
| Boğaz RF / helis | 4 |
| Toplam boğaz RF | 12 |
| Normal tüp çapı | 10 cm |
| Boğaz çapı | 5 cm |
| İdeal kesit alanı oranı | 4:1 |
| İdeal \(B_5/B_{10}\) ölçeği | ≈4 |
| Referans boğaz uzunluğu | ≈80 cm |

---

# 18. GENEL FİZİBİLİTE DEĞERLENDİRMESİ

Bu tasarımın en güçlü tarafı, üç helisin birbirinden oldukça uzak yerleştirilmesi sayesinde:

- RF sistemlerinin fiziksel yerleşiminin kolaylaşması,
- hatlar arası doğrudan mekanik etkileşimin azalması,
- her plazma hattının bağımsız test edilebilmesi,
- toplam aktif plazma hacminin artırılması,
- üç ayrı deneysel kanal oluşturulmasıdır.

Bunun karşılığında sistem:

- daha fazla RF kanalı,
- daha karmaşık manyetik alan,
- daha büyük toplam plazma yolu,
- daha fazla teşhis sistemi,
- daha karmaşık termal altyapı

gerektirecektir.

---

# 19. KRİTİK TEKNİK DOĞRULAMA SIRASI

Tasarımın bundan sonraki teknik geliştirme sırası:

### A.

$$\[
R,\ p,\ D,\ N
\]$$

parametrelerinin optimizasyonu.

### B.

10 → 5 → 10 cm boğaz geometrisinin 3B MHD analizi.

### C.

Boğazda:

$$\[
n(x),T(x),B(x)
\]$$

profillerinin hesaplanması.

### D.

RF elektromanyetik alan çözümü.

### E.

RF-plazma kuplaj modeli.

### F.

Üç helisin karşılıklı elektromanyetik etkileşim modeli.

### G.

Termal analiz.

### H.

Sıvı metal MHD analizi.

### I.

Plazma kayıp oranının hesaplanması.

### J.

D–³He füzyon reaksiyon hızının hesaplanması.

### K.

Füzyon güç yoğunluğu.

### L.

RF + manyetik sistem + termal sistem toplam enerji bütçesi.

### M.

Net enerji kazancı / kaybı.

---

# 20. RAPOR SONUCU

Mevcut referans geometri:

$$\[
\boxed{
3\text{ helis}
+
20\text{ tur}
+
R=43.3\text{ cm}
+
p=30\text{ cm}
+
D=10\text{ cm}
}
\]$$

şeklindedir.

Her helis:

$$\[
\boxed{54.8\text{ m}}
\]$$

plazma yoluna sahiptir.

Üç helisin toplamı:

$$\[
\boxed{164.4\text{ m}}
\]$$

olur.

Fiziksel eksenel yükseklik:

$$\[
\boxed{6.0\text{ m}}
\]$$

olur.

Her heliste:

$$\[
\boxed{2\text{ boğaz}}
\]$$

olmak üzere toplam:

$$\[
\boxed{6\text{ boğaz}}
\]$$

vardır.

RF sistemi:

$$\[
\boxed{6\text{ normal RF} + 12\text{ boğaz RF}}
\]$$

şeklindedir.

Bu değerler **nihai mühendislik tasarımı olarak dondurulmamıştır**.

Özellikle pitch ve helis yarıçapı, sonraki aşamada hesaplanarak optimize edilmelidir.

---

# 21. SONRAKİ HESAPLAMA AŞAMASI

Bir sonraki teknik çalışma doğrudan şu optimizasyon olacaktır:

$$\[
\boxed{
p=20,\ 25,\ 30,\ 35,\ 40\text{ cm}
}
\]$$

için;

- bir tur uzunluğu,
- 20 tur uzunluğu,
- eksenel yükseklik,
- helis açısı,
- üç helisin toplam plazma yolu,
- boğazların fiziksel yerleşimi,
- komşu tur mesafesi

hesaplanacak ve **en uygun pitch** seçilecektir.

Ardından seçilen geometri üzerine **5 cm boğazın gerçek yerleşimini ve iki boğaz arasındaki mesafeyi** hesaplayacağız.

---

## Tasarım statüsü

**v1.0 — Ön Fizibilite Referans Tasarımı**

Geometrik yapı tanımlanmıştır.  
RF mimarisi tanımlanmıştır.  
Manyetik sistem gereksinimi tanımlanmıştır.  
Termal ve sıvı metal sistemleri tanımlanmıştır.  
Teşhis ve prototip aşamaları tanımlanmıştır.  
Riskler tanımlanmıştır.

**Henüz doğrulanması gereken ana konular:**

1. 5 cm boğazda gerçek plazma kararlılığı
2. RF'nin gerçek sıkıştırma/enerji aktarım mekanizması
3. Üç helisin manyetik alan topolojisi
4. Kapalı çevrim plazma kayıpları
5. D–³He füzyon reaksiyon oranı
6. Toplam enerji bütçesi
7. Net enerji kazancı
