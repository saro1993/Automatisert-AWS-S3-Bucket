# Automatisert AWS S3 Bucket Liste med GitHub Actions og Secrets

## Introduksjon
I moderne programvareutvikling er det avgjørende å kunne automatisere og strømlinje prosesser for å forbedre effektiviteten og påliteligheten. En viktig del av denne automatiseringen er integrasjonen av skytjenester som Amazon Web Services (AWS) med verktøy som GitHub. I denne oppgaven vil du lære å opprette en GitHub Actions workflow som bruker AWS Command Line Interface (CLI) for å liste alle S3-bøtter i en AWS-konto. Dette vil gi deg en dypere forståelse av automatisering og sikkerhetsprinsipper i DevOps-praksis.

## Oppgavebeskrivelse

### 1. Opprett GitHub Secrets
- Opprett to GitHub repository secrets: `AWS_ACCESS_KEY_ID` og `AWS_SECRET_ACCESS_KEY`. Disse vil bli brukt til å autentisere mot AWS-kontoen din.

### 2. GitHub Actions Workflow
- Lag en GitHub Actions workflow-konfigurasjonsfil (f.eks. `.github/workflows/aws-s3-list.yml`) i repoet ditt. Denne filen skal definere selve arbeidsflyten.

### 3. Workflow Handlinger
- Bruk nøkkelverdiene fra GitHub repository secrets (`AWS_ACCESS_KEY_ID` og `AWS_SECRET_ACCESS_KEY`) i arbeidsflyten for å autentisere AWS CLI.
- Bruk AWS CLI til å liste alle S3-bøtter i den tilknyttede AWS-kontoen.
- Skriv resultatene til en fil eller vis dem i arbeidsflytens logg.

### 4. Testing og Validering
- Kjør arbeidsflyten manuelt ved hjelp av GitHub Actions grensesnittet for å sikre at den fungerer som forventet.

### 5. Dokumentasjon
- Oppdater README-filen i repoet ditt med en kort beskrivelse av arbeidsflyten og hvordan man konfigurerer repository secrets.

Merk: Sørg for å følge beste praksis for sikkerhet når du håndterer hemmelige nøkler og tilgang til skyressurser. Denne oppgaven vil gi deg verdifull erfaring i å automatisere skyrelaterte oppgaver og forbedre prosessene i utviklingsprosjekter.
