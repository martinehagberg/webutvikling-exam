# 🎾 SportsWorld - Web Application

En fullstack webapplikasjon utviklet som eksamensprosjekt i webutvikling (DS3103).  
Applikasjonen gir brukeren mulighet til å administrere tennisspillere (athletes), arenaer (venues) og økonomi (finance).

---

## Funksjonalitet

Applikasjonen består av flere sider og funksjoner:

### Home
- Oversikt over applikasjonen
- Navigasjon til alle sider
- Visuell presentasjon av innhold

### Athletes
- Se alle spillere
- Registrere nye spillere
- Redigere og slette spillere
- Opplasting av bilder

### Venues
- Oversikt over tennisarenaer
- Legge til, redigere og slette venues
- Visning av kapasitet og bilder

### Finance
- Oversikt over økonomi
- Se saldo, forbruk og kjøp
- Ta opp lån
- Kjøpe spillere

---

## Teknologier

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Context API

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- SQLite

### Andre verktøy
- Axios (API-kall)
- Swagger (testing av API)

---

## Arkitektur

Prosjektet er strukturert med tydelig skille mellom frontend og backend:

- **Frontend:** komponentbasert struktur med pages, components, context og services
- **Backend:** controllers, modeller og database via Entity Framework
- **Kommunikasjon:** REST API via Axios

State håndteres globalt med Context API:
- AthleteContext
- VenueContext
- FinanceContext

Dette gjør at data oppdateres automatisk i hele applikasjonen.

---

## Hva jeg har lært

Gjennom dette prosjektet har jeg lært:

- Fullstack utvikling (frontend + backend)
- Hvordan koble React til et API
- Bruk av TypeScript 
- Strukturering av større prosjekter
- CRUD-operasjoner i både frontend og backend
- State management med Context API
- Samarbeid med GitHub og håndtering av merge conflicts

---

## Universell utforming

- Responsivt design (fungerer på mobil og desktop)
- God kontrast og lesbarhet
- Tastaturnavigasjon
- Semantisk HTML og labels
- Alt-tekst på bilder

---

## Screenshots

<img width="794" height="445" alt="Skjermbilde 2026-03-17 kl  20 42 42" src="https://github.com/user-attachments/assets/588c66ff-69b2-4bbb-9376-ed4eea00ac2d" />

<img width="794" height="445" alt="Skjermbilde 2026-03-17 kl  20 43 15" src="https://github.com/user-attachments/assets/97a762a3-c405-4dfd-960e-eb23f6cecd6e" />

<img width="794" height="445" alt="Skjermbilde 2026-03-17 kl  20 43 40" src="https://github.com/user-attachments/assets/377d10b3-275e-4742-857f-a13c92729cc6" />
