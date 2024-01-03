# AMZMP - CodeIgniter
## Indíce
- [Instalar](#instalar-)
- [Objetivo](#objetivo)
- [Descrição](#descrição)
- [Uso](#uso)
- [Licença](#licença)

## Instalar 🛠️
<sub>Passo a passo de como instalar e rodar a aplicação na sua máquina.</sub>
- Banco de Dados: Verifique de estar utilizando o banco de dados relacional MySql, e que o mesmo esteja alocado na porta default (:3306), certifique que o servidor está rodando. <pre>Endereço Default = http://localhost:3306/ </pre>
- Git clone: pegue o endereço de clonagem do repositório aqui no GitHub em Code -> Local -> Clone -> HTTPS, execute: <pre>git clone ENDEREÇO_REPOSITÓRIO</pre>
- Instalando dependências: entre na pasta raiz do projeto e execute o comando: <pre>composer install</pre>
- Contruir tabelas: para que o projeto possa armazenar informações, deve ser utilizadas tabelas do banco de dados, então devemos rodas as migrations do projeto para a tabela ser gerada automaticamente, vá até a pasta raiz do projeto e execute: <pre>php spark migration</pre>
- Executar código: após seguir todos os passos, você deve iniciar o servidor da aplicação, para que possa acessar e realizar a utilização, para isso execute: <pre>php spark serve</pre>
