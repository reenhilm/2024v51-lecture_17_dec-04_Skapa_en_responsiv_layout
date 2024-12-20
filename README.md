---

## **Övning 4: Skapa en Responsiv Layout**

### **Beskrivning**
Skapa en layout med **flera kortkomponenter** (`.card`) i en flexbox/grid-layout. Använd **Container Queries** och `clamp()` för att göra korten och deras innehåll responsiva.

---

### **Mål**
1. Lägg flera `.card`-komponenter i en **flexbox** eller **CSS Grid**-layout.  
2. Applicera Container Queries för att ändra utseendet på korten.  
3. Använd `clamp()` för att göra textstorleken responsiv.

---

### **Steg-för-steg**
1. HTML-struktur:

```html
<div class="cards-container">
  <div class="card">
    <h3>Kort 1</h3>
    <p>Responsivt kort 1.</p>
  </div>
  <div class="card">
    <h3>Kort 2</h3>
    <p>Responsivt kort 2.</p>
  </div>
  <div class="card">
    <h3>Kort 3</h3>
    <p>Responsivt kort 3.</p>
  </div>
</div>
```

2. CSS:
   - Använd **Flexbox/Grid** för att layouta korten.  
   - Definiera containern som en **container**.  
   - Använd **Container Queries** och `clamp()` på kortens text.

---

### **Exempeloutput**
- Korten ska placeras i en **rad** på breda skärmar och **staplas vertikalt** på smala skärmar.  
- Texten ska vara responsiv med `clamp()`.

---
