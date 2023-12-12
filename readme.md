# Estacionamento - avanade

#### Contrato para construir um sistema para estacionamento, usado para gerenciar veículos estacionados:

## Features
- Adicionar veículos
- Listar veículos
- Remover veículos
- Cobrança de estacionamento (valor)

## Variáveis
- precoInicial - É o preço cobrado para deixar seu veículo estacionado.
- precoPorHora - É o preço por hora que o veículo permanecer estacionado.
- veiculos - (List) representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

## Métodos
- AdicionarVeiculo - Recebe uma placa digitada pelo cliente e guardar na variável veiculos.
- RemoverVeiculo - Verifica se um determinado veículo está estacionado, caso verdadeiro, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: 
```
precoInicial * precoPorHora
```
- ListarVeiculos: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem:
 ```
 Não há veículos estacionados.
 ```

 Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:
 ```
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar
 ```

## Importante

O código não está funcional, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada TODO no código, em seguida, implemente conforme as regras acima.