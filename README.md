A API retorna uma lista de filmes com a maior bilheteria até este momento (nov/2023).

## Instruções para executar a API na sua máquina

Primeiramente, baixe este repositório na sua máquina (ou clone-o).

### Instale o NodeJS

Se você ainda não possui o NodeJS instalado, é a hora de baixá-lo. Acesse o **[site oficial do NodeJS](https://nodejs.org/),** faça o download da versão recomendada e siga os passos da instalação.

Você precisa ter o NodeJS instalado na sua máquina, pois a API é feita com NodeJS, um ambiente de execução JavaScript do lado do servidor, permitindo o desenvolvimento de aplicações web escaláveis e assíncronas.

Não se preocupe se você não souber Javascript ou NodeJS! O objetivo aqui é apenas executar a nossa API, de onde vamos consumir os dados, salvar agendamentos de consulta, etc.

### Execute a API

- Abra o terminal;
- Navegue até o diretório onde baixou o projeto da API, utilizando o comando `cd <caminho-para-o-projeto>`;
- Execute `npm install -g json-server` para instalar todas a dependência do projeto;
    - Se der algum erro na instalação por conta de permissão, execute o `sudo npm install -g json-server` para instalar como administrador;
- Por fim, digite `json-server --watch db.json` para iniciar a API.

Pronto! Agora, a API estará rodando localmente em sua máquina e estará pronta para receber as requisições.
