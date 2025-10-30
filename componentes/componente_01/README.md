## [COMPONENTE 01] Registrador Flip-Flop do tipo D e do tipo JK

### Relatório

#### (i) Descrição
- **Funcionalidade:** Flip-Flops armazenam um único bit de informação e são elementos básicos de memória sequencial.  
- **Pinos (Ambos):** `CLK`, `Q`, `Q'`.  
- **Pinos (Tipo D):** `D` (Data).  
- **Pinos (Tipo JK):** `J`, `K`.  
- **Lógica (Tipo D):** Na borda ativa do clock, `D` é transferido para `Q`.  
- **Lógica (Tipo JK):**  
  - `J=0`, `K=0`: mantém estado  
  - `J=1`, `K=0`: `Q=1`  
  - `J=0`, `K=1`: `Q=0`  
  - `J=1`, `K=1`: `Q` inverte estado  

#### (iii) e (iv) Testes do Componente
- **Teste (Tipo D):** `D=1`, pulso em `CLK` → `Q=1`  
- **Teste (Tipo JK):** `J=1`, `K=1`, `Q` inicial `0`, pulso em `CLK` → `Q=1`
