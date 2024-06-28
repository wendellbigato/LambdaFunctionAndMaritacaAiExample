# Função Lambda Simples para integração com Maritaca AI

Para criar a build e .zip da função e camada vá até o diretório da função ou camada e execute os comandos

´´´
Construa a imagem Docker

docker build -t my_lambda_function_builder .

Execute o contêiner e monte o diretório atual

docker run --rm -v $(pwd):/mnt my_lambda_function_builder

´´´

