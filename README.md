# Farxod English — 5-in-1 English Mastery Studio

Ingliz tilini har tomonlama mustahkamlash, erkin gapirish, tinglab tushunish, so‘z boyligini oshirish va grammatikani sinash uchun yaratilgan 5 ta maxsus bo‘limdan iborat to‘liq web studiya.

---

## 🌟 5 Asosiy Bo‘lim (Categories & Modes)

### 1. 🎙️ Shadowing — Matnni ovoz chiqarib o‘qish, smooth scroll
* **Silliq siljish (Smooth scroll)**: 30 dan 250 WPM gacha sozlanadigan, bir tekis ravon harakatlanuvchi matn.
* **✨ Fokus effekti darajalari**:
  - `✨ Kuchli (Deep)`: Markazdagi qator o‘ta to‘q qora va ravshan, yuqori va pastki qatorlar chuqur xiralashadi.
  - `✨ O‘rtacha (Medium)`: Muvozanatli standart optik fokus.
  - `✨ Mayin (Soft)`: Yengil xiralashish.
  - `✨ Oddiy (Off)`: Fokus maskasisiz toza matn.
* **🌧️ Fon atmosferasi darajalari**:
  - `🌧️ Yomg‘ir (Rain)`: Mayin lofi yomg‘ir tomchilari.
  - `❄️ Qor (Snow)`: Sekin tushuvchi qor parchalari.
  - `✨ Mayin (Glow)`: Mayin suzuvchi lofi nurlari.
  - `🚫 O‘chiq (Off)`: Chalg‘itmaydigan toza fon.
* **🧘 Breathe (Nafas mashqi)**:
  - O‘qish va Shadowingdan oldin nutqni erkinlashtirish va ovoz titrashini yo‘qotish uchun interaktiv nafas mashqi (`4s Nafas olish -> 2s Ushlab turish -> 4s Sekin chiqarish`).
* **Interaktiv qurollar**:
  - `[ 🎙️ Shadowing ]`: Namuna ovozi bilan bir vaqtda matnga ergashib ovoz chiqarib o‘qish.
  - `[ 🎤 Ovoz bilan ]`: Jimlikni sezuvchi mikrofon (gapirsangiz siljiydi, 1.5s jim qolsangiz to‘xtaydi).
  - `[ 🔴 Yozish ]`: O‘z ovozingizni yozib olib, xatolaringizni qayta eshitish.
  - `[ 🎵 Lofi on ]`: 5 xil foniy ambient musiqa generatori.

---

### 2. 🎧 Listening — Audio tinglash va savollarga javob berish
* **50 ta boyitilgan audio mavzu**: Real hayotiy, dolzarb va qiziqarli mavzulardagi matnlar (~150–200 so‘z).
* **Audio pleyer**: Toza inglizcha talaffuz (TTS Audio), tinglash tezligini boshqarish (`0.85x`, `1.0x`, `1.15x`) va vizual to‘lqin animatsiyasi.
* **Matnni tushunish savollari (Comprehension Questions)**:
  - 170 ta test savoli (Multiple Choice va True / False).
  - Tanlangan javob darhol yashil (to‘g‘ri) yoki qizil (noto‘g‘ri) rangga kiradi.
  - Har bir savol ostida matnga asoslangan batafsil tushuntirish (*Explanation*) chiqadi.

---

### 3. 📚 Vocabulary — So‘zlar, misollar va tarjimalar
* **1,200 ta B2 darajadagi so‘z**: 50 ta mavzu bo‘yicha to‘liq taqsimlangan boy lug‘at bazasi.
* **Har bir so‘z kartochkasida**:
  - So‘z va uning so‘z turkumi (*noun, verb, adjective, phrase*).
  - **🔊 Audio talaffuz tugmasi**: Toza inglizcha talaffuzni eshitish.
  - **O‘zbekcha aniq tarjimasi**.
  - **Inglizcha misol jumla**.
  - **Misol jumlaning o‘zbekcha tarjimasi**.
* **Tezkor qidiruv & Filtrlar**: So‘z yoki tarjima bo‘yicha lahzalik qidiruv hamda so‘z turkumi bo‘yicha filtrlar.

---

### 4. 📖 Reading — Matn o‘qish va tushunishni tekshirish
* **50 ta o‘qish matni**: Qiziqarli ilmiy, psixologik va hayotiy mavzulardagi to‘liq matnlar.
* **O‘qish tezligi o‘lchagichi (Reading Speed / WPM Tracker)**:
  - `[ ⏱️ O‘qishni boshlash ]` tugmasi bilan taymer boshlanadi.
  - O‘qib bo‘lgach `[ ✓ O‘qib bo‘ldim ]` bosiladi va ilova sizning aniq o‘qish tezligingizni (WPM — so‘z/daqiqa) hisoblab beradi (masalan, `🚀 220 WPM`).
* **Tushunishni tekshirish savollari**: Matn yuzasidan savollarga javob berib, tushunish foizini bilib olish.

---

### 5. ⚡ Quiz — Grammatika va lug‘at bo‘yicha testlar (Tezlik rejimi bilan)
* **Tezlik / Vaqt chegarasi (Speed Mode)**:
  - `⚡ 10 soniya (Tez)`
  - `⏱️ 20 soniya (O‘rta)`
  - `⏳ 30 soniya (Sekin)`
  - `♾️ Cheklovsiz`
* **Test turlari**:
  - `🔥 Aralash`: Grammatika va yangi so‘zlar aralash holda.
  - `📚 Lug‘at`: So‘z ma’nosi va kontekstdagi bo‘shliqni to‘ldirish.
  - `📝 Grammatika`: Zamonlar, Conditionals, Passive voice, Inversion, Gerunds va iboralar.
* **Jonli taymer & Streak**: Har bir savol uchun rangini o‘zgartiruvchi vaqt chizig‘i, ketma-ket to‘g‘ri javoblar streaki (`🔥 Streak: 5`), tushuntirishlar va yakuniy ball.

---

## 🛠️ Optimallashtirilgan Arxitektura

- **`createParticles(x, y, color, count, type)`**: Qotmasdan va xotirani band qilmasdan ishlovchi yengil zarrachalar generatori.
- **`animate(now)`**: 60fps to‘liq apparat tezlanishidagi birlashgan animatsiya sikli (`requestAnimationFrame`).
- **`breathe(action)`**: Ovoz erkinligi va nafasni to‘g‘rilash uchun interaktiv vizual mashq boshqaruvi.

---

## 🚀 Ishga tushirish

Ilovani to‘g‘ridan-to‘g‘ri brauzerda ochishingiz yoki mahalliy server orqali ishlatishingiz mumkin:
```bash
python -m http.server 3000
```
Brauzerda: `http://localhost:3000/index.html`

🌐 **Jonli havola (GitHub Pages)**: [https://umarovafiruza.github.io/farxod-english/](https://umarovafiruza.github.io/farxod-english/)
