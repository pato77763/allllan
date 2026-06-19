echo "# allllan" >> README.md git init git add README.md git commit -m "primeiro commit" git branch -M main git remote add origin https://github.com/pato77763/allllan.git git push -u origin main
echo "# allllan" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git branch -M main 
git remote add origin https://github.com/pato77763/allllan.git
 git push -u origin main
# 1. Adiciona as imagens comprimidas e os arquivos limpos
git add .

# 2. Cria o commit de atualização
git commit -m "Ajuste: imagens comprimidas e remocao de video"

# 3. Garante que está na branch principal
git branch -M main

# 4. Envia de forma limpa ao GitHub (forçando a atualização correta)
git push -u origin main -f
git vite buld
