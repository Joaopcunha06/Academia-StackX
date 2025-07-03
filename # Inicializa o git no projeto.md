# Inicializa o git no projeto
git init

# Adiciona a URL do repositório remoto (substitua pelo seu URL)
git remote add origin https://github.com/SEU_USUARIO/academia-stackx.git

# Adiciona todos os arquivos ao git
git add .

# Faz o commit inicial
git commit -m "Initial commit - projeto React academia-stackx"

# Cria branch principal (caso não exista)
git branch -M main

# Envia para o GitHub
git push -u origin main
