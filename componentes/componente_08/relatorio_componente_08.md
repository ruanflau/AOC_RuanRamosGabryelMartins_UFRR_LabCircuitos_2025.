### [COMPONENTE 08]. Somador de 8 bits

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Realiza soma de dois números de 8 bits.
    * **Pinos de Entrada:**
        * `A[7..0]`, `B[7..0]`: Parcelas da soma.
        * `Cin`: Carry-in.
    * **Pinos de Saída:**
        * `S[7..0]`: Resultado.
        * `Cout`: Carry-out.
    * **Lógica:** `S = A + B + Cin`.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Soma simples**
        * **Entrada:** `A=00010000` (16), `B=00100001` (33), `Cin=0`.
        * **Resultado:** `S=00110001` (49), `Cout=0`.
    * **Teste 2: Soma com carry**
        * **Entrada:** `A=00010000`, `B=00100001`, `Cin=1`.
        * **Resultado:** `S=00110010` (50), `Cout=0`.
