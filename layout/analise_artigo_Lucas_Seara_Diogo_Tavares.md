## IFSC - EngEletrônica - ELP22109
# Análise comparativa entre um carregador genuíno e genérico.

### Lucas Seara Manoel e Diogo Tavares
---

**Análise do artigo:** [IPad charger teardown: inside Apple's charger and a risky phony](http://www.righto.com/2014/05/a-look-inside-ipad-chargers-pricey.html)

**Sumário dos itens considerados:**
1. Custo
2. Volume
3. Segurança
4. Assistência Técnica
5. Confiabilidade
6. Robustez
7. Eficiência
8. Atendimento às normas
Conclusão

## 1. Custo
O carregador genérico apresenta no seu projeto um circuito mais simples em vista a tonar o produto mais barato. Porém a redução do custo pode deminuir a segurança e a qualidade do produto.

## 2. Volume
Apensar de ambas as fonte ocuparem praticamente o mesmo volume, a fonte genérica apresenta uma densidade menor pois seu projeto de baixo custo utiliza menos componentes que o projeto da fonte original.

## 3. Segurança
A fonte original possui maior isolação. Apresenta fitas isolantes separando os componentes operando em alta tensão do restante do circuito.
No quesito de segurança a fonte original também conta com:
* Encaixo com aterramento da linha com a fonte. (Ground)
* *Sparl Gap*.(Spark Gap)
* *Latch* para desligar a fonte em caso de erros. (Latch releaser circuit)
* Monitoramento de tensão de entrada e corrente no indutor.(Line voltage resistor)(Current sense resistor)
* Sensor de Temperatura.(Protection)

![](https://raw.githubusercontent.com/lsmanoel/PowerEletronics/master/layout/images/ipad_board_labeled_protection.png)

## 4. Assistência Técnica
Devido ao fato de ser uma fonte falsificada, não há para quem recorrer em caso de problema, como seria o caso de uma fonte original. 
Assistências técnicas genéricas até podem resolver determinados problemas, mas não são facilmente encontradas hoje em dia. Sem mencionar o quesito garantia.

## 5. Confiabilidade
É muito provável não haver um rigoroso procedimento de testes, e a fonte falsificada pode não apresentar um bom desempenho, em termos de eficiência, durabilidade e segurança.

## 6. Robustez
Pode-se dizer que o projeto é severamente simplificado, utilizando muitos componentes a menos, e os componentes utilizados são ainda de qualidade inferior para baixar o preço de produção. A qualidade do leiaute da placa também é duvidosa. Isso tudo levanta uma questão: esse dispositivo suportaria adequadamente um bom funcionamento?

## 7. Eficiência
Dentre os dois dispositivos, o falsificado apresenta uma potência bem inferior (5,6 W) ao que ele alega (10 W). Além da qualidade da tensão de saída ser extremamente ruidosa e cheia de picos, o que representa uma má qualidade energética.

## 8. Atendimento às normas
Posivelmente, o grande motivo pelo qual a fonte falsificada é inferior seja pelo fato de não haver preocupação com as normas de qualidade e segurança. Por este motivo, podem haver tanto riscos Á segurança, quanto uma má qualidade energética fornecida para o dispositivo a ser carregado, quanto também a poluição da rede elétrica com ruídos.

## Conclusão
Portanto, devido a todas as características que apontam evidentemente que a fonte falsificada tem qualidade inferior em todos os aspectos, pode-se imaginar o porque estas saem tão mais baratas. No entanto, vários riscos estão envolvidos ao se adquirir uma, mas tendo-se em vista que os consumidores em geral jamais pensariam nestes dados técnicos, estes dispositivos genéricos são comercializados em larga escala, uma vez que o consumidor apenas olha o preço. O barato pode seir caro!
