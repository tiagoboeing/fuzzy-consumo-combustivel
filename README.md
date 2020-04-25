# Fuzzy aplicada ao consumo de combustível

> [Demonstração](https://colab.research.google.com/drive/1VwlnyPma-wm0pDFUwLpdVJp2jeaozaG1)

Lógica de Fuzzy aplicada para cálculo de consumo de combustível dado algumas variáveis

![](https://i.imgur.com/VVOr2sS.png)

As variáveis que impactam no consumo de combustível do veículo são:

- A velocidade que o mesmo se encontra;
- A temperatura do ar condicionado.

### Regras

- SE **velocidade_baixa** e **temperatura_baixa** → CONSUMO BAIXO
- SE **velocidade_baixa** e **temperatura_alta** → CONSUMO MEDIO
- SE **velocidade_media** e **temperatura_baixa** → CONSUMO BAIXO
- SE **velocidade_media** e **temperatura_alta** → CONSUMO ALTO
- SE **velocidade_alta** e **temperatura_baixa** → CONSUMO MEDIO
