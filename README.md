# vuepraktik – Praktik Vendre

Ett Vue-projekt från min praktik på Vendre (2024). Projektet demonstrerar frontend-utveckling med Vue 3, JavaScript och API-integration.

## Om projektet

1. **Vue-projektstruktur:**
   - `src/App.vue`: Huvudkomponenten som laddar data och visar en lista över anställda.
   - `src/components/EmployeeCard.vue`: En komponent för att visa varje anställd med en rund profilbild och en e-postlänk.

2. **Responsiv design:**
   - Flexbox används i `App.vue` för att arrangera anställdas kort i en flexibel och responsiv layout.

3. **Runda profilbilder och kontaktlänkar:**
   - CSS används i `EmployeeCard.vue` för att göra profilbilder runda och skapa stil för e-postlänkar.

4. **Dynamisk datahantering:**
   - Axios används för att hämta anställdas data från ett API (`https://reqres.in/api/users`) och ladda fler data vid behov.

## Tekniker
- Vue.js 3
- JavaScript / HTML / CSS
- Axios (API-anrop)
- REST API (reqres.in)
- npm, Babel, ESLint

---

## Projektinstruktioner (standard från Vue CLI)

### Project setup
```bash
npm install
```

### Compiles and hot-reloads for development
```bash
npm run serve
```

### Compiles and minifies for production
```bash
npm run build
```

### Lints and fixes files
```bash
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).




