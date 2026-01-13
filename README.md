<div align="center">

# 🎮 System Breach: Five Nights

![GameMaker](https://img.shields.io/badge/GameMaker-000000?style=for-the-badge&logo=gamemaker&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Version](https://img.shields.io/badge/v1.0.0.0-5865F2?style=for-the-badge)

*A Five Nights At Freddy's parody — survival horror*

[🇮🇹 Italiano](#-italiano) · [🇬🇧 English](#-english)

</div>

---

## 🇮🇹 Italiano

<div align="center">
*Un tributo a Five Nights at Freddy's.*<br>
*Sopravvivi a cinque notti in un edificio abbandonato.*
</div>

---

### 🎮 Descrizione

**System Breach: Five Nights** è un gioco survival horror sviluppato con **GameMaker Studio 2**, ispirato alla saga di *Five Nights at Freddy's*. Vestirai i panni di una guardia notturna assunta per sorvegliare un edificio abbandonato di una compagnia di telecomunicazioni. Il tuo turno va dalle 00:00 alle 06:00 per cinque notti. Usa telecamere di sorveglianza, firewall e una misteriosa maschera per sopravvivere agli ostili che abitano l'edificio.

### 📖 Story

Un'antica compagnia di telecomunicazioni futuristica ha abbandonato i suoi uffici anni fa, lasciando dietro di sé macchinari, server e segreti. Ora l'edificio è infestato da tre entità ostili. Tu sei una guardia notturna assunta per monitorare l'edificio attraverso le telecamere di sicurezza. Ogni notte, dalle 00:00 alle 06:00, dovrai difenderti da queste entità usando gli strumenti a tua disposizione.

### ⚙️ Meccaniche di Gioco

| Meccanica | Descrizione |
|-----------|-------------|
| 📹 **Telecamere** | Monitora la posizione di VAL-Z attraverso le telecamere di sorveglianza |
| 🛡️ **Firewall 1 & 2** | Attiva i firewall per bloccare i tentativi di hacking di VAL-Z alle porte dell'ufficio |
| 🎭 **Maschera Valsy** | Indossa la maschera per nasconderti da The Unknown quando entra in ufficio |
| ⚡ **Campo EM** | Gestisci il campo elettromagnetico per contenere The Singularity |
| 💻 **Hacking** | Difenditi dagli attacchi informatici con i minigiochi di hacking |
| 🌙 **5 Notti** | Ogni notte aumenta la difficoltà — sopravvivi fino alle 06:00 |

### 👾 Personaggi / Nemici

| VAL-Z | The Singularity | The Unknown |
|-------|----------------|-------------|
| <div align="center">🤖</div> | <div align="center">💻</div> | <div align="center">👻</div> |
| **Ex-mascotte robot** umanoide della compagnia, abbandonata e impazzita | **IA senziente** nata nei server abbandonati del lato destro | **Entità incappucciata** tenuta in una cella oscura |
| • Si muove stanza per stanza<br>• Tenta di hackerare i firewall<br>• Aggressività aumenta ogni notte | • Tenta di sincronizzare i processori<br>• Se il campo EM scende a 0%, causa blackout<br>• Disabilita le difese | • Cerca di hackerare la barriera energetica<br>• Comunica con suoni e sussurri<br>• Uccide all'istante se non indossi la maschera |
| **Difesa:** Firewall 1 e 2 | **Difesa:** Mantieni il campo EM attivo | **Difesa:** Maschera Valsy |

### 🖥️ Requisiti di Sistema

**Windows:**
- **OS:** Windows 7 o successivo
- **CPU:** Dual-core 2.0 GHz
- **RAM:** 2 GB
- **GPU:** Compatibile DirectX 9.0c
- **Storage:** 500 MB
- **Audio:** Scheda audio compatibile

### 🚀 Come Eseguire

1. Apri `SystemBreach-FiveNights/`
2. Avvia `SystemBreach-FiveNights.yyp` con GameMaker Studio 2
3. Premi **Play** (▶️) per eseguire il gioco

### 📁 Struttura del Progetto

```
SystemBreach-FiveNights/
├── SystemBreach-FiveNights/   # Gioco (GameMaker Studio 2)
│   ├── objects/               # oggetti (controller, bottoni, nemici, UI, telecamere)
│   ├── rooms/                 # stanze (menu, manuale, ufficio, telecamere, hacking, singularity, unknown, jumpscare, end)
│   ├── sprites/               # sprite (sfondi, bottoni, personaggi, UI, maschera)
│   ├── sounds/                # suoni (musiche, click, maschera, scossa, unknown)
│   ├── shaders/               # shader GLSL
│   ├── scripts/               # script (ridimensionamento, salvataggio)
│   ├── fonts/                 # font
│   ├── options/               # opzioni build (Windows, main)
│   └── datafiles/             # file dati (video cutscene, font, effetti)
├── Allegati/                  # Asset di design
│   ├── Assets/                # Asset originali (audio, bottoni, menu, personaggi, stanze, video, telecamere)
│   ├── Mockups/               # concept art
│   ├── Swimlane-UseCase-UML/  # diagrammi UML
│   └── Top-Secret/            # documenti di lore
└── README.md
```

### 🛠️ Tecnologie Utilizzate

- **GameMaker Studio 2** — IDE v2024.14.2.213
- **GameMaker Language (GML)** — Linguaggio di scripting
- **GLSL ES** — shader

### 📜 Crediti e Fonti

- **Musica di sottofondo:** [Freesound.org](https://freesound.org)
- **Effetti sonori:** [Freesound.org](https://freesound.org), audiomass.co
- **Video:** Kapwing, CapCut (montaggio)

---

## 🇬🇧 English

<div align="center">
*A tribute to Five Nights at Freddy's.*<br>
*Survive five nights in an abandoned building.*
</div>

---

### 🎮 Description

**System Breach: Five Nights** is a survival horror game developed with **GameMaker Studio 2**, inspired by the *Five Nights at Freddy's* saga. You play as a night security guard hired to watch over an abandoned telecommunications company building. Your shift runs from 00:00 to 06:00 for five nights. Use surveillance cameras, firewalls, and a mysterious mask to survive the hostile entities that inhabit the building.

### 📖 Story

A former futuristic telecommunications company abandoned its offices years ago, leaving behind machinery, servers, and secrets. The building is now haunted by three hostile entities. You are a night guard hired to monitor the building through security cameras. Each night, from 00:00 to 06:00, you must defend yourself using the tools at your disposal.

### ⚙️ Game Mechanics

| Mechanic | Description |
|----------|-------------|
| 📹 **Cameras** | Monitor VAL-Z's position through surveillance cameras |
| 🛡️ **Firewall 1 & 2** | Activate firewalls to block VAL-Z's hacking attempts |
| 🎭 **Valsy Mask** | Wear the mask to hide from The Unknown |
| ⚡ **EM Field** | Manage the electromagnetic field to contain The Singularity |
| 💻 **Hacking** | Defend against cyber attacks with hacking minigames |
| 🌙 **5 Nights** | Difficulty increases each night — survive until 06:00 |

### 🖥️ System Requirements

**Windows:**
- **OS:** Windows 7 or later
- **CPU:** Dual-core 2.0 GHz
- **RAM:** 2 GB
- **GPU:** DirectX 9.0c compatible
- **Storage:** 500 MB
- **Audio:** Compatible sound card

### 🚀 How to Run

1. Open `SystemBreach-FiveNights/`
2. Launch `SystemBreach-FiveNights.yyp` with GameMaker Studio 2
3. Press **Play** (▶️) to run the game

### 🛠️ Technologies Used

- **GameMaker Studio 2** — IDE v2024.14.2.213
- **GameMaker Language (GML)** — Scripting language
- **GLSL ES** — shaders

### 📜 Credits & Sources

- **Background music:** [Freesound.org](https://freesound.org)
- **Sound effects:** [Freesound.org](https://freesound.org), audiomass.co
- **Videos:** Kapwing, CapCut (video editing)

---

*System Breach: Five Nights — sviluppato con GameMaker Studio 2*
