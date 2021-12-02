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
> ![Exemplo de Arvore Binaria](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRFmlprp5ozA302T9Vndm0olGuLKu1MefaPe5_t7PmmiHrZEdCkkMojBOzoMmS_9fvWDys&usqp=CAU)

