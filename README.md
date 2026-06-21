# 🎵 Statify

Dashboard pessoal de estatísticas musicais do Spotify, inspirado no Last.fm. Mostra suas músicas, artistas e álbuns favoritos, hábitos de escuta, histórico, conquistas e muito mais — tudo direto da sua conta Spotify.

🔗 **Site:** https://dainty-zuccutto-23ef99.netlify.app

## ✨ Funcionalidades

- **Visão Geral** — perfil, "tocando agora" em tempo real, top músicas e recomendações
- **Semana** — relatório semanal com top músicas/artistas/álbuns dos últimos 7 dias, artistas similares
- **Relatório** — coeficiente musical, impressão digital (radar você vs média global), tags ao longo do tempo, música por década, relógio de escuta radial
- **Músicas / Artistas / Álbuns** — rankings com filtro por período (30 dias / 6 meses / sempre)
- **Hábitos** — gêneros, popularidade, décadas, personalidade musical (radar), mainstream vs underground
- **Histórico** — calendário de atividade, streak, relógio de escuta, tempo por artista
- **Biblioteca** — busca em todos os artistas, álbuns e gêneros do seu perfil
- **Comparar** — gere um código compacto e compare compatibilidade musical com amigos
- **Conquistas** — badges desbloqueáveis baseados nos seus hábitos de escuta

## 🛠️ Tecnologias

- HTML, CSS e JavaScript puro (sem frameworks)
- [Chart.js](https://www.chartjs.org/) para gráficos
- Spotify Web API com autenticação PKCE (OAuth 2.0, sem backend)
- Hospedado na [Netlify](https://www.netlify.com/)

## 🚀 Rodando localmente

1. Clone o repositório
2. Sirva os arquivos com qualquer servidor estático, por exemplo:
   ```bash
   npx serve .
   ```
3. Configure seu próprio app no [Spotify for Developers](https://developer.spotify.com/dashboard) e atualize `CLIENT_ID` e `REDIRECT_URI` no `index.html`
4. Adicione a Redirect URI correspondente no painel do Spotify

## 📄 Licença e Avisos

Este projeto não é afiliado, patrocinado ou endossado pelo Spotify. Spotify é uma marca registrada da Spotify AB.

Veja os [Termos de Uso](terms.html) para mais detalhes.
