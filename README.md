# 💇‍♂️ GoBarber Web 💪

A aplicação Gobaber Web foi desenvolvida no BootCamp da RocketSeat.

Gobarber Web é aplicação React Js que consiste em cadastro de novos barbeiros e gerenciamento de atendimento aos seus clientes. O profissional de barbearia consegue organizar os seus horários tendo acesso ao dia e horários de cada dia, é um app completo que possibilita agilidade eficácia no atendimento de cada precioso cliente .

![](https://github.com/brenokf/GoBarber/blob/master/Front-End/github/GoBarber.gif?raw=true)


#### Bibliotecas Utilizadas

 - Axios
 - Yup
 - React Dom
 - Unform Web
 - Unform Core
 - React Icons
 - Styled Components

#### To start, **Docker** is required

### :rocket: How to install and start
- `git clone https://github.com/Alessandro1979-itac/GoBarber`
- **Go to repository folder**
- `docker-compose up` (in Backend)
- `yarn start` (in Frontend)

### :page_facing_up: Routes in Backend

- **post('/users')** - Create a login
- **post('/sessions')** - Log in to an account

#### From here, authentication is required

- **put('/users')** - Update an account
- **get('/providers')** - List providers
- **get('/providers/:providerId/available')** - Check provider availability
- **post('/appointments')** - Create an appointment
- **get('/appointments')** - List all logged-in user's appointments
- **delete('/appointments/:id')** - Delete an appointment
- **get('/schedule')** - Schedule services
- **post('/files')** - Profile pictures
- **get('/notifications')** - List all logged in user notifications
- **put('/notifications/:id')** - Confirm notification was seen

###  Como Rodar o Projeto na sua Maquina
###### Para rodar na sua maquina, recomendo o comando **yarn** ou **mpn install** acessando a raiz do projeto no comando você pode apenas dar o um dos comandos abaixo, com isso irá instalar as depencias contidas no arquivo package.json
    yarn
    npm install

###### Todas as depencias serão instaladas no seu projeto na pasta **node_modules**

### Rodando o Projeto
###### Para rodar o projeto você precisa do seguinte comando

###### No Front-End
    yarn start

###### No Back-End
    yarn dev

##### Fique tranquilo ja deu tudo certo , agora será aberta uma janela no seu navegador padrão e pronto e vualá este projeto está rodando no seu pc
😃 🤩

<p align="center">
Made with ♥ by <a href="https://www.linkedin.com/in/alessandro-muniz-caranha">Alessandro</a>
</p>
