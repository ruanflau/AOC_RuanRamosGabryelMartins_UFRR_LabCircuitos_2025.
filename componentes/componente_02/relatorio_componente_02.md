### [COMPONENTE 02]. Multiplexador de quatro opções de entrada

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Atua como um seletor de dados. Possui quatro entradas de dados e escolhe qual delas será passada para a saída, conforme o valor de duas entradas de seleção.
    * **Pinos de Entrada:**
        * `I0`, `I1`, `I2`, `I3`: Quatro pinos de 1 bit para as entradas de dados.
        * `S1`, `S0`: Dois pinos de 1 bit para seleção.
    * **Pinos de Saída:**
        * `Y`: Um pino de 1 bit que reflete o valor da entrada selecionada.
    * **Lógica:** A combinação das entradas de seleção define a saída:
        * `S1S0 = 00 → Y = I0`
        * `S1S0 = 01 → Y = I1`
        * `S1S0 = 10 → Y = I2`
        * `S1S0 = 11 → Y = I3`

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Seleção da entrada I0**
        * **Pinos de Entrada:** `S1=0`, `S0=0`, `I0=1`, `I1=I2=I3=0`.
        * **Conexões Ativas:** As entradas de seleção ativam o caminho lógico de `I0`.
        * **Resultado:** `Y = 1`.
    * **Teste 2: Seleção da entrada I3**
        * **Pinos de Entrada:** `S1=1`, `S0=1`, `I3=1`, `I0=I1=I2=0`.
        * **Conexões Ativas:** As entradas de seleção ativam o caminho lógico de `I3`.
        * **Resultado:** `Y = 1`.
