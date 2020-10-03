
# Análise de Tarefas

## 1 - Sobre

<p align="justify"> Análise de Tarefa (AT) é o termo genérico para um conjunto de métodos para descrever as tarefas das
pessoas visando entender melhor os procedimentos para sua realização.[UsabGlossary]</p>

<p align="justify"> O enfoque básico da AT é descrever a tarefa como tendo um objetivo determinado
e um conjunto de passos envolvidos na sua realização. O nível de detalhe desta
descrição é determinado pelas intenções da AT. Uma melhor compreensão de tarefas pode auxiliar a delimitar um problema coletando informações de modo sistemático sobre um problema, organizar as informações coletadas, fazer predições de tempo de execução de tarefas, prevenir erros (identificando procedimentos difíceis e/ou confusos), auxiliar a identificar as fontes de problemas e gerar hipóteses para solucioná-los. AT é um processo interativo e iterativo, com períodos alternados de coleta, classificação e de interpretação de dados. Várias famílias de métodos de AT existem e entre as principais estão a Análise Hierárquica de Tarefas – abreviada AHT (Hierarchical Task Analysis – HTA), e a Análise Cognitiva de tarefas (Cognitive Task
Analysis). </p>

## 1.1 - AHT

<p align="justify"> AHT é a mais comumente utilizada, decompondo uma tarefa de modo top-down para formar uma hierarquia de subtarefas que por sua vez podem também ser decompostas sucessivamente. Em geral, sugere-se que a decomposição acabe quando for atingido um nível baixo de descrição em termos de ações elementares não decomponíveis </p>
<p align="justify">Tarefas com múltiplos níveis de decomposição apresentam relações, e estas podem ser do tipo sequencial (1>2), seleção (1/2) ou paralelo (1+2). (SILVA; BARBOSA, 2010, p. 193)</p>

## 1.2 - CTT

<p align="justify"> Os elementos da notação CTT são definidos em torno da idéia de que o objetivo do
usuário ao realizar uma tarefa pode ser traduzido como uma modificação do estado do
sistema ou uma consulta a um recurso do sistema. Assim, os modelos criados em CTT
podem ser interpretados como uma representação (de alto nível de abstração) dos
estados possíveis do sistema e do usuário durante a realização de uma tarefa específica.
Segundo esta abordagem, a execução de cada tarefa individual é capaz de modificar a
configuração de estados do sistema. O comportamento do modelo de tarefas é definido em CTT pela adição de
operadores temporais (tais como escolha, repetição, seqüência, etc.) entre as tarefas. A
existência de tais operadores temporais torna possível a modelagem de tarefas em
sistemas interativos. </p>
<p align="justify">A tabela abaixo apresenta os operadores, suas notações e descrições (SILVA; BARBOSA, 2010, p. 203).</p>

| Operador | Notação | Descrição
|------|----|----|
| Ativação | T1 >> T2 | T2 só pode iniciar após T1 terminar
| Ativação com passagem de informação | T1 []>> T2 | T2 só pode iniciar após T1 e a informação produzida por T1 é passada para T2
| Escolha | T1 [] T2 | Duas tarefas possíveis, entretanto, assim que uma é iniciada, a outra é desabilitada
| Tarefas concorrentes | T1 \|\|\| T2 | Podem ser realizadas em qualquer ordem ou ao mesmo tempo
| Tarefas concorrentes e comunicantes | T1 \| [] \| T2 | Podem ser realizadas em qualquer ordem ou ao mesmo tempo e também podem trocar informações
|Tarefas independentes | T1 \|=\| T2 | Podem ser realizadas em qualquer ordem, mas quando uma é iniciada, precisa terminar para iniciar a outra
| Desativação | T1 [> T2 | T1 é interrompida por T2
| Suspensão/retomada | T1 \|> T2 | T1 pode ser interrompida por T2 e é retomada ao ponto em que parou assim que T2 é terminada.


## 2 - Objetivos

### 2.1 - Fazer Login

Objetivos/operações | Problemas e recomendações | 
---- | ----------- |
0. Acessar ao SIGAA  | - |
1. Navegar até a página de Login | ação: navegar até a página de login <br/> feedback: o site apresentará o formulário de login |
2. Informar matrícula e senha | plano: informar dados de cadastro <br/> recomendado1: Aluno <br/> recomendado2: Servidor |
2.1 Verificar os dados de login | ação: inserir dados de nome de usuário e senha |
2.1.1  Confirmar login | ação: pressionar o botão login ou apertar enter. |

#### AHT Login

<p align="center">Figura 1 - AHT de Login</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/38164895/94977248-52a1e000-04ee-11eb-9447-94e430676ae0.png"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Login

<p align="center">Figura 2 - CTT de Login</p>
<div align="center">
    <img  src="https://user-images.githubusercontent.com/38164895/94978982-9dbff100-04f6-11eb-839d-78ff845065fb.png"/>
</div>
<p align="center">  Fonte: Autor </p>

###  2.2 - Fazer cadastro
Objetivos/operações | Problemas e recomendações | 
---- | ----------- |
0. Acessar o SIGGA | - |
1. Navegar até a página de cadastro | feedback:  o site irá carregar a tela de login inicialmente |
2. Clicar em cadastra-se aqui | ação: clicar no link cadastra-se. <br/> feedback: o site irá carregar a página de formulário |
3. Fazer Aluno | plano: informar dados de cadastro do aluno <br/> recomendado: Aluno |
3.1. Cadastro Servidor | plano: Informar dados de cadastro <br/> recomendado: Servidor|
3.1.1 - Preencher os dados  de Aluno ou Servidor| plano: o Aluno  ou Servidor deve informar: Matrícula, Nível, CPF, Nome Social, RG, Data de nascimento, E-mail, Ano/semestre inicial, Senha.  <br/> |
3. - Confirmar Cadastro | ação: pressionar o botão de confirmar cadastro. <br/> feedback: o site irá mostrar a página inicial do aluno ou servidor |

#### AHT Cadastro

<p align="center">Figura 3 - AHT de Cadastro</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/38164895/94979128-76b5ef00-04f7-11eb-9df9-724adfca850f.png"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Cadastro

<p align="center">Figura 2 - CTT de Cadastro</p>
<div align="center">
    <img  src="https://user-images.githubusercontent.com/38164895/94979107-5128e580-04f7-11eb-80e9-0c11ac1d416c.png"/>
</div>
<p align="center">  Fonte: Autor </p>

### 2.3 Visualizar calendário acadêmico

|Objetivos/operações | Problemas e recomendações |
|------------------- | ------------------------ |
|0. Visualizar calendário acadêmico| Plano: navegar até a página de listagem dos calendários e clicar no ícone de visualização
|1. Navegar até a página de listagem dos calendários| Plano: logar no sistema, e na página inicial, passar o mouse no menu Ensino e Clicar no calendário acadêmico
|1.1. Na página inicial, com o usuário logado, passar o mouse no menu Ensino|Feedback: um menu flutuante é aberto com as opções
|1.2. Clicar em Calendário Acadêmico|-
|2. Clicar no ícone de lupa associado ao calendário que se deseja visualizar|-

#### AHT Visualizar Calendário Acadêmico

<p align="center"> Figura 3 - AHT da visualição do Calendário Acadêmico</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/94999517-3fdfe780-0590-11eb-93a7-d061baf0c10b.png"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Visualizar calendário acadêmico

<p align="center"> Figura 4 - CTT da visualição do calendário acadêmico</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/94999552-6b62d200-0590-11eb-84e8-ee7a34a8e28a.png"/>
</div>
<p align="center">  Fonte: Autor </p>

### 2.4 Acessar dados de um componente curricular

|Objetivos/operações | Problemas e recomendações |
|------------------- | ------------------------ |
|0. Acessar dados de um componente curricular|Plano: preencher o formulário de busca e acessar a página do componente 
|1. Preencher o formulário de busca|Plano: navegar até a página do formulário, informar os dados de busca e clicar em buscar<br/> Input: campos do formulário para procurar componentes<br/> Feedback: a página exibe uma lista de itens baseada nos dados do formulário enviados
|1.1. Navegar até a página do formulário|Plano: acessar a página inicial, e no menu, selecionar Ensino, Consultas Gerais e clicar em Consultar Componente Curricular
|1.1.1. Com o usuário logado, acessar a página inicial|-
|1.1.2. No menu, selecionar Ensino, Consultas Gerais, e clicar em Consultar Componente Curricular|-
|1.2. Informar pelo menos um dos dados do componente que deseja acessar|Ação: Informar nível, código, nome da disciplina, pré-requisito, co-requisito, equivalência, unidade responsável, tipo do componente **ou** modalidade 
|1.3 Clicar em buscar |-
|2. Acessar a página do componente | Plano: Procurar o componente desejado e clicar no ícone de visualização
|2.1. Na lista aberta após o preenchimento do formulário, procurar o componente desejado |-
|2.2. Clicar no ícone de lupa (Visualizar o componente) |-

#### AHT Acessar dados de um componente curricular

<p align="center"> Figura 5 - AHT Acessar dados de um componente curricular</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/94999529-56863e80-0590-11eb-97c3-3e0c9f23afa9.png"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Acessar dados de um componente curricular

<p align="center"> Figura 6 - CTT Acessar dados de um componente curricular</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/94999574-86cddd00-0590-11eb-8dbe-56570a031fa2.png">
</div>
<p align="center">  Fonte: Autor </p>

###  2.5 - Visualizar Estrutura Curricular
Objetivos/operações | Problemas e recomendações | 
---- | ----------- |
0. Visualizar Estrutura Curricular 1>2| feedback:Estrutura correspondente ao curso mostrada em tela<br/>plano:Preencher o formulário da busca e selecionar a estrutura desejada |
1. Preencher Formulario de busca da estrutura 1>2>3 | input:Formulario de busca com curso,Matriz curricular,Código.<br/>ação:emitir um lista de curriculos.<br/>plano:Acessar a página de Busca da estutura curricular,selecionar os filtros de busca e clicar no botão "buscar" |
2. Selecionar Estrutura curricular desejada |<br/> feedback: o site irá carregar a página de com as diversas matérias que compõem o currículo<br/>plano:Selecionar a lupa correspondente ao currículo desejado |
1.1. Acessar a página de busca da estrutura curricular1>2 | plano: Usuário logado, percorrer o cursor até a opção"Ensino" e selecionar "Consultar Estrutura Curricular <br/> feedback:Página permitindo a busca do currículo<br> input:Formulario de busca com curso,Matriz curricular,Código |
1.2. Determinar um filtro de busca| input:Curso,Matriz Curricular,Código |
1.3 Clicar no botão "buscar| - |
1.1.1. Com o usuário logado percorrer o cursor até a opção "Ensino| - |
1.1.2. - Selecionar a Opção"Consultas Gerais" e clicar em "Consultar Estrutura Curricular"| - |
2.1. - Dentre as opções de matrizes curriculares, clicar no ícone da lupa correspondente| - |

#### AHT Visualizar Estrutura Curricular

<p align="center">Figura 7 - AHT Visualizar Estrutura Curricular</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/95003277-1b960200-05b4-11eb-94ba-c634b41badaf.jpg"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Visualizar Estrutura Curricular

<p align="center">Figura 8 - CTT de Visualizar Estrutura Curricular</p>
<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/95003292-47b18300-05b4-11eb-98b4-68b8362f3513.jpg"/>
</div>
<p align="center">  Fonte: Autor </p>

###  2.6 - Visualizar Historico
Objetivos/operações | Problemas e recomendações | 
---- | ----------- |
0. Visualizar Historico| Feedback: Documento referente ao histórico do aluno baixado<br/> Plano: Acesso ao arquivo disponibilizado pelo SIGAA  |
1. Acesso ao arquivo de Histórico sisponibilizado pelo SIGAA 1>2 | Plano:Logado o aluno deve percorrer,na página inicial,o cursor até a opção "Ensino" e selecionar a opção "Emitir Histórico" |
1.1.Logado o aluno deve percorrer,na página inicial,o cursor até a opção "Ensino"| - |
1.2. - Secionar a opção "Emitir Histórico| - |


#### AHT Visualizar Historico

<p align="center">Figura 9 - AHT de Visualizar Histórico</p>

<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/95003285-323c5900-05b4-11eb-9b50-615fff721423.jpg"/>
</div>
<p align="center">  Fonte: Autor </p>

#### CTT Visualizar Historico

<p align="center">Figura 10 - CTT de Visualizar Histórico</p>
<div align="center">
    <img  src="https://user-images.githubusercontent.com/47457792/95003293-5a2bbc80-05b4-11eb-90db-f7a78fbf1bbe.jpg"/>
</div>
<p align="center">  Fonte: Autor </p>


## **Histórico de revisões**
Autor | Versão | Data(dd/mm/aaa) | Descrição 
---- | ----------- | ------ | ---------
Lucas Lopes| 1.0 | 02/10/2020 | Criação do documento. <br/> Criação dos objetivos 2.1 e 2.2 e seus respectivos modelos de tarefas.
Murilo Schiler| 1.1 | 03/10/2020 | Acréscimo no Documento. <br/> Criação dos objetivos 2.5 e 2.6 e seus respectivos modelos de tarefas.
Wagner Martins| 1.2 | 03/10/2020 | Acréscimo no Documento. <br/> Criação dos objetivos 2.3 e 2.4 e seus respectivos modelos de tarefas.

## **Referências**
 * <p align="justify">WINCKLER, M. A. A; PIMENTA, Marcelo Soares. Análise e Modelagem de Tarefas : IHC2004 (Tutorial).  LIIHS-IRIT, Curitiba, v. 1, n. 1, p. 1-29, out./2004. Disponível em: https://www.irit.fr/~Marco.Winckler/publications/2004-IHC-tutorial.pdf. Acesso em: 2 out. 2020.</p>
 * <p align="justify"> BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. Interação Humano computador. Elsevier. Ed. 1. 2010.