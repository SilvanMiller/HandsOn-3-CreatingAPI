# **Hands on 3 - #43 - La Vie**
Um grupo de amigos psicólogos se juntaram e criaram a clínica La Vie - Saúde Mental que oferece diversos tipos de terapia aos seus pacientes. 

Com o intuito de melhor atender, agilizar e documentar todas as consultas e atendimentos.
Buscam uma API que proporciona-se criar os registros dos psicólogos, pacientes e prontuários diarios.

<hr>

### **Documentação da API [documentação](https://documentaçãoDoPostmanOuInsonia)**

<hr>

## **Banco de dados relacional**
Criação do DER no banco de dados
imagem do banco de dados ![der]()

<hr>

## **API** 
Foram utilizado Sequelize mais Express na construção e assim dividido em 5 etapas:
<br>
* Login
* Pacientes
* Psicólogos
* Atendimento 
* Dashboard
    <br>
    <br>

## **login**
No área de login é feito uma autenticação de e-mail e senha q tem como resposta um token gerado pelo [JWT](https://www.npmjs.com/package/jsonwebtoken)

## **Pacientes**
Feito um CRUD bem simples que cosnta na documentação.

## **Psicólogos**
O CRUD foi utilizado o pacote [bcrypt](https://www.npmjs.com/package/bcrypt) fazendo a criptografia para cadastro quanto no login para novos acessos. 

### **Atendimentos**

Para criação do atendimento é necessário uma autorização. Essa autorização é feita pelo token.

### **Dashboard**
O Dashboard vai trazer informações mais simples, como número de psicólogos, pacientes, atendimentos e a media entre atendimentos por psicólogos.

<hr>
<br>

## **Desenvolvedores**
Desenvolvido pela equipe  
[nome](link_do_github), 
[nome](link_do_github), 
[nome](link_do_github), 
[Silvan](https://github.com/SilvanMille)
