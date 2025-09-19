# Animation
# CSS Animatsioonide Ülesanne

## Ülesande kirjeldus
Selles ülesandes tuleb luua väike veebileht, mis demonstreerib **vähemalt viit erinevat CSS-animatsiooni või üleminekut**.  
Eesmärk on näidata, kuidas CSS-i abil saab luua interaktiivseid ja visuaalselt atraktiivseid efekte **ilma JavaScripti kasutamata**.

Leht võib olla lihtne demo või väike disainiprojekt (nt hero-bänner, kaardid, navigeerimismenüü ja nupud).

---

## Õppeeesmärgid
Pärast ülesande lõpetamist oskad:
- eristada `transition` ja `animation (keyframes)` võimalusi;
- rakendada animatsioone HTML-elementidel (nt nupp, pilt, kaart, menüü);
- kasutada omadusi nagu `transform`, `opacity`, `filter`, `clip-path`, `box-shadow`;
- lisada **staggered** animatsioone (erineva viivitusega elemendid);
- arvestada ligipääsetavust (`prefers-reduced-motion`).

---

## Nõuded
1. **HTML** peab olema semantiline ja korrastatud (`header`, `main`, `section`, `footer` jne).
2. **CSS** peab olema eraldi failis, mitte inline.
3. Kasuta vähemalt **5 erinevat animatsiooni**, näiteks:
   - nupu hover-efekt (`transition` värv/scale),
   - hero-teksti sisselennutamine (`@keyframes`),
   - kaardianimatsioon (hover-efekt `transform` ja `box-shadow` abil),
   - navigeerimismenüü underline animatsioon,
   - pildi hover filter-efekt (`filter: grayscale` → värviline),
   - või mõni muu loov efekt (nt loader, clip-path reveal, pulse).
4. Lisa **@media (prefers-reduced-motion: reduce)**, et vähendada liikumist kasutaja eelistuste järgi.
5. Kood peab olema kommenteeritud ja loetav.

---

## Failistruktuur (soovituslik)
