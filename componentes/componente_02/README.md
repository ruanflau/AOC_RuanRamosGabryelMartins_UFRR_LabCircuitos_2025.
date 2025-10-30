## [COMPONENTE 02] Multiplexador de Quatro Opções de Entrada

### Relatório

#### (i) Descrição
- **Funcionalidade:** Seleciona uma de quatro entradas (`C0–C3`) para a saída `Y`, com base nas entradas de seleção `S1`, `S0`.  
- **Entradas:** `C0`, `C1`, `C2`, `C3`, `S1`, `S0`  
- **Saída:** `Y`  
- **Lógica:**  
  - `S1S0 = 00` → `C0`  
  - `S1S0 = 01` → `C1`  
  - `S1S0 = 10` → `C2`  
  - `S1S0 = 11` → `C3`

#### (iii) e (iv) Testes do Componente
- **Teste 1:** `S1=0`, `S0=0`, `C0=1` → `Y=1`  
- **Teste 2:** `S1=1`, `S0=1`, `C3=1` → `Y=1`
