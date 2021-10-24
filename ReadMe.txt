Comandos Básicos do Docker:

---- Comandos Básicos Linux/Docker

Validar todas as opções
# Docker

Validar a versão do Docker
# Docker --version 

Limpar a Tela 
# Clear 

Mostrar Conteúdo da pasta 
# ls

Criar um diretório 
# mkdir 

Se mover entre diretórios 
# cd

Autompletar algum comando 
- Pressionar tecla "TAB"

Iniciar um Container 
# Docker container run (nome da imagem)

Listar Containers
# Docker ls

Listar todos os Containers
# Docker container ls --all ou "-a"

Criar um container e especificar uma imagem 
# docker container run --name(nome da imagem)

Iniciar um container
# Docker Container Start (nome ou ID do Container)

Parar um container em execução 
# Docker Container Stop (nome ou ID do Container)

Remover um container (Parado)
# Docker container rm (ID do container em questão)

Remover um container que está rodando 
# Docker container rm --foce (ID co container em questão)

Obter informações adicionais sobre um container 
# Docker container inspect (nome do container)

Realizar requisições http pelo próprio terminal 
# curl (IP do container)

Acessar um container 
# Docker container exec -t (terminal) -i(interativo) (nome do container) bash 