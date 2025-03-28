# Retificador de Onda Completa com Regulador 7805 e LED Indicador

Este projeto apresenta um circuito de retificador de onda completa com regulador de tensão 7805 e LED indicador. O circuito é projetado para converter uma fonte de corrente alternada (AC) em corrente contínua (DC) estabilizada em 5V.

---

## Esquemático do Circuito

**(Inserir aqui a imagem do esquemático do Proteus)**

### Componentes Utilizados
- **J1** - Conector de entrada para fonte AC
- **BR1** - Ponte retificadora (Bridge Rectifier)
- **C1** - Capacitor de filtragem (1µF)
- **C2 e C3** - Capacitores de desacoplamento (22pF cada)
- **U1** - Regulador de tensão 7805 (5V fixo)
- **J2** - Conector CONN-SIL2 para saída estabilizada
- **R1** - Resistor de 130Ω para limitar a corrente do LED
- **D1** - LED indicador de saída estabilizada

---

## Descrição do Funcionamento

1. **Entrada AC**:
   - O conector J1 é a entrada para a fonte de corrente alternada. Essa tensão será retificada e estabilizada para 5V DC.

2. **Ponte Retificadora**:
   - O componente BR1 é uma ponte retificadora que converte a tensão AC em uma tensão DC pulsante.

3. **Filtragem Inicial**:
   - O capacitor C1 (1µF) atua como filtro, reduzindo as oscilações na tensão retificada.

4. **Regulador 7805**:
   - O CI U1 regula a tensão de saída para 5V DC fixo, adequado para alimentar dispositivos eletrônicos sensíveis.

5. **Capacitores de Desacoplamento**:
   - C2 e C3 (22pF) são capacitores de desacoplamento que ajudam a estabilizar a tensão na entrada e na saída do regulador.

6. **LED Indicador**:
   - O LED D1, acompanhado do resistor R1 (130Ω), indica que a saída de 5V está ativa e estabilizada.

7. **Conector CONN-SIL2**:
   - O J2 é um conector de saída para ligações externas, permitindo conexão fácil com outros circuitos.

---

## Layout da PCB

**(Inserir aqui a imagem do layout da PCB no Proteus)**

### Dicas para Montagem
- Certifique-se de respeitar a polaridade dos capacitores eletrolíticos e do LED.
- Utilize uma ponte retificadora adequada para a corrente prevista no projeto.
- O regulador 7805 pode exigir um dissipador de calor dependendo da potência dissipada.

---

## Visualização 3D

**(Inserir aqui a imagem da visualização 3D no Proteus)**

---

## Testes e Validação
- A entrada AC deve estar dentro da faixa suportada pelo retificador e pelo regulador 7805.
- A tensão na saída deve estar estabilizada em aproximadamente **5V DC**.
- O LED deve acender confirmando a presença da tensão estabilizada na saída.

---

## Aplicações
Este circuito é ideal para alimentar microcontroladores, sensores e outros dispositivos eletrônicos que exigem uma tensão estabilizada de 5V DC.

---

## Licença
Este projeto é livre para uso educacional e pessoal. Sinta-se à vontade para modificá-lo e melhorá-lo conforme suas necessidades.

