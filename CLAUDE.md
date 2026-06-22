# SPEC-KOP — Instrukcja dla Claude Code

## Kontekst projektu
Strona internetowa firmy **SPEC KOP Leszek Marasek** — jednoosobowa działalność gospodarcza świadcząca usługi robotami ziemnymi. Firma działa od **2026 roku**. Leszek Marasek pracował jako operator koparki i kierowca wywrotki w firmie budowlano-transportowej na terenie Przysuchy (jedna firma, ważna funkcja — nie podawaj konkretnej liczby lat, bo nie jest zweryfikowana). Zdecydował się założyć własną działalność.

## Główny plik
`spec-kop.html` — pojedynczy plik HTML (CSS i JS inline, zero frameworków zewnętrznych poza Google Fonts).

## Dane firmy (NIE ZMIENIAJ bez polecenia)
- Nazwa: SPEC KOP Leszek Marasek
- Adres: Pomyków 49, 26-400 Przysucha
- Telefon: +48 607 066 478
- E-mail: leszekmarasek89@gmail.com
- NIP: 7991134649
- REGON: 543638720
- Sprzęt: Liebherr A 918 Compact (zdjęcie: IMG_8905.jpg)

## Tokeny designu (NIE ZMIENIAJ bez polecenia)
```
--bg: #050505
--bg-2: #0d0d0b
--bg-3: #141410
--border: rgba(255,255,255,0.07)
--text: #f5f5f7
--text-muted: #8e8e93
--accent: #f59e0b
--f-display: 'Barlow Condensed', sans-serif
--f-body: 'Barlow', sans-serif
```

## Zasady projektowe (ZAWSZE przestrzegaj)
1. **Dark mode** — tło zawsze ciemne, nigdy białe sekcje
2. **Zero border-radius** — wszystkie elementy mają ostre narożniki (border-radius: 0)
3. **Typografia display** — nagłówki zawsze Barlow Condensed, uppercase, font-weight 900
4. **Akcent bursztynowy** — #f59e0b wyłącznie do akcentów, nigdy jako tło sekcji
5. **Jeden plik** — CSS i JS zawsze inline w `spec-kop.html`, bez zewnętrznych plików .css/.js
6. **Responsive** — breakpoint 960px, mobile-first podejście
7. **Reveal animacje** — nowe sekcje dodawaj z klasą `.reveal` i odpowiednim `.reveal-delay-N`

## Prawdziwy opis firmy (używaj przy pisaniu treści)
- Firma **nowa, założona w 2025 roku**
- Leszek ma **wieloletnie doświadczenie jako operator** — zdobyte podczas pracy u innych firm
- **Nie kłam o liczbie realizacji** — firma jest nowa, zleceń było niewiele, brak zdjęć z prac
- Mocna strona: doświadczenie i kompetencje operatora, nie historia firmy
- Podkreślaj: **własny sprzęt**, **bezpośredni kontakt z operatorem** (nie przez pośredników), **uczciwa wycena**
- Ton: konkretny, rzemieślniczy, bez korporacyjnego bełkotu

## Usługi (PKD)
- 43.99.Z — Roboty ziemne & wykopy (fundamenty, korytowanie, niwelacja)
- 46.63.Z — Dostawa & Wywóz wywrotką (kruszywa, ziemia, gruz)
- 43.21.Z — Przyłącza & Wykopy liniowe (wod-kan, energetyka, teletechnika)

## Zasady przy edycji treści
- Sekcja "Realizacje" lub liczniki zleceń — **nie dodawaj** dopóki nie będzie prawdziwych danych/zdjęć
- Licznik "15 lat na rynku" odnosi się do doświadczenia operatora, **nie do istnienia firmy**
- Statystyki w stylu "300+ zleceń" — **nie dodawaj**, firma jest nowa
- Jeśli pytasz o coś — zadaj **jedno pytanie na raz**

## Jak pracować z tym projektem
Przy każdej sesji:
1. Przeczytaj ten plik (`CLAUDE.md`)
2. Sprawdź aktualny stan `spec-kop.html` (`cat spec-kop.html | head -50`)
3. Edytuj wyłącznie przez `str_replace` (nie nadpisuj całego pliku bez potrzeby)
4. Po każdej zmianie powiedz co zrobiłeś i dlaczego

## Planowane rozszerzenia (nie rób tego sam, czekaj na polecenie)
- Podstrona galerii gdy pojawią się zdjęcia realizacji
- Formularz z wysyłką e-mail (np. Formspree lub własny backend)
- Google Analytics / Search Console
- Podstrona dla każdej usługi (SEO)
