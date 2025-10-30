## [COMPONENTE 16] Decodificador de 7 Segmentos

### Relatório

#### (i) Descrição
- **Entrada:** `D[3..0]`  
- **Saídas:** `a–g`  
- **Lógica:** Cada segmento é ativado por uma função booleana.

#### (iii) e (iv) Testes
- **‘8’:** `D=1000` → `a–g=1`  
- **‘C’:** `D=1100` → `a,d,e,f=1`; `b,c,g=0`
