### [COMPONENTE 10]. Unidade Lógica Aritmetrica (ULA) de 8 bits

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Unidade Lógica e Aritmética com operações selecionadas por opcode.
    * **Pinos de Entrada:**
        * `A[7..0]`, `B[7..0]`: Operandos.
        * `OP[3..0]`: Código da operação.
    * **Pino de Saída:** `Y[7..0]`: Resultado.
    * **Lógica:** Um multiplexador de 8 bits seleciona a saída do subcircuito correspondente à operação definida em `OP`.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Operação OR**
        * **Entrada:** `A=11001100`, `B=10101010`, `OP=0001`.
        * **Resultado:** `Y=11101110`.
    * **Teste 2: Operação Subtração**
        * **Entrada:** `A=00001111` (15), `B=00001001` (9), `OP=0111`.
        * **Resultado:** `Y=00000110` (6).
