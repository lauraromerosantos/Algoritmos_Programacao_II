# Algoritmos e Programação II
Repositório destinado aos exemplos realizados durante as aulas de Algoritmos e Programação II - 2020/2
## Aula 01 - Revisão Python
	Revisão de métodos
## Aula 02 - Lista Encadeada 
	• Estrutura que armazena um conjunto de elementos, em uma determinada sequência.
	• Permite alocação dinâmica de memória.
	• É constituída por elementos que possuem uma estrutura composta de valor e endereço do próximo elemento.
	• Se estivermos no último elemento da lista, o campo para o endereço terá como valor: NULL
## Aula 03 - Lista Duplamente Encadeada
	• Estrutura que armazena um conjunto de elementos, em uma determinada sequência.
	• Permite alocação dinâmica de memória.
	• É constituída por elementos que possuem uma estrutura composta de valor e endereço do elemento anterior e do próximo elemento.
	• Se estivermos no primeiro elemento da lista, o campo para o endereço do elemento anterior terá como valor: NULL
	• Se estivermos no último elemento da lista, o campo para o endereço do próximo elemento terá como valor: NULL
Link para o exercício da aula 03: [Exercício 03 - Clique aqui](https://github.com/lauraromerosantos/Exercicio03_Algoritmos_Programacao_II) 
## Aula 04 - Fila

_FIFO: First In, First Out_

	• Estrutura de dados linear
	• Inserções de elementos são realizadas no final da fila
	• Exclusões de elementos são realizadas no início da fila
	• Semelhante à uma fila de banco, o primeiro elemento a entrar na fila, será o primeiro também a sair da fila
	• É necessário saber quais são os elementos que estão no início e no fim da fila
        
## Aula 05 - Pilha

_LIFO: Last In, First Out_

    • Estrutura de dados linear
    • Inserções de elementos são realizadas no top da pilha
    • Exclusões de elementos são realizadas no top da pila
    • Semelhante à uma pilha de objetos, o último elemento a entrar na pilha, será o primeiro também a sair da pilha.
    • É necessário saber qual elemento está no topo da pilha
Link para o exercício da aula 05: [Exercício 05 - Clique aqui](https://github.com/lauraromerosantos/Exercicio05_Algoritmos_Programacao_II) 

## Aula 06 - Tuplas e Dicionários

	• Uma tupla é uma coleção que é ordenada e imutável.
	• Tuplas em Python são escritas com parênteses. A partir do Python 3, não precisa de parênteses.
	• Um dicionário é uma coleção que é desordenada, mutável e indexada.
	• Em Python, dicionários são escritos com chaves, e sua estrutura é composta por:
	{ “key” : “value” }
Link para o exercício da aula 06: [Exercício 06 - Clique aqui](https://github.com/lauraromerosantos/Exercicio06_Algoritmos_Programacao_II) 

## Aula 07 - Orientação a Objetos

_CLASSE_

	• Representam um conjunto de objetos que compartilham características e comportamentos comuns.
	• As classes definem como os objetos devem se parecer e se comportar, ou seja, define as características e funcionalidades
	• Uma classe possui atributos (características) e métodos (funções/ações)

_OBJETO_

	• Um objeto é uma entidade que exibe algum comportamento bem definido.
	• OBJETO = DADOS + OPERAÇÕES
	• Características: dados representam características
		• São chamados atributos
		• São as variáveis do objeto.
	• Comportamento: operações definem comportamento
		• São os métodos de um objeto
		• São as funções que são executadas por um objeto
		
### Propriedades
	• Estado
		• Representado pelos valores dos atributos de um objeto
	• Comportamento
		• Definido pelo conjunto de métodos do objeto
		• Estado representa o resultado cumulativo de seu comportamento
	• Identidade
		• Um objeto é único, mesmo que o seu estado seja idêntico ao de outro
	• Os valores dos DADOS são modificados a partir das OPERAÇÕES sobre estes dados 
	
_ATRIBUTO_

	• Características dos objetos de uma classe, também são conhecidos como variáveis ou campos
	• Essas propriedades definem o estado de um objeto, fazendo com que esses valores possam sofrer alterações

_MÉTODO_

	• São ações ou procedimentos, onde podem interagir e se comunicarem com outros objetos. 
	A execução dessas ações se dá através de mensagens, tendo como função o envio de uma solicitação ao objeto para que seja efetuada a rotina desejada.
	
### RESUMINDO

	• Objeto
		• Qualquer entidade que possui características e comportamento
	• Classe
		• Descreve um tipo de objeto
		• Define atributos e métodos
	• Atributo
		• Define características do objeto
	• Método
		• Operações que o objeto pode realizar 
