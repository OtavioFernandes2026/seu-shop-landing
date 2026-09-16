# Seu Shop — Painel de Ofertas ao Vivo

Landing page do grupo **Seu Shop Promoções e Ofertas**, feita para divulgar o grupo do WhatsApp e converter visitantes em membros através de um painel com estilo "ao vivo" (métricas, atividade recente e chamada para ação).

🔗 **Site:** [seushop.site](https://seushop.site)
📲 **Grupo no WhatsApp:** [Entrar no grupo](https://chat.whatsapp.com/E7jFappltzh12cbuNytEr0)

## ✨ Sobre o projeto

Página única em HTML/CSS/JS puro, sem dependências de build, pensada para ser leve e rápida de carregar em qualquer hospedagem estática (GitHub Pages, Vercel, Netlify, etc).

Destaques visuais:
- Indicador "ao vivo" com animação de pulso
- Painel de métricas (novos membros/dia, ofertas postadas/dia, desconto médio)
- Log de atividade recente simulando movimentação em tempo real
- Botão de call-to-action direto para o grupo do WhatsApp
- Logo do Seu Shop no topo, responsivo para mobile e desktop
- Tema adaptável a modo claro/escuro do navegador

## 📁 Estrutura

```
.
├── index.html   # página única com HTML, CSS e JS embutidos
└── README.md
```

## 🚀 Como publicar

### GitHub Pages
1. Suba o `index.html` para a raiz do repositório (ou para a branch `gh-pages`).
2. Vá em **Settings → Pages** e selecione a branch/pasta onde está o arquivo.
3. Aguarde alguns minutos até o GitHub gerar o link público.

### Vercel
1. Importe este repositório no [Vercel](https://vercel.com).
2. Como é um projeto estático (sem build), pode publicar direto — não é necessário configurar comandos de build.
3. Aponte o domínio `seushop.site` nas configurações de domínio do projeto.

## 🛠️ Como editar

O arquivo `index.html` é autocontido: todo o CSS está na tag `<style>` e o JS de simulação das métricas está na tag `<script>` no final do arquivo. Basta abrir e editar diretamente, sem necessidade de instalar dependências.

Para atualizar as métricas exibidas (novos membros/dia, ofertas/dia), edite os valores dentro do bloco `<script>`:

```js
var membrosMin = 4, membrosMax = 7;
var postMin = 20, postMax = 50;
```

## 📌 Próximos passos

- [ ] Conectar métricas reais (ex: via planilha ou API) no lugar dos valores simulados
- [ ] Adicionar analytics para medir cliques no botão do grupo
- [ ] Testar performance em diferentes dispositivos

---

Feito para divulgação do grupo **Seu Shop — Lugar de Comprar Barato** 🛍️
