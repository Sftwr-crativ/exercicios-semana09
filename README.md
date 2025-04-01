# exercicios-semana09

1.
a) nome, especie, idade

b) AnimalSelvagem além de importer os atributos de Animal, também adiciona o atributo "habitat", além de criar um novo método chamado exibirHabitat()

2.
c) Essa linha significa que a classe AnimalSelvagem conseguirá herdar o conteúdo de outra classe, além de adicionar outras funções à classe

d) Quando utilizamos super(), os elementos que citamos dentro dos parentheses serão herdados da classe inicial

3.
e) Quando esse commando é executado, um novo objeto da classe AnimalSelvagem é criado com os parametros indicados dentro do parentheses

f) O animal1 cria um novo objeto dentro da classe "Animal", na qual tem apenas tres entradas de parametros. Já o animal2 cria um objeto da classe AnimalSelvagem no qual contem quatro entradas de parametros, sendo tres delas herdadas pela classe "Animal"
m,

4.
g) Esse metodo pode ser utilizado nas duas classes pois ele é criado na primeira classe e herdado na segunda, portanto pode ser aplicado nas duas.

h) Esse método não está disponível em animal1, uma vez que animal1 é um objeto da classe "Animal". Essa classe não contém esse método, uma vez que de acordo com a logica de programação, ele só será criado e aplicado na classe AnimalSelvagem que HERDA a classe Animal. Em resumo, a classe Animal antecede a criação do método exibirHabitat()

5.
i) A herança contribui para evitar a repetição de Código, uma vez que ao herdar elementos da classe "Animal", os mesmos não precisam ser reescritos na classe que está herdando tais elementos.

j) Ele deveria ser implementado na classe Animal(), uma vez que ele precisa ser aplicado para TODOS os animas, e não apenas os animais selvagens

6.
k) Nome: Tico, Espécie: Macaco, Idade: 4
Nome: Nala, Espécie: Leoa, Idade: 5
Habitat natural: Savana Africana

l) Se essa linha fosse removida, a classe AnimalSelvagem não conseguiria herdar os atributos escritos na classe Animal, portanto não conseguiria executar codigos como o indicado na constante animal2

7.
m)
n)
```
class AnimalDomestico extends Animal{
	constructor(nome, especie, idade, nomeDono) {
	super(nome, especie, idade)
	this.nomeDono = nomeDono;
	}

	exibirDono() {
	return `Dono de ${this.nome}: ${this.nomeDono}.`;
	}
}
```
