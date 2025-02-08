git clone https://github.com/Pettra22/abigail_gonzalez.git
cd abigail_gonzalez
git checkout -b AG_PROC_INF
echo "print('Hola Mundo')" > app.py
git add app.py
git commit -m "Añadiendo archivo de código fuente"
git push origin AG_PROC_INF
git checkout main
git pull origin main
git merge AG_PROC_INF
git push origin main
git tag CODE_200
git push origin CODE_200

