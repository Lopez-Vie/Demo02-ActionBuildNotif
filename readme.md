# Demo 02 - CICD

## Pour lancer le projet démo
```yml
# Installation des Node_Modules
npm i

# Tester le code
npm run test

# Build le projet TS → JS
npm run build

# Lancer le projet buildé
npm run start
```

## Mise en place d'un action CI/CD (Github)
- Créer le repertoire `.github/workflows`
- Dans celui-ci, créer une fichier `<action-name>.yaml`
- Dans le fichier « workflow » définir :
    - Le nom du workflows
    - Les déclancheurs
    - Les jobs
