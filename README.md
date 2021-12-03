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
 - [x] Laços de Repetição
 - [x] Funções
 - [x] Eventos
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

# Livros Lidos
## O gerente Minuto

## Guia Pratico do SCRUM

## Gerencimanento de Redes Com windowns XP

## Refatoração

## Montagem de Micros

## Arquitetura Limpa
