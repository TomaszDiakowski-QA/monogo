# monogo
## Playwright tests using typescript

tests/
│
├── config/
│   └── markets.ts              # Konfiguracja rynków
│
├── pages/
│   ├── BasePage.ts             # Bazowa klasa strony
│   ├── HomePage.ts             # Strona główna
│   ├── ProductPage.ts          # Strona produktu
│   └── CartPage.ts             # Strona koszyka
│
├── tests/
│   ├── addToCart.spec.ts       # Test dodawania do koszyka
│   ├── removeFromCart.spec.ts  # Test usuwania z koszyka
│   └── checkLinks.spec.ts      # Test linków i obrazów
│
└── utils/
    └── helpers.ts              # Dodatkowe funkcje pomocnicze
