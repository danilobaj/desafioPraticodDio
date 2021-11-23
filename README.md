# Desafio Pratico Dio
Desafio Pratico da DIO

#### Nesse repositório vou subir 2 códigos escritos em Java, feito por mim no desafio prático da Trybe.

### Multiplicando os elementos dentro do Array por 3
``````
function tripleTheChances(chances) {
    for (let i = 0; i < chances.length; i += 1) {
        chances[i] = chances[i] * 3
    }
    return chances;
}
``````
### Contar quantas vezes uma letra se repete numa frase
``````
function vezesLetraAparece(frase, letra) {
    let contador = 0;
    for (let i = 0; i < frase.length; i += 1) {
        if (letra === frase[i]) {
            contador += 1;
        }
    }
    return contador;
}
``````
