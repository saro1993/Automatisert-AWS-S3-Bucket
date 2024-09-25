# Automatisert AWS S3 Bucket Liste med GitHub Actions og Secrets

## Introduksjon

I denne oppgaven skal du lage en GitHub Actions workflow som bruker AWS Command Line Interface (CLI) for å liste alle S3-bøtter i vår AWS-konto. 
 
## Beskirvelse 
- Lag en GitHub Actions workflow
- I din workflow; Bruk AWS CLI til å liste alle S3-buckets i  AWS-kontoen vår. Alle CLI kommandoer for s3 starter med ```aws s3 .. ``` 
- Opprett nødvemndige GitHub repository secrets, hvis ikke din IAM bruker har "access keys" så må du også lage det- 
  
### 4. Bonus 
- Klarer du å gjøre det slik at  arbeidsflyten kan startes manuelt ved hjelp i GitHub Actions GUI? Spør ChatGPT eller google "workflow_dispatch"  
