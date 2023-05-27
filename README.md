# Postup řešení Aimeos pro E-letak

### Nastavení prostředí
---
1. **Instalace a konfigurace systému Aimeos**
    * Nainstalujme Laravel, nastavíme jeho prostředí, poté nainstalujeme Aimeos pomocí nástroje Composer a inicializujeme jej.

<br>

### Konfigurace s databází

---

1. **Databáze**.
    * Konfigurace připojení k databázi v konfiguračním souboru Laravel.
2. **Datový model**.
    * Vytvoření modelů interiéru kuchyně, domácích spotřebičů (název, cena, vlastnosti).
    * Vytvoření migrací pro zadání modelů do databáze.
3. **Vkládání dat do databáze**.
    * Vkládání dat o kuchyňském nábytku, spotřebičích atd. do databáze.
    * Vytvoření kategorií a atributů pro snadné třídění a filtrování zboží.
    * Přizpůsobíme ceny, dostupnost

<br>

### Vytvořit části front-endu a back-endu

---

Po inicializaci Aimeosu získáme základní funkce jako filtry, řazení do seznamu, vyhledávání zboží, přidávání zboží do košíku, nákupní proces (pouze editace nákupních polí a přidání platebního systému), stránku zboží, panel administrátora.

1. **Úprava hlavních stránek**.
    * Stylování stránek pro zobrazení seznamu produktů, nákupního košíku, profilu, stránky produktu, vyhledávání produktů atd.
2. **Základní funkce**.
    * Nastavení filtrů podle kategorií, atributů a dalších parametrů vyhledávání.
    * Funkce pro přidávání položek do košíku, aktualizaci množství položek na skladě, pokladnu.
3. **Nastavení platby za objednávku**.
    * Integrace platebního systému pro transakce
4. **Dokončení zbývajících detailů webu**.

S ohledem na to, že mnoho věcí je připraveno předem přímo z krabice, stačí jen, aby vše hezky vypadalo, odstranit všechny chyby, nastavit platební systém, zpracování objednávek atd.
