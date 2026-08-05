# ⏰ PontoLimite — Lembrete e Trava de Segurança de Ponto

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0+-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

O **PontoLimite** é uma aplicação web (_PWA_) desenvolvida para resolver uma dor real no ambiente corporativo: a aplicação de advertências disciplinares devido a extrapolações mínimas de horários de saída que ultrapassam o limite legal de horas extras (a famosa "10ª hora").

Com um design focado em **UX de zero fricção**, a ferramenta permite registrar o ponto de entrada com apenas 1 clique e calcula instantaneamente a hora exata de término da jornada e o limite máximo permitido pela legislação trabalhista (CLT).

📱 **Acesse o App em Produção:** [https://allanrein.github.io/PontoLimite/](https://allanrein.github.io/PontoLimite/)

---

## 🎯 O Problema

Em diversas empresas sob regime CLT, a tolerância para a realização da 2ª hora extra é rígida. Atrasos de apenas **1 minuto** além do limite permitido podem gerar advertências formais devido a passivos trabalhistas. No dia a dia corrido, é fácil perder a noção do tempo ou se confundir com cálculos de intervalo intrajornada.

## 💡 A Solução

O **PontoLimite** foi criado para funcionar como um assistente de ponto pessoal:

- **Zero digitação na maioria dos casos:** Botão de captura do horário de entrada atual com 1 toque.
- **Suporte a Múltiplos Turnos:** Cálculo dinâmico para jornadas ADM (8h48) ou Turnos de 7h20min.
- **Linha Vermelha de Segurança:** Exibição clara e destacada do horário limite inegociável (+2 horas extras).
- **Notificações do Sistema:** Agendamento de alertas antes do término do tempo limite.
- **Instalável (PWA):** Adicione à tela inicial do smartphone sem necessidade de download via loja de apps.

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)** — Semântica e estrutura do app.
- **[Tailwind CSS](https://tailwindcss.com/)** — Estilização responsiva e UI moderna via utility-first classes.
- **[JavaScript (Vanilla)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** — Lógica de cálculo de horários e manipulação do DOM.
- **[Lucide Icons](https://lucide.dev/)** — Conjunto de ícones vetoriais leves para interface visual.

---

## 🚀 Como Rodar o Projeto Localmente

Como a aplicação é 100% _Client-Side_ (rodada no próprio navegador), não é necessário configurar servidores ou bancos de dados.

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/allanrein/PontoLimite.git](https://github.com/allanrein/PontoLimite.git)
   ```
