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
🎯 Link para o exercício da aula 03: [Exercício 03 - Clique aqui](https://github.com/lauraromerosantos/Exercicio03_Algoritmos_Programacao_II) 
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
🎯 Link para o exercício da aula 05: [Exercício 05 - Clique aqui](https://github.com/lauraromerosantos/Exercicio05_Algoritmos_Programacao_II) 

## Aula 06 - Tuplas e Dicionários

	• Uma tupla é uma coleção que é ordenada e imutável.
	• Tuplas em Python são escritas com parênteses. A partir do Python 3, não precisa de parênteses.
	• Um dicionário é uma coleção que é desordenada, mutável e indexada.
	• Em Python, dicionários são escritos com chaves, e sua estrutura é composta por:
	{ “key” : “value” }
🎯 Link para o exercício da aula 06: [Exercício 06 - Clique aqui](https://github.com/lauraromerosantos/Exercicio06_Algoritmos_Programacao_II) 

## Aula 07 - Orientação a Objetos

_CLASSE_

	• Representam um conjunto de objetos que compartilham características e comportamentos comuns.
	• As classes definem como os objetos devem se parecer e se comportar, ou seja, define as características e funcionalidades
	• Uma classe possui atributos (características) e métodos (funções/ações)

_OBJETO_

	• Um objeto é uma entidade que exibe algum comportamento bem definido.
	• OBJETO = DADOS + OPERAÇÕES
	• Características: dados representam características
		- São chamados atributos
		- São as variáveis do objeto.
	• Comportamento: operações definem comportamento
		- São os métodos de um objeto
		- São as funções que são executadas por um objeto
		
### Propriedades
	• Estado
		- Representado pelos valores dos atributos de um objeto
	• Comportamento
		- Definido pelo conjunto de métodos do objeto
		- Estado representa o resultado cumulativo de seu comportamento
	• Identidade
		- Um objeto é único, mesmo que o seu estado seja idêntico ao de outro
	• Os valores dos DADOS são modificados a partir das OPERAÇÕES sobre estes dados 
	
_ATRIBUTO_

	• Características dos objetos de uma classe, também são conhecidos como variáveis ou campos
	• Essas propriedades definem o estado de um objeto, fazendo com que esses valores possam sofrer alterações

_MÉTODO_

	• São ações ou procedimentos, onde podem interagir e se comunicarem com outros objetos. 
	A execução dessas ações se dá através de mensagens, tendo como função o envio de uma solicitação ao objeto para que seja efetuada a rotina desejada.
	
### RESUMINDO

	• Objeto
		- Qualquer entidade que possui características e comportamento
	• Classe
		- Descreve um tipo de objeto
		- Define atributos e métodos
	• Atributo
		- Define características do objeto
	• Método
		- Operações que o objeto pode realizar 
		
🎯 Link para o exercício da aula 07: [Exercício 07 - Clique aqui](https://github.com/lauraromerosantos/Exercicio07_Algoritmos_Programacao_II)

## Aula 08 - Herança
	• Herança nos permite definir uma classe que herda todos os atributos e métodos de outra classe.
	• Classe pai (Super Class) é a classe que está sendo herdada também chamada de classe base ou classe genérica.
	• Classe filha (Sub Class) é a classe que herda de outra classe, também chamada de classe derivada ou classe especializada.
	• A herança é um princípio da POO que permite a criação de novas classes a partir de outras previamente criadas.
	• Essas novas classes são chamadas de subclasses, ou classes derivadas; e as classes já existentes, que deram origem às subclasses, são chamadas de superclasses, ou classes base.
	• Uma subclasse herda métodos e atributos de sua superclasse; apesar disso, pode escrevê-los novamente para uma forma mais específica de representar o comportamento do método herdado.
	
🎯 Link para o exercício da aula 08: [Exercício 08 - Clique aqui](https://github.com/lauraromerosantos/Exercicio08_Algoritmos_Programacao_II)

## Aula 09 - Encapsulamento
	• O encapsulamento é uma forma de restringir o acesso ao comportamento interno de um objeto. 
		○ Um objeto que precise da colaboração de outro para realizar alguma tarefa simplesmente envia uma mensagem a este último.
		○ O método (maneira de fazer) que o objeto requisitado usa para realizar a tarefa não é conhecido dos objetos requisitantes.
	• Na terminologia da orientação a objetos, diz-se que um objeto possui uma interface.
		○ A interface de um objeto é o que ele conhece e o que ele sabe fazer, sem descrever como o objeto conhece ou faz.
		○ A interface de um objeto define os serviços que ele pode realizar e consequentemente as mensagens que ele recebe.
	• Encapsular é fundamental para que seu sistema seja suscetível a mudanças: não precisaremos mudar uma regra de negócio em vários lugares, mas sim em apenas um único lugar, já que essa regra está encapsulada.
	
_Modificadores de Acesso_

	▷ Público (Public)
		○ Qualquer classe tem acesso ao atributo ou método
	▷ Protegido (Protected)
		○ Apenas classes filhas (subclasses) tem acesso ao atributo ou método
	▷ Privado (Private)
		○ O atributo ou método só pode ser acessado dentro da própria classe
_GETTERS_

	▷ Nomeamos um método acessor com GET toda vez que este método for verificar algum campo ou atributo de uma classe.
	▷ Como este método irá verificar um valor, ele sempre terá um retorno. Mas não terá nenhum argumento.

_SETTERS_

	▷ Nomeamos um método acessor com set toda vez que este método for modificar algum campo ou atributo de uma classe, ou seja, se não criarmos um método acessor set para algum atributo, isso quer dizer que este atributo não deve ser modificado.

🎯 Link para o exercício da aula 09: [Exercício 09 - Clique aqui](https://github.com/lauraromerosantos/Exercicio09_Algoritmos_Programacao_II)
