# O que é um array?
Os arrays são estruturas que servem para guardar dados, e organizá-los. Seu objetivo é ser um espaço fixo na memória do computador que armazena elementos. Esses elementos podem ser acessados por um tipo de indicação, que chamamos de índice. Você pode guardar seus chapéus na gaveta 1, suas calças na gaveta 2 e as meias na gaveta 3, e sempre que precisar de calças, chapéus ou meias, vai saber em que gaveta buscar.

Dentro do array existe vários métodos específicos, sendo alguns delez, o map, sort, filter, reduce e spread


# Map array

O método map chama a função callback recebida por parâmetro para cada elemento do Array original, em ordem, e constrói um novo array com base nos retornos de cada chamada. A função callback é chamada apenas para os elementos do array original que tiverem valores atribuídos; os elementos que estiverem como undefined, que tiverem sido removidos ou os que nunca tiveram valores atribuídos não serão considerados.

 ```
//Array com o método de map, que soma +1
const arraymap = [2, 4, 6, 8]
const soma = arraymap.map(num => num + 1);
console.log(soma);//Resultado=[3, 5, 7, 9]

Resultado: (4) [3, 5, 7, 9]
```
