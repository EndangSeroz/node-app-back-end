# notes-app-back-end

sudo apt-get install git
git --version
git config --global user.name "EndangSeroz"
git config --global user.emaail "official.seroz@gmail.com"
git init

{buat file .gitignore, isi :
node_modules
notes-api-webserver.pem}

git add .
git commit -m "initial commit"
git remote add origin https://github.com/EndangSeroz/notes-app-back-end.git
git push origin master
