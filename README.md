# ☕ AromaCafe – Modern Coffee Shop Template

AromaCafe to responsywny i elegancki szablon sklepu internetowego dla branży Specialty Coffee. Zbudowany z myślą o szybkości i estetyce, wykorzystuje najnowszą wersję **Tailwind CSS 4** oraz czysty **JavaScript**.



## ✨ Funkcje (Features)

* **Dynamiczny Koszyk:** W pełni funkcjonalny panel boczny koszyka (Side Cart) z obliczaniem sumy zamówienia w czasie rzeczywistym.
* **Zaawansowane Filtrowanie:** Intuicyjne filtrowanie produktów po kategorii, stopniu palenia (roast) oraz przeznaczeniu (metoda parzenia).
* **Wyszukiwarka:** Szybkie przeszukiwanie asortymentu po nazwie, kraju pochodzenia lub nutach smakowych.
* **Mobile First:** W pełni responsywny design, który wygląda świetnie na smartfonach i tabletach.
* **Clean Code:** Logika oparta na prostym stanie aplikacji (State Management), łatwa do przeniesienia do Reacta, Vue czy Next.js.

## 🛠️ Technologie (Stack)

* **HTML5 & CSS3**
* **Tailwind CSS 4** (JIT Engine przez CDN)
* **Vanilla JavaScript** (ES6+)

## 🚀 Szybki start (Quick Start)

Szablon jest zawarty w jednym pliku, co ułatwia jego wdrożenie:

1. Sklonuj repozytorium: `git clone https://github.com/TwojUser/AromaCafe.git`
2. Otwórz plik `index.html` w swojej przeglądarce.
3. Aby edytować produkty, przejdź do sekcji `const products` wewnątrz tagu `<script>`.

## 📖 Przykładowe dane produktu
Struktura danych jest przygotowana pod łatwą integrację z API lub CMS:
```javascript
{
  id: 1,
  name: "Kenya Kirinyaga",
  country: "Kenia",
  roast: "light",
  tasting: ["porzeczka", "cytrusy", "karmel"],
  price: 54
}
