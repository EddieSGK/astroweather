# 🔭 AstroWeather Dashboard for Seestar S30 Pro

Lekki, responsywny dashboard HTML/JS wspomagający planowanie nocnych sesji astrofotograficznych z wykorzystaniem inteligentnego teleskopu **ZWO Seestar S30 Pro**. 

Aplikacja automatycznie przelicza pozycje obiektów głębokiego nieba dla lokalizacji **Bydgoszcz**, uwzględniając lokalne warunki zachmurzenia oraz fizyczne zasłonięcia horyzontu.

---

## ✨ Kluczowe funkcje

* **Prognoza zachmurzenia w nocy astronomicznej:** Wykres przebiegu chmur z API Open-Meteo z uwzględnieniem świtu i zmierzchu astronomicznego (SunCalc).
* **Ściągawka parametrów dla Seestara S30 Pro:** Dynamiczne podpowiedzi filtrów (Dual-Band LP vs UV/IR Cut) i czasów integracji uzależnione od typu obiektu i fazy Księżyca.
* **Katalog Messiera (M1–M110) + Planety:** Automatyczne wyliczanie punktów kulminacji, wysokości nad horyzontem oraz optymalnego okna obserwacyjnego.
* **Filtr Horyzontu:** Możliwość przełączania widoku między spersonalizowanym horyzontem (zdefiniowane strefy wysokości) a pełną listą obiektów powyżej $0^\circ$.
* **Dedykowane ikony SVG:** Czyste, wektorowe symbole klas obiektów (galaktyki spiralne, gromady kuliste, gromady otwarte, mgławice, planety).
* **Tryb Czerwony (Night Vision):** Pełne dostosowanie interfejsu i wykresów do pracy w ciemności, chroniące adaptację wzroku.

---

## 🛠️ Technologia

* **Zero backendu / Zero zależności przy budowaniu:** Działa natywnie w przeglądarce jako pojedynczy plik `index.html`.
* **Tailwind CSS CDN:** Responsywny i nowoczesny układ kart.
* **Chart.js:** Wykres zachmurzenia w czasie rzeczywistym.
* **SunCalc.js:** Wyliczanie epafrydów Słońca, Księżyca i zmierzchów.

---

## 🚀 Uruchomienie lokalne

Wystarczy pobrać plik `index.html` i otworzyć go w dowolnej przeglądarce internetowej lub serwować przez dowolny serwer HTTP (np. Nginx w Dockerze, GitHub Pages).
