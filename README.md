# 📅 Calendário Guarda Personalizado (PDF / Impressão)

🔗 **Acesse a aplicação:** [https://caiorn.github.io/calendariodaguarda](https://caiorn.github.io/calendariodaguarda)

---

## 🚀 Recursos[span_2](start_span)[span_2](end_span)

- **Interface Mobile-First:** Desenvolvido prioritariamente para navegação rápida e simples em celulares e tablets.
- **Seleção Dinâmica de Período:** Escolha a data de início e fim. Pré-seleciona automaticamente o semestre atual de acordo com a data de hoje (Jan-Jun / Jul-Dez).
- **Escala de Escala / Guarda (Múltiplos de 5 dias):**
  - Ao clicar em um dia, a escala é gerada automaticamente alternando entre **Vermelho** e **Azul** a cada 5 dias.
  - Funciona tanto para o **futuro** quanto para o **passado**.
  - Dias passados possuem cor suave/opacidade reduzida para facilitar a diferenciação visual das datas futuras.
- **Contadores de Período:** Exibe o total de dias do intervalo selecionado e o total de marcações ativas.
- **Pronto para Impressão / PDF (Papel A4):**
  - Botão de impressão otimizado via CSS (`@media print`).
  - Oculta controles e botões ao imprimir.
  - Ajusta perfeitamente os 6 meses do semestre em uma **única folha A4** (Grid 2x3).

---

## 🛠️ Tecnologias Utilizadas[span_3](start_span)[span_3](end_span)

- **HTML5:** Estrutura semântica[span_4](start_span)[span_4](end_span).
- **CSS3:** Estilização responsiva, CSS Grid, variáveis CSS e suporte avançado para impressão `@media print`[span_5](start_span)[span_5](end_span).
- **JavaScript (Vanilla / ES6+):** Lógica pura de cálculo de datas, alternância de cores e renderização sem dependências externas[span_6](start_span)[span_6](end_span).

---

## 💻 Como Executar Localmente[span_7](start_span)[span_7](end_span)

1. Clone este repositório ou baixe os arquivos[span_8](start_span)[span_8](end_span):
   ```bash
   git clone [https://github.com/caiorn/calendariodaguarda.git](https://github.com/caiorn/calendariodaguarda.git)
