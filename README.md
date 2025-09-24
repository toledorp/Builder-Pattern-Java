# Builder-Pattern-Java

Esta pasta contem um exercicio em Java sobre Builder PAttern

Sinopse do exercicio:
Implemente uma classe Carro utilizando o padrão Builder. 
O carro deve ter atributos como modelo, ano, cor e motor. 
Crie objetos de Carro usando o Builder e exiba suas informações.

Teste de Mesa:
Carro carro = new Carro.Builder()
    .setModelo("Civic")
    .setAno(2022)
    .setCor("Prata")
    .setMotor("2.0")
    .build();
carro.exibirInfo();
// Saída esperada:
// Modelo: Civic
// Ano: 2022
// Cor: Prata
// Motor: 2.0
