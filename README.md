# inițializare repo local
git init
# adăugare fișiere
git add .
# commit inițial
git commit -m "Initial project setup"
# adăugare remote
git remote add origin https://github.com/<mihailisneac>/<ST_IND_PAD_NR1>.git
# împingere pe main
git branch -M main
git push -u origin main

# flux zilnic de lucru
git checkout -b feature/sincronizare
git add .
git commit -m "Implementare modul sincronizare"
git push -u origin feature/sincronizare

# actualizare repo
git pull origin main
