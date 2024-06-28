Os arquivos extraídos incluem:

1. `README.md`
2. `src/Dockerfile`
3. `src/lambda_function.py`
4. `src/lambda_layer/Dockerfile`
5. `src/lambda_layer/lambda_layer.zip`

### Conteúdo do README.md Atual

Vou ler o conteúdo atual do arquivo README.md e depois criar um novo README.md com base nas informações dos arquivos fornecidos.

Vamos começar lendo o conteúdo atual do README.md:

### Novo Conteúdo do README.md

Aqui está um exemplo de um novo `README.md` que pode ser adequado para o repositório com base na estrutura e nos arquivos fornecidos:

```markdown
# LambdaFunctionAndMaritakaAiExample

Este repositório contém um exemplo de função Lambda da AWS e uma camada Lambda configurada com um ambiente de desenvolvimento Docker.

## Estrutura do Repositório

- `src/`
  - `Dockerfile`: Dockerfile para configurar o ambiente de desenvolvimento.
  - `lambda_function.py`: Script Python que define a função Lambda.
  - `lambda_layer/`
    - `Dockerfile`: Dockerfile para criar a camada Lambda.
    - `lambda_layer.zip`: Arquivo zip contendo as dependências da camada Lambda.

## Configuração do Ambiente de Desenvolvimento

### Docker

Para configurar o ambiente de desenvolvimento usando Docker, siga os passos abaixo:

1. Navegue até o diretório `src`:
   ```sh
   cd src
   ```

2. Construa a imagem Docker:
   ```sh
   docker build -t lambda-function .
   ```

3. Execute o container Docker:
   ```sh
   docker run -it lambda-function
   ```

### Função Lambda

O arquivo `lambda_function.py` contém o código da função Lambda. Para implementar a função Lambda na AWS, você pode seguir os passos abaixo:

1. Crie uma função Lambda na AWS.
2. Faça o upload do arquivo `lambda_function.zip`.
3. Configure a camada Lambda criada a partir do Dockerfile em `lambda_layer`.


