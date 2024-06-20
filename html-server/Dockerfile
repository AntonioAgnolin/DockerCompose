# Usando a imagem oficial do nginx
FROM nginx:latest

# Remover configuração padrão do nginx
RUN rm /usr/share/nginx/html/*

# Copiar o conteúdo do html-server para o diretório padrão do nginx
COPY . /usr/share/nginx/html

# Expor a porta 80
EXPOSE 80
