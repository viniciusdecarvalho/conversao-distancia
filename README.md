# conversao-distancia

# Criar imagem Docker
docker image build -t conversao-distancia:v1 .

# Iniciar container Docker
docker container run -it -d -p 80:80 --name conversao-distancia conversao-distancia:v1