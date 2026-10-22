# MindCore 

**Asistent inteligent pentru învățare, bazat pe inteligență artificială**

MindCore este o aplicație web dezvoltată pentru a facilita procesul de învățare prin intermediul inteligenței artificiale. Proiectul își propune să ofere utilizatorilor un spațiu digital în care pot interacționa cu un asistent AI și își pot organiza activitățile de studiu.

Aplicația este funcțională și se află în continuă dezvoltare, urmărind îmbunătățirea experienței utilizatorilor și extinderea funcționalităților existente.

## Funcționalități

- **Asistent AI** – interacțiune conversațională pentru sprijin în procesul de învățare.
- **Gestionarea conversațiilor** – organizarea și accesarea conversațiilor cu asistentul.
- **Autentificare** – acces la funcționalitățile aplicației prin intermediul contului de utilizator.
- **Încărcarea documentelor PDF** – utilizarea documentelor ca resurse pentru activitățile de studiu.
- **Căutare semantică** – valorificarea tehnicilor de căutare bazate pe similaritatea semantică a informațiilor.
- **Arhitectură full-stack** – integrarea interfeței web cu un backend și servicii de stocare a datelor.
- **Rulare cu Docker** – configurarea serviciilor aplicației într-un mediu containerizat.

## Tehnologii utilizate

### Frontend
- React
- JavaScript
- npm

### Backend
- Python
- FastAPI

### Baze de date și inteligență artificială
- PostgreSQL
- Qdrant
- Sentence Transformers
- Groq API

### Infrastructură
- Docker
- Docker Compose

## Structura proiectului

```text
proiectAI/
├── backend/            # Logica aplicației și serviciile backend
├── frontend/           # Interfața web
├── docker-compose.yml  # Configurarea serviciilor Docker
├── package.json        # Scripturi și dependențe Node.js
├── package-lock.json   # Versiunile dependențelor npm
├── .gitignore          # Fișiere excluse din Git
└── readme.md           # Documentația proiectului
```

## Instalare și rulare

### Cerințe preliminare

Înainte de pornire, asigură-te că ai instalate:
- Git
- Docker și Docker Compose
- Node.js și npm, dacă sunt necesare pentru rularea sau dezvoltarea frontendului în afara containerelor
- Cheile API și variabilele de configurare necesare serviciilor externe

### 1. Clonarea repository-ului

```bash
git clone https://github.com/cristinaa17/mindcore-ai-study-assistant.git
cd mindcore-ai-study-assistant
```

### 2. Configurarea variabilelor de mediu

Configurează variabilele necesare pentru backend, baza de date, serviciile AI și celelalte servicii externe, conform configurației proiectului.

**Nu publica parole, chei API sau fișiere `.env` care conțin informații secrete.**

### 3. Pornirea aplicației

Dacă serviciile sunt configurate pentru pornire prin Docker Compose, rulează:

```bash
docker compose up --build
```

Pentru oprirea serviciilor:

```bash
docker compose down
```

> Notă: comenzile și variabilele exacte pot depinde de configurația actuală a proiectului. Consultă fișierele de configurare din `backend/`, `frontend/` și `docker-compose.yml`.

## Direcții de dezvoltare

Proiectul poate fi extins prin:
- îmbunătățirea răspunsurilor și a contextului utilizat de asistentul AI;
- extinderea funcționalităților de lucru cu documente;
- îmbunătățirea interfeței și a experienței utilizatorilor;
- optimizarea căutării semantice și a recuperării informațiilor;
- extinderea testelor automate și a documentației tehnice;
- consolidarea securității și a gestionării erorilor.

Acestea reprezintă direcții de dezvoltare, nu neapărat funcționalități deja implementate.

## Stadiul proiectului

MindCore este o aplicație funcțională, aflată în dezvoltare continuă. Repository-ul documentează implementarea actuală și evoluția proiectului.

---

*MindCore – tehnologie și inteligență artificială în sprijinul învățării.*
