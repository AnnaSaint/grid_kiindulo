# HTML & CSS Rövid Összefoglaló

## Igazítás

- **justify-content**: A fő tengelyen történő igazítás (pl. space-evenly, center, flex-start / end).  
- **align-content**: A több sorból álló tartalom keresztirányú igazítása.  
- **align-items**: Az egyes elemek keresztirányú igazítása a konténerben.  

## Grid Alapok

- **display: grid**: A konténer grid elrendezést kap.  
- **grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))**: Automatikusan létrehoz oszlopokat, minimum 200px szélességgel, rugalmasan növelve.  
- **grid-template-rows: 100px 1fr auto**: Sorok magassága: első 100px, második rugalmas, harmadik automatikus.  
- **grid-auto-flow: row / column**: Meghatározza, hogy az automatikus elemek sorban vagy oszlopban helyezkedjenek el.  

- **direction: ltr / rtl**: Szöveg és elrendezés iránya, balról jobbra vagy jobbról balra.  
- **order: -1**: Az elem sorrendjének módosítása a Grid konténerben.

- **grid-template-areas**: A grid területeinek elrendezését nevekkel adjuk meg. Pl.:

  ```css
  grid-template-areas:
    "h h"
    "ar as";

- **grid-area**: Az elem hozzárendelése a név szerint definiált grid-területhez. Pl.:
  
  ```css
  header{
    grid-area: h;
  }

