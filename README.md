# ⚡ CHROMACOIL 2.0

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-00f2fe?style=for-the-badge)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Optimized-ff0844?style=for-the-badge)

> *"Inietta il codice. Divora i dati. Diventa l'anomalia perfetta."*  
> *"Inject the code. Devour the data. Become the perfect anomaly."*

**ChromaCoil** è un videogioco arcade di sopravvivenza in stile *Slither.io* con estetica Cyberpunk/Synthwave, sviluppato interamente in un **singolo file `index.html`** senza alcuna libreria o risorsa esterna. Progettato e ottimizzato per girare a 60 FPS su smartphone (anche direttamente da editor mobile come **A-Code**) e browser desktop.

### 🎮 [Gioca alla Live Demo (GitHub Pages)](https://davide23567.github.io/chromacoil/)


---

## 🚀 Caratteristiche Principali

* **🌐 Arena Infinita Procedurale:** Nessun muro perimetrale. La griglia olografica, i frammenti di dati (cibo) e i bot si generano e riposizionano dinamicamente attorno al giocatore.
* **📱 Controllo Direct-Touch & Multi-Touch:** Sistema di guida fluido a 360° che segue il dito sullo schermo (con *deadzone* anti-tremolio e *Smooth Camera* ammortizzata), affiancato da un pulsante **⚡ Turbo** indipendente utilizzabile contemporaneamente con il secondo pollice.
* **🧠 Intelligenza Artificiale Predittiva:** 18 Bot avversari dotati di radar anticollisione (sterzano d'emergenza per evitare il tuo corpo), ricerca attiva del cibo e utilizzo strategico del Turbo.
* **🔊 Sintetizzatore Audio Integrato (Web Audio API):** Effetti sonori retro-synth generati matematicamente in tempo reale dal codice. Nessun file `.mp3` o `.wav` esterno richiesto.
* **🎨 Personalizzazione & Glassmorphism UI:** Interfaccia utente moderna con effetto vetro satinato (`backdrop-filter`), selettore di **5 Skin al Neon**, particelle esplosive, testi fluttuanti e coda anatomica affusolata.
* **🌍 Multilingua (i18n) & Salvataggio Dati:** Traduzione istantanea **Italiano / Inglese** dal menu impostazioni e salvataggio automatico del Miglior Punteggio tramite `localStorage`.

---

## 🕹️ Comandi di Gioco

| Piattaforma | Movimento (Sterzata 360°) | Turbo (Boost) | Pausa |
| :--- | :--- | :--- | :--- |
| **📱 Mobile / Touch** | Trascina il dito in qualsiasi punto dello schermo | Tieni premuto il tasto **⚡** in basso a sinistra | Tocca **⏸️** in alto a destra |
| **💻 PC / Desktop** | Muovi il cursore del mouse | Tieni premuta la **Barra Spaziatrice** (o clicca su **⚡**) | Clicca su **⏸️** in alto a destra |

> **Nota sul Turbo:** Attivare il potenziamento di velocità raddoppia l'andatura ma consuma gradualmente i tuoi punti, rilasciando una scia energetica dalla coda (richiede almeno 20 punti).

---

## 🛠️ Come Avviare il Gioco

Essendo costruito con architettura *Single-File*, non serve installare Node.js, database o compilatori:

### 1. Da Smartphone (con A-Code o browser mobile)
1. Scarica il file `index.html`.
2. Aprilo dentro **A-Code** (o qualsiasi editor di codice Android/iOS) e premi il tasto **Play ▶** in alto a destra.

### 2. Da PC
1. Clona questo repository:
   ```bash
   git clone [https://github.com/Davide23567/chromacoil.git](https://github.com/Davide23567/chromacoil.git)
   
