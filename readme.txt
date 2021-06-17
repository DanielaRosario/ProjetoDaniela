# Projeto em Grupo QA Crew - Accenture 10 QE - Academia Gama

<b>Este projeto foi elaborado por:</b>
<ul>
<li>Camila Ribeiro Pinto https://github.com/camisarp</li>
<li>Cyntia Cybelle Lopes C. de Oliveira https://github.com/cyntialopes</li>
<li>Daniel Vidiri Neto https://github.com/dvidirin</li>
<li>Daniela Gon�alves do Ros�rio https://github.com/DanielaRosario</li>
<li>Daniela Martinez https://github.com/danizzo7</li>
<li>Danieli do Nascimento Baviera https://github.com/danibaviera</li>
<li>Samantha Bertozzi https://github.com/bert1307</li>
</ul>

# Descri��o do desafio
### Criar uma aplica��o Selenium com os seguintes casos de teste
### Caso de teste 1
Acessar o site da accenture, aceitar e configurar os cookies do LGPD<br>

<b>Cenario</b>: Aceitar o cookie LGPD<br>
Dado que o usuario esta no site da accenture<br>
Quando abre as configuracoes de cookies<br>
Quando clica em confirmar minhas escolhas<br>
Ent�o deve fechar a caixa de informacao<br>

<b>Cenario</b>: Configuracoes do cookie<br>
Dado que o usuario esta no site da accenture<br>
Quando abre as configuracoes de cookies<br>
Ent�o deve ver o item Sua privacidade<br>
Ent�o deve ver o item Cookies estritamente necessarias<br>
Ent�o deve ver o item Cookies Analiticos de Primeira Parte<br>
Ent�o deve ver o item Cookies de Desempenho e Cookies Funcionais<br>
Ent�o deve ver o item Cookies de Publicidade e Redes Sociais<br>

### Caso de teste 2
Acessar o site da accenture a mostrar a lista de servi�os<br>

<b>Cen�rio</b>: listar servi�os da Accenture<br>
Dado que o usuario esta no site da accenturee<br>
Quando clica no item servicos<br>
Ent�o deve mostrar os itens<br>
- Accenture Strategy
- Application Services
- Artificial Intelligence
- Automation
- Business Process Services
- Change Management
- Cloud
- Customer Experience
- Data & Analytics
- Ecosystem Partners
- Finance Consulting
- Industry X
- Infrastructure
- Marketing
- Mergers & Acquisitions (M&A)
- Operating Models
- Security
- Supply Chain Management
- Sustainability
- Technology Consulting
- Technology Innovation
- Zero Based Budgeting (ZBB)

<b>Cen�rio</b>: Clicar no servi�o de cloud<br>
Dado que o usuario esta no site da accenture<br>
Quando clica no item servicos<br>
Quando clica no item do menu cloud<br>
Ent�o deve encontrar o titulo servicos de cloud<br>

### Caso de teste 3
Acessar a lista de carreiras da Accenture<br>

<b>Cen�rio</b>: Acessar o item de vagas de tecnologia<br>
Dado que o usuario esta no site da accenture<br>
Quando clicar no menu carreiras<br>
Quando clicar no item do menu vagas em tecnologia<br>
Ent�o deve ver o destaque em Carreiras em Tecnologia<br>

<b>Cen�rio</b>: Acessar o item de vagas de tecnologia<br>
Dado que o usuario esta no site da accenture<br>
Quando clicar no menu carreiras<br>
Quando clicar no item do menu procure por vagas<br>
E pesquisa por desenvolvedor no campo de busca<br>
E clicar no botao search<br>
Ent�o deve ver a vaga de desenvolvedor<br>

###  Caso de teste 4                     
Sobre a accenture<br>

<b>Cen�rio</b>: Ver as caracter�sticas da accenture<br>
Dado que o usuario esta no site da accenture<br>
Quando clicar no item sobre a accenture<br>
Quando clicar no item de menu sobre a accenture<br>
Ent�o deve ver o destaque nosso proposito<br>

----------------------------------------------------------------------
link para a apresenta��o: https://www.canva.com/design/DAEhHsZj8NE/giFvaCj9FJqLcT4ucElcOA/view?utm_content=DAEhHsZj8NE&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent#1<br>
----------------------------------------------------------------------

## Ferramentas utilizadas 
:heavy_check_mark: <b>Java</b><br>
Linguagem de programa��o utilizada para programar os passos<br>

:heavy_check_mark: <b>Maven</b><br>
Gerenciador de depend�ncias<br>

:heavy_check_mark: <b>Cucumber</b><br>
Framework respons�vel para usar a linguagem Gherkin<br>

:heavy_check_mark: <b>Selenium</b><br>
Framework respons�vel por fazer a integra��o do c�digo Java com a linguagem Gherkin e automatiza��o do navegadore<br>

:heavy_check_mark: <b>JUnit</b><br>
Framework respons�vel por fazer a manuten��o e valida��o dos casos de testes<br>

--------------------------------------------------------------------
## Como utilizar
### Pr�-requisitos
Instalar programas abaixo de acordo com seu sistema operacional.<br>
- Instalar o java:
https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR
- Instalar jdk

- Instalar a IDE Eclipse

- Verificar se o JAVA_HOME est� configurado em seu computador<br>

### Baixar a tarefa do GitHub
- Estando no reposit�rio do projeto, clicar no bot�o "Code" (bot�o verde) e selecionar "Download ZIP"

- O arquivo vir� compactado, descompactar o arquivo<br>

### Para importar no Eclipse
- Com o Eclipse aberto, ir na op��o de menu File e em seguida selecionar "Open Projects from File System..."

- Na nova janela que se abriu, clicar no bot�o "Directory..." e escolher onde est� a pasta do projeto que foi descompactado

- Selecionar a "testFinalTricentis", que dever� estar dentro de outra pasta e clicar no bot�o "Selecionar pasta"

- O Eclipse ir� importar o projeto<br>

### Para executar a tarefa no Eclipse
- Ap�s importar o projeto, dar dois cliques em "src/test/java"

- Dois cliquem em "runner"

- Dois cliques em "RunnerCasoDeTesteUm.java, por exemplo se quiser executar o Caso 1"

- Abrindo o c�digo na janela central do Eclipse, clicar em qualquer lugar desses c�digos com o bot�o direito e selecionar "Run As" -> "1 Cucumber Feature"

- Caso seja aberto uma janela dizendo que h� um erro no Workspace do Eclipse, clique no bot�o "Proceed" que o c�digo ser� executado corretamente. Isso � um bug de importa��o do pr�prio Eclipse.

- O c�digo executar� com sucesso.

- Executar esses mesmos passos novamente para executar os Casos de teste, somente mudando o arquivo "RunnerCasoDeTesteXXX.java".

-------------------------------------------------------------------

# Obrigado pela Oportunidade!