### [COMPONENTE 04]. Somador de 8 bits que recebe um valor inteiro e soma com o valor 4

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Circuito aritmético que adiciona o valor constante 4 a uma entrada de 8 bits.
    * **Pinos de Entrada:** `A[7..0]`: Barramento de 8 bits para o valor de entrada.
    * **Pinos de Saída:**
        * `S[7..0]`: Resultado da soma.
        * `Cout`: Pino de 1 bit (Carry-out), indica overflow.
    * **Lógica:** O circuito realiza `S = A + 4`, utilizando um somador completo com a segunda entrada fixa em `00000100`.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Soma sem overflow**
        * **Entrada:** `A = 00010000` (16).
        * **Resultado esperado:** `S = 00010100` (20), `Cout = 0`.
    * **Teste 2: Soma com overflow**
        * **Entrada:** `A = 11111100` (252).
        * **Resultado esperado:** `S = 00000000`, `Cout = 1`.
