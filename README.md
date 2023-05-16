# Config Git
git config –-global user.name "usuario"
git config –-global user.email "email@dominio.com"

# Crear repo en GitHub

# En cliente
mkdir repodemo1
cd repodemo1
echo "# repodemo1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/utpcix/repodemo1.git
git push -u origin main