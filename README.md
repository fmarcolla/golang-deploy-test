# Criar Imagem
docker build -t fmarcoll/godeploy:latest .

# Rodar Imagem
docker run --rm -p 8080:8080 fmarcoll/godeploy:latest

# Enviar Imagem para o DockerHub
docker push fmarcoll/godeploy:latest

