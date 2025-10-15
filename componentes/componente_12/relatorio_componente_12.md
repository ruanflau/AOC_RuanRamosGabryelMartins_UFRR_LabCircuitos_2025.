### [COMPONENTE 12]. Máquina de estados utilizando portas lógicas

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Implementa um circuito sequencial que percorre estados predefinidos. Exemplo: contador de 2 bits (`00 → 01 → 10 → 11 → 00`).
    * **Pinos de Entrada:** `CLK`, `RESET`.
    * **Pinos de Saída:** `Q1`, `Q0`.
    * **Lógica:** Dois Flip-Flops armazenam o estado atual; a lógica combinacional define o próximo estado (`D0 = ¬Q0`, `D1 = Q1 XOR Q0`).

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Ciclo de contagem**
        * **Entrada:** `RESET=0`.
        * **Resultado:** Saídas ciclam por `00 → 01 → 10 → 11 → 00`.
    * **Teste 2: Reset**
        * **Entrada:** Durante qualquer estado, `RESET=1`.
        * **Resultado:** Saídas retornam a `00`.

