sp1 krouzky

21

3 chyby: nektere krouzkmaji prvni pismeno male, u nekterych je IT2 a jinde IT 2 (s mezerou), par dni je napsanych celym jmenem a jinak zkratkou

přihlášky:

PK: id_přihlášky
FK: id_žáka → žáci
FK: id_kroužku → kroužky

žáci:
PK: id_žáka

kroužky:
PK: id_kroužku

<img width="2051" height="1777" alt="Mermaid Flow Flow-2026-10-12-122423" src="https://github.com/user-attachments/assets/43f76240-31e3-4c53-86c7-ee6036c648e4" />

SELECT nazev, cena
FROM krouzky
WHERE cena > 500;
