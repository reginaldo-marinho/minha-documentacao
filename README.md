Essa documentação é destinada a minha análise pessoal
sobre o meu desempenho profissional.

# Javascript 
## Core
1. Básico
 - [x] Variáveis
 - [x] Números e operadores
 - [x] Textos
 - [x] Arrays 
2.  Estrutura
 - [x] Condicionais
 - [x] tratamento de erros
 - [x] Laços de Repetição
 - [x] Funções
 - [x] Eventos
 - [x] Módulos
 - [ ]  
3. Objetos
 - O básico dos objetos
 - Protótipos
 - Herança
 - JSON
## Intermediário

## Avançado
- Herança
- Protótipos
- Modo Estrito
- Vetores Tipados
- Gerenciamento de Memória
- Modelo de concorrência e event loop

# C# 
## core
1. Tipos de dados
- por valor
- por referência
2. Estrutura
- Namespaces
- programas
- Tipos
- Assemblies
3. Orientação a objetos
- classe
- interface
- classes abstratas
- membros da classe
4. Áreas da linguagem
- matrizes
- coleções
- LINQ
- Delegates
- Expressões labda
- Métodos sincronos e assincronos
- Atributos
5. Tratamentos de erros

## Memória
### Conceitos Básicos
#### Alocação de Memoria
Na linguagem c# seu codígo é conhecido como codigo gerenciavel, isso porque o proprio COMMON Language Runtime ou CLR gerencia o codigo, as linguagem c/c++ não contém um tipo de CLR, dessa forma quem será responsavel pelo gerenciamento desse codigo, em especial, o gerenciamento de memoria, será o proprio desenvolvedor.
- O proprio CLR gerencia a memoria do codigo compilado e executado
- Quando um  processo é executado, o runtime reserva um espaço na memória
- O espaço reservado pelo CLR é chamado de HEAP
- tipos de referencias são alocados no HEAP

#### Liberação de Memoria
  coletor de lixo libera as memorias dos objetos que não estão sendo mais utilizadas pelo aplicativo, isso é feito com base nas raises do aplicativo.
 Raizes do Aplicativo são:
 - campos estaticos
 - varaveis locais
 - parametros na pilha de um thread
 - registros da CPU
 
1. Estados de Memória
- gratuita
> O bloco de memória não contém referências e ele está disponível para alocação 
- reservada
> O bloco de memória está disponível para seu uso e não pode ser usado para nenhuma outra solicitação de alocação. No entanto, você não pode armazenar dados nesse bloco de memória até que ele esteja comprometido.
- confirmada
> O bloco de memória é atribuído para armazenamento físico.

Nesse link existe um ótimo artigo explicando sobre a [diferença ente memória stack e memória heap](https://www.c-sharpcorner.com/article/stack-vs-heap-memory-c-sharp/) 

# Arvores Binarias
### Resumão
Arvores binarias é um conjunto de dados que são inseridos de forma organizada, de modo que quando os mesmos são obtidos, o tempo de processamento diminui, ja que o dado desejado é encontrado de uma forma mais rapida.

### Árvore Binaria de busca
No caso abaixo, se fomos buscar o numero 4, devemos fazer operações logicas entre o ramo esquedo e o direiro, a partir da raiz da arvore, que nesse caso é o 8, vejamos:

A logica usada para buscar um elemento dentro de uma arvore é:
- EI = O elemento do nó é igual ao procurado?
- DI = Se sim, vá para a direita
- ES = Se não, vá para a esquerda

chagando ao elemento  4 
```
inicio 
8 == 4 {false}
8 > 4 {ES}
3 == 4 false
3 > 4 {DI}
6 == 4 {false}
6 > 4 {ES}
4 == 4 {true}
fim

```
> ![Exemplo de Arvore Binaria](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRFmlprp5ozA302T9Vndm0olGuLKu1MefaPe5_t7PmmiHrZEdCkkMojBOzoMmS_9fvWDys&usqp=CAU)

# Compressão de Dados
É a arte de reduzir o tamanho de um arquivo de acordo com o que ele tem, exemplo:
Se eu tenho um arquivo "AAAAAA", eu posso representalo usando  6A, que é uma redução de mais de 80% no disco.


# SQL Server
1. O básico
- Os mais básicos do sql server são:
 Create, alter, Drop e Select para operações ligadas a tabelas
Views, procedures, índices, PKS, FKS, funções, esquemas...
- Create, Update, Delete, Read são comandos para registros
Contidos em tabelas, que podem ser tando tabelas criadas  pelo usuário ou comandos contidos
nos esquemas do próprio sql: sys, dbo...

# Crystal Reports
Não vejo muitas empresas proucupadas com quem sabe trabalhar com Crystal reports,
Na verdade não lembro disso ser um dos requisitos  sites como Catho, Programathor, outros sites de buscas de emprego.
Para se começar a trabalhar com crystal devemos:
- saber criar uma conexão com o banco de dados
- Saber criar joins entre as tabelas
- entender a estrutura do documento: header, detail, foother, groups
- conhecer campos especiais: data de impressão, número de página, entre outros.
- Fórmulas: Aqui é onde tratamos campos que precisão de algum tipo de 
Formatação, condição, interação...
- grupos
- Filtros(where)

# Angular
Depois do html, css e Javascript, é hora de saber sobre o framework front-end angular, com ele estou aprendendo a trabalhar com o typescrip.
Para criar minha aplicação, preciso saber sobre:
1. Componentes
- os componentes são a parte visual meu aplicativo, nele estará as extensões hmtl, css e Javascript
2. Módulos
- Aqui, é o local onde será possível importar componentes, serviços...
3. Diretivas
- Aqui manipulamos comportamentos do componente com instruções com : if, else, foreach...
4. Rotas.
- nesse tópico, é entendido como é criado a estrutura de rotas de uma aplicação angular
5. HTTP
- Como o angular é front-end, aplicação backend devem ser chamadas através do consumo de API's, essas chamadas são feitas através de solicitações HTTP
6. Pasta global
- aqui é colocado todos componentes e recursos que fazem parte de um contexto global, exemplo: um component NAVBAR
7. Pasta Shared
-Aqui é mais simples de entender, como o próprio nome explica, aqui fica todos componentes e serviços que são compartilhados por componentes da aplicação, exemplo: um serviço de validação de caracteres, um component loader...



# Livros Lidos

## Refatoração
Quando penso em refatoração, eu penso na palavra "TEMPO", como no meu trabalho a grande parte do codigo que presto manutenção é em uma linguagem estruturada... eu 
fico P da vida no modo  em que aquelas rotinas são contruidas, é If, Else, for, variavel global, nomes reduzidos para todos os lados, sem contar nas funções que chegam as ter mais de 1000, 2000 ou 3000. É uma loucura entender aqueles processos, o tempo perdido para enteder em quais locais preciso fazer tais customizações é muito grande.
Se lá existisse um pouco dos principios de refatorações, grande parte do tempo que era perdido para entender o codigo poderia ser usado para aprender algo mais importante ou até mesmo refatorar o que já existe, seria bom se esse sistema não tivesse regras relacionadas a codigo "standard".
O legal de ter essa visão sobre o codigo é quando começo a olhar para esse codigo e pensar em como eu poderia melhora-lo usando tecnicas desse livro. Como esse trecho é dedicado a minha visão sobre o que vou aprendendo, nada mais justo que eu citar algun pontos importantes que fizeram grande diferença no meu processo de aprendizagem:
### Maus Cheiros
No capítulo 3, Martin fowler da inico a sessão de " Maus Cheiros"
É aqui que começamos a ver com outros olhos códigos fontes, nessa capítulo ele explicada sobre: Nomes Misterios, Funções Longas, excesso de parâmetros,duplicação de código, dados globais, dados mutáveis, obsessão por primitivos,switches repitidos, laços ...
Bom, existe muitos casos que podem ser considerados maus cheiros, sair por aí querendo apontar o que é e o que não é mal cheiro não é uma boa ideia para minha performance, o importante para mim é saber que um aquele recurso existe e que quando eu precisar, buscarei no livro ou em qualquer outra documentação.
### Testes Unitarios
Os testes são apresentados no capítulo quatro, aqui fowler fala sobre a importância de um código autotestavel, durante a leitura é afirmado que quando fazemos testes unitários, reduzimos a porcentagem de chance de um determinado processo resultar em erros.
### Escolha da refatoração
Bom, a partir daqui é só exemplo prático de como implementar melhores práticas de refatoração, cada tipo de refatoração tem um nome específico e um jeito especial para resolver um problema, os mais comuns que uso no meu dia-a-dia são:
- extrair função
> Motivo: Quando um determinado trecho que código representa um nome ou algum tipo de procedimento, eu consigo extrai-lo para uma função com o nome que representa aquele código.
Durante a criação: dessa função eu posso usar outras boas práticas de refatoração, como: substituir variável por objeto, dar um nome significativo para a função, internizar variável, extrair variável


### Sistemas Operacionais
Bom, como meu objetivo é criar as melhores aplicações nos quesitos de velocidade e performace, então preciso ter muito frizado em minha cabeça pontos importantes sobre gerenciamento de tarefas e gerenciamento de memória. Sendo assim, irei descrever um pouco sobre cada um deles.

#### Gerenciamento de tarefas

#### Gerenciamento de Memoria (RAM)
- A menor unidade de uma memória RAM é de 1 byte (8 bits) 2x2x2x2x2x2x2x2 => 256 combinações binarias
- O gerenciamento de memoria é feita pela MMU (Memory managment unit) => Unidade de Gerenciamento de Memoria
- Cada endereço de memoria representa um byte
- A execução de programas diretamente na memoria principal é pouco usada
- Hoje em  dia  são usados <espaços de endereçamento> e <memoria virtual> (Swapp out >> Memoria RAM => Memoria Secundaria. Swapp in >> Memoria Secundaria => Memoria RAM)
##### Espaço de Endereçamento
Interessante entender o espaço de endereçamento de um memoria RAM, pois, é com base na quantidade de barramentos dados fixos que um processador tem que se define o tamanho maximo de memoria que um processador consegue endereçar. 
> Um processador com 32 vias de endereço que permite acessar 2*32 (4Gbbytes) de memoria 
##### A memória Virtual
Ocultando a complexidade da memoria fisica, a memoria virtual simplifica a alocação de memoria pelos processos, transendo junto a ela dois tipos de endereços de memoria, sendo eles:
 - Endereço Fisico: Aqui são os endereços  que de fato existem na memoria RAM (Verdadeiro), disponiveis somente aqueles que não estão sendo usando por processos.
 - Endereço Lógico: Usados pelos processos e sistema operacional, eles são definidos com base no espaço de endereçamento do processador.
 
 
 
### Expressões Regulares
#### o que é?
É uma definição para que eu encontre padrões em um texto
#### Quando usar?
Usamos quando precisamos buscar ou validar um padrão dentro de um texto


 
 
 
