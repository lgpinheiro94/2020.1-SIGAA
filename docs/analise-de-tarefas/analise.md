
# Análise de Tarefas

<p align="justify"> Análise de Tarefa (AT) é o termo genérico para um conjunto de métodos para descrever as tarefas das
pessoas visando entender melhor os procedimentos para sua realização.[UsabGlossary]</p>

<p align="justify"> O enfoque básico da AT é descrever a tarefa como tendo um objetivo determinado
e um conjunto de passos envolvidos na sua realização. O nível de detalhe desta
descrição é determinado pelas intenções da AT. Uma melhor compreensão de tarefas pode auxiliar a delimitar um problema coletando informações de modo sistemático sobre um problema, organizar as informações coletadas, fazer predições de tempo de execução de tarefas, prevenir erros (identificando procedimentos difíceis e/ou confusos), auxiliar a identificar as fontes de problemas e gerar hipóteses para solucioná-los. AT é um processo interativo e iterativo, com períodos alternados de coleta, classificação e de interpretação de dados. Várias famílias de métodos de AT existem e entre as principais estão a Análise Hierárquica de Tarefas – abreviada AHT (Hierarchical Task Analysis – HTA), e a Análise Cognitiva de tarefas (Cognitive Task
Analysis). </p>

## AHT

<p align="justify"> AHT é a mais comumente utilizada, decompondo uma tarefa de modo top-down para formar uma hierarquia de subtarefas que por sua vez podem também ser decompostas sucessivamente. Em geral, sugere-se que a decomposição acabe quando for atingido um nível baixo de descrição em termos de ações elementares não decomponíveis </p>

## CTT

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




## **Histórico de revisões**
Autor | Versão | Data(dd/mm/aaa) | Descrição 
---- | ----------- | ------ | ---------
Lucas Lopes| 1.0 | 02/10/2020 | Criação do documento. <br/> Criação dos objetivos 2.1 e 2.2 e seus respectivos modelos de tarefas.

## **Referências**
 * <p align="justify">WINCKLER, M. A. A; PIMENTA, Marcelo Soares. Análise e Modelagem de Tarefas : IHC2004 (Tutorial).  LIIHS-IRIT, Curitiba, v. 1, n. 1, p. 1-29, out./2004. Disponível em: https://www.irit.fr/~Marco.Winckler/publications/2004-IHC-tutorial.pdf. Acesso em: 2 out. 2020.</p>