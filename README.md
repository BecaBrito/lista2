//exercício 1
const Cores = ['Azul','Verde-água']
const Nomes = ['Beatriz', 'Emily','Maria','Giovanna']

const CoresNomes = Cores.concat(Nomes)
console.log(CoresNomes)



//execício 2
const numeros =[1,2,3,4,5,6,7,8,9,10]
const parteNumeros = numeros.slice(2,7, numeros.length) 
console.log(parteNumeros)

//Exercício 3
const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']
frutas.splice(2,3, 'Kiwi','Pêssego')
console.log(frutas)



//Exercício 4
const MenuPrincipal = ['Frango Grelhado com Batatas Fritas','Escondidinho de Carne Moída',
    'Strogonoff', 'Lasanha', 'Bife à Milanesa', 'Peixe Frito com Arroz e Salada',
    'Feijão Tropeiro com Arroz','Panqueca de Carne ou Frango','Frango Assado com Batatas']

const MenuDeSobremesas = ['Sorvete', 'Brownie com sorvete', 'Pudim de Leite Condensado', 
    'Mousse de Chocolate', 'Torta de Limão']


const MenuCompleto =MenuPrincipal.concat(MenuDeSobremesas)
console.log(MenuCompleto)
