# 📊 Mağaza Satış Analizi Dashboardu

## 📌 Layihə Haqqında
Bu layihə ABC şirkətinin satış məlumatlarına əsaslanaraq hazırlanmış interaktiv Power BI dashboardudur. Dashboard iki əsas analiz istiqamətini əhatə edir: **ümumi satış performansı** və **regional satış analizi**.

Layihənin məqsədi şirkətin satış və mənfəət dinamikasını izləmək, məhsul və brend üzrə performansı qiymətləndirmək, həmçinin regional və kanal üzrə bölgünü vizual şəkildə təqdim etməkdir.

---

## 🛠 İstifadə Olunan Alətlər
- Power BI
- Microsoft Excel

---

## 🔄 İş Axını (Workflow)
- Məlumatların toplanması
- Data təmizlənməsi
- Data modelləşdirmə
- DAX ölçülərinin yaradılması
- Dashboard dizaynı
- İnteraktiv funksiyaların tətbiqi (filter, slicer, page navigation)

---

## 📊 Dashboard Baxışı

### 🔹 Səhifə 1 — İlkin Analiz

Bu səhifə şirkətin ümumi satış performansını bir baxışda təqdim edir. Yuxarıdakı KPI kartları, zaman üzrə trendlər, məhsul/brend/kateqoriya üzrə müqayisələr və sol tərəfdəki filter paneli — hamısı birlikdə istifadəçiyə sürətli və dərin analiz imkanı yaradır.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7f7fe48c-2141-4082-aa31-093ac531cdec" width="90%" />
</p>

---

#### 🃏 KPI Kartları

<!-- Kart şəkillərini buraya əlavə et -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/5b22b159-f97b-4430-a08e-26e798b860a9" width="90%" />
</p>

Dashboardun yuxarı hissəsində 4 əsas KPI bloku yerləşir:

- **Satış Kartı** — Cari dövrün ümumi satış həcmini göstərir (**56M**). Alt hissədə keçən ilin müqayisəli dəyəri (**K/İl: 40.25M**) və illik artım faizi (**▲39.76%**) ilə birlikdə vurğulanır. Yaşıl ox artımı, qırmızı ox azalmanı simvolizə edir.

- **Mənfəət Kartı** — Cari dövrün ümumi mənfəətini göstərir (**32M**). Keçən ilə nisbətən (**K/İl: 23.16M**) **▲40.13%** artım qeydə alınıb. Satış kartı ilə eyni müqayisəli quruluşa malikdir.

- **Ümumi Miqdar Kartı** — Satılan məhsulların ümumi sayını əks etdirir (**251K**). Sifariş həcminin real miqyasını göstərmək üçün nəzərdə tutulub.

- **Order Count Kartı** — Tamamlanmış sifariş sayını göstərir (**15K**). Əməliyyat yükünü və müştəri aktivliyini ölçmək üçün istifadə olunur.

---

### 🎛 Filter Paneli 

<table>
  <tr>
    <td width="40%">
      <img src="https://github.com/user-attachments/assets/4644cd82-6bd5-4375-ad29-eca0bc680149" width="100%" />
    </td>
    <td width="60%">

Dashboardun sol hissəsində yerləşən filter paneli State (əyalət) adlarının siyahısından ibarət slicer-dir. İstifadəçi istənilən əyaləti seçdikdə bütün vizuallar dinamik olaraq həmin əraziyə görə yenilənir. Bu, regional müqayisəni son dərəcə asanlaşdırır.

  </tr>
</table>

---

#### 📈 Aylıq Satış Trendi və Həftəlik Satış

<!-- Hər iki vizualın şəklini buraya əlavə et -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/f0d677e2-e6b1-4c21-ac60-18433cc10e82" width="90%" />
</p>

- **Aylıq Satış Trendi** — Xətt qrafiki vasitəsilə Yanvardan Dekabra qədər aylıq satış dinamikasını göstərir. Fəsli dəyişiklikləri, pik ayları və tənəzzül dövrlərini aydın şəkildə müəyyən etməyə imkan verir. Qrafikdən göründüyü kimi, satışlar yaz aylarında müəyyən düşüş yaşayır, payızda isə kəskin artım müşahidə olunur.

- **Həftəlik Satış** — Sütun diaqramı şəklində həftə nömrəsinə görə satış miqdarını əks etdirir. İlin sonuna yaxın (45–55-ci həftələr) satışların zirvəyə çatdığı aydın görünür. Bu vizual mövsümi planlaşdırma üçün əhəmiyyətlidir.

---

#### 🏆 Top 10 Məhsul, BrandName / Satış və Kateqoriya / Satış

<!-- Üç vizualın şəklini birlikdə buraya əlavə et -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/33866e20-c4b1-4abe-a904-d9019f8749aa"width="90%" />
</p>

Bu üç vizual birlikdə məhsul, brend və kateqoriya üzrə satış performansının tam mənzərəsini yaradır:

- **Top 10 Product BY Satış** — Cədvəl formatında ən yüksək satış həcminə sahib 10 məhsulu Mənfəət və Satış sütunları ilə birlikdə sıralayır. Seçilmiş sıra mavi rənglə vurğulanır. Qrafikdən göründüyü kimi lider məhsullar Contoso və Proseware brendlərinin proyektor modelləridir — ən yüksək satış **452K**, ən yüksək mənfəət isə **326K** səviyyəsindədir.

- **BrandName / Satış** — Üfüqi sütun diaqramı ilə hər brendin ümumi satış həcmini müqayisə edir. **Fabrikam (12M)** lider mövqedədir, ardınca **Contoso (10M)** və **Adventure Works (8M)** gəlir. Bu vizual hansı brendin biznesə daha çox dəyər qatdığını dərhal göstərir.

- **Məhsul Kategoriya / Satış** — Üfüqi sütun diaqramı ilə kateqoriyalar üzrə satış bölgüsünü əks etdirir. **Computers (22M)** açıq şəkildə liderdir, **Cameras and Camcorders (17M)** ikinci yerdədir. Bu vizual hansı məhsul qrupunun əsas gəlir mənbəyi olduğunu müəyyən edir.

---

### 🔹 Səhifə 2 — Regional Analiz

İkinci səhifə satışların coğrafi və kanal üzrə bölgüsünə həsr olunub. Xəritə vizualı, promosyon analizi və kanal üzrə donut diaqramları birlikdə regional performansın tam şəkildə anlaşılmasını təmin edir.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7f7fe48c-2141-4082-aa31-093ac531cdec" width="90%" />
</p>

---

#### 🗺 Ümumi Satış by State (Xəritə)

<table>
  <tr>
    <td width="40%">
      <img src="https://github.com/user-attachments/assets/cd75511b-da42-47d9-833b-8de83f9a0385" width="100%" />
    </td>
    <td width="60%">

Microsoft Bing xəritəsi üzərində Nigeriya əyalətləri üzrə satış həcmi baloncuqlarla vizuallaşdırılıb. Baloncuğun ölçüsü satış miqdarı ilə mütənasibdir — **Kano, Kaduna, Kebbi və Abia** kimi əyalətlər iri baloncuqlarla öndə görünür. Bu vizual hansı regionların daha güclü performans göstərdiyini dərhal aydınlaşdırır.

  </tr>
</table>


---

#### 📣 Ümumi Satış by PromotionName

<p align="center">
  <img src="https://github.com/user-attachments/assets/a63c8e59-fb16-4437-bdfb-9bc12adfa9ee" width="60%" />
</p>

Üfüqi sütun diaqramı müxtəlif promosyon növlərinin satışa təsirini müqayisə edir. **Regular Sales** açıq fərqlə liderdir (~18M). **Ramadan Promotion, Hammartan Promotion** və **New Year Promotion** da əhəmiyyətli töhfə verir. Bu vizual hansı kampaniyanın ən effektiv olduğunu göstərir və marketinq qərarlarının verilməsinə birbaşa dəstək olur.

---

#### 🍩 Ümumi Satış by Channel Name və Ümumi Mənfəət by Channel Name

<!-- Hər iki donut diaqramının şəklini birlikdə buraya əlavə et -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/55ae254d-1361-44d9-bc43-d9a4a0514eda" width="80%" />
</p>

Mərkəzi boş olan iki donut diaqramı satış kanallarının (Store, Online, Reseller, Mobile Outlet) həm satış, həm də mənfəət üzrə payını göstərir:

- **Ümumi Satış by Channel** — **Online kanal** **32M (57%)** ilə dominant mövqedədir. Ardınca **Store (12M, 20.8%)**, **Reseller (7M, 12.98%)** və **Mobile Outlet (5M, 9%)** gəlir.

- **Ümumi Mənfəət by Channel** — Mənfəət bölgüsü də satış strukturunu əks etdirir: **Online (19M, 57%)**, **Store (7M, 20.7%)**, **Reseller (4M, 13.07%)**, **Mobile Outlet (3M, 9.11%)**. Bu iki diaqramın yan-yana yerləşdirilməsi kanalların həm gəlir, həm mənfəət effektivliyini bilavasitə müqayisə etməyə imkan verir.

---

## ✅ Dashboard-un Üstünlükləri
- Satış və mənfəət performansını keçən illə avtomatik müqayisə etmək imkanı
- YoY% göstəriciləri və istiqamət oxları ilə artım/azalmanın dərhal görünməsi
- Çoxsəviyyəli filtrasiya (il, ay, həftə günü, əyalət, promosyon növü)
- Xəritə üzərindən regional performansın vizual oxunması
- Kanal üzrə həm satış, həm mənfəət bölgüsünün eyni vaxtda müqayisəsi
- İki səhifəli strukturun page navigator ilə rahat keçidi

---

## 📎 Nəticə
Bu layihə real satış məlumatları əsasında hazırlanmış, şirkətin performansını həm zaman, həm məhsul, həm də coğrafi baxımdan əhatə edən professional dashboard nümunəsidir. İnteraktiv filtrləri və müqayisəli göstəriciləri sayəsində data əsaslı qərarverməni birbaşa dəstəkləyir.
