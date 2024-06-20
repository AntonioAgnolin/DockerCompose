# Usar a imagem base do Node.js versão 14
FROM node:14

# Definir o diretório de trabalho no container
WORKDIR /app

# Copiar todos os arquivos do diretório atual para o diretório de trabalho no container
COPY . /app

# Instalar as dependências do projeto
RUN npm install

# Expor a porta 3001 para acesso externo
EXPOSE 3001

# Comando para iniciar a aplicação
CMD ["node", "index.js"]
