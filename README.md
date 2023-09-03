# fc-desafio-go

## Desafio FC: Imagem Go <2MB

### Docker

1. Desafio:
   - Criar uma imagem docker para rodar um programa na liguagem GO. Onde a imagem tenha menos de 2MB.
2. Solução
   - Criei um dockerfile utilizando a funcionalidade Multi-stage builds.
     - Primeira parte: Criei a imagem para compilar o programa
     - Segunda parte: Montei a imagem final utilizando o scratch, para otimizar o tamanho da imagem final para <2MB.
4. Imagem:
   - https://hub.docker.com/r/viniciusvieira/fullcycle
