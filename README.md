# ✈️ Uçuş Qiymətlərinin Proqnozlaşdırılması və Data Analizi

Bu layihə, Hindistanın daxili uçuş bazarına aid genişmiqyaslı **Exploratory Data Analysis (EDA)** və statistik araşdırmadır. Əsas məqsəd, bilet qiymətlərinə təsir edən gizli faktorları aşkar etmək və sərnişin davranışlarını analiz etməkdir.

---

## 📊 Vizuallaşdırma və Təhlil

Analiz zamanı əldə olunan əsas vizual nəticələr:

### 1. Aviaşirkətlərin Bazar Payı
Tədqiqat göstərir ki, **Vistara** və **Air India** bazarda ən böyük uçuş həcminə malik şirkətlərdir. **SpiceJet** isə ən az uçuş sayına malik operator kimi qeyd olunur.

### 2. Uçuş Vaxtlarının Paylanması
Gediş və gəliş vaxtlarının analizi göstərir ki:
* Sərnişinlər ən çox **Səhər (Morning)** gedişlərini üstün tuturlar.
* Gəliş vaxtı olaraq isə **Gecə (Night)** saatları üstünlük təşkil edir.
* Bu zaman dilimləri qiymət artımına birbaşa təsir edən amillərdir.

### 3. Marşrut Analizi (Mənbə və Təyinat)
Analiz nəticəsində məlum oldu ki, **Delhi** və **Mumbai** şəhərləri həm ən böyük gediş (Source), həm də ən böyük gəliş (Destination) mərkəzləridir (hubs).

---

## 🎯 Əsas Nəticələr (Insights)

* **Qənaət Strategiyası:** Biletləri uçuşa ən azı **21 gün qalmış** almaq kəskin qənaət təmin edir. Son 10 gündə qiymətlər pik həddə çatır.
* **Sinif Fərqi:** **Business** sinfi **Economy** sinfindən orta hesabla **8 dəfə** bahadır.
* **Bazar Lideri:** **Vistara** həm uçuş sayına, həm də lüks seqmentdəki qiymət göstəricilərinə görə (maksimum: 123,071 ) liderdir.
* **Dayanacaqların Təsiri:** Birbaşa (non-stop) uçuşlar həm vaxt baxımından daha qısadır, həm də orta hesabla daha ucuzdur.

---

## 🛠 Texnologiyalar

Layihənin hazırlanmasında aşağıdakı texnoloji stack istifadə olunub:

* **Dil:** Python
* **Data Manipulyasiyası:** `Pandas`, `NumPy`
* **Vizuallaşdırma:** `Matplotlib`, `Seaborn`

---

## 🚀 Quraşdırma və İstifadə

1. Repozitoriyanı klonlayın:
   ```bash
   git clone [https://github.com/istifadeci_adiniz/flight-price-analysis.git](https://github.com/istifadeci_adiniz/flight-price-analysis.git)
