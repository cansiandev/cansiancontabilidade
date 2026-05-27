## Projeto Web: Cansian Contabilidade 📊

Esse site foi desenvolvido para a AP2 de Desenvolvimento Front-End. A ideia era colocar em prática tudo que vimos sobre layout responsivo, HTML semântico e principalmente os componentes do Bootstrap.

# 🔗 Link do Projeto
*(coloca o link aqui se tiver hospedado)*

# 📋 Tema Escolhido
Escolhi fazer um site para a **Cansian Contabilidade**, que é onde trabalho. Queria algo com cara de empresa séria, mas sem ser complicado de navegar. O foco é mostrar os serviços que a gente oferece e deixar o cliente agendar uma consulta de forma simples.

# 🏗️ Estrutura do Projeto
O site tem três páginas:

**index.html (Home):** Uma boas-vindas com um carrossel de imagens e alguns cards com os serviços mais procurados.

**servicos.html (Serviços):** Lista completa do que a contabilidade faz, separado por categorias: Fiscal, Trabalhista e Planejamento Tributário. Cada serviço tem um card com descrição e uma badge de "sob consulta".

**agendamento.html (Agendamento):** Um formulário pra cliente solicitar horário. Tem campos de nome, e-mail, telefone, escolha do serviço, data e hora.

# 🚀 Componentes do Bootstrap que usei
**Navbar:** O menu lá em cima que vira hambúrguer no celular. Coloquei o nome da empresa e os links.

**Dropdown:** No item "Serviços" do menu, pra deixar as opções organizadinhas.

**Carousel:** Na home, com 3 imagens e texto por cima. Fica passando sozinho mas dá pra clicar nos botões também.

**Cards:** Usei bastante. Na home tem 4 cards, na página de serviços tem 9. Ficou tudo padronizado.

**Grid System:** Usei row e col pra organizar os cards. No celular fica um embaixo do outro, no computador aparece vários lado a lado.

**Badges:** Coloquei aquelas etiquetas verdes "Sob Consulta" nos cards da página de serviços.

**Formulário:** Os campos de input, select e textarea vieram do Bootstrap, só ajustei um pouco no CSS.

# 📐 Decisões de Layout
**Responsividade:** Comecei pensando no celular e depois fui ajustando pra telas maiores. Os cards se empilham no mobile e vão se espalhando conforme a tela aumenta.

**Cores:** Usei fundo escuro no cabeçalho e rodapé (bg-dark) pra passar uma ideia de seriedade, coisa de contabilidade mesmo. O conteúdo principal ficou com fundo claro pra não cansar a vista.

**Navegação:** Deixei o menu sempre no topo, igual em todas as páginas, pro usuário não se perder.

# 🦾 Onde usei Flexbox (d-flex)
Precisei do flexbox pra alguns ajustes finos:

**Altura dos cards:** Usei mt-auto nos botões pra eles ficarem sempre no final do card, mesmo se a descrição fosse maior.

**Alinhamento dos títulos:** Na página de serviços, deixei o título do lado esquerdo e a badge do lado direito com justify-content-between.

**Rodapé:** Centralizei o texto com text-center.

# 🎨 O style.css que fiz por fora
Bootstrap sozinho já faz bastante coisa, mas eu quis dar uma temperada com um CSS próprio:

**Hover nos cards:** Quando passa o mouse, o card sobe um pouquinho e fica com uma sombra. Ficou sutil mas bonito.

**Transições:** Todos os botões e links têm uma animação leve, não é instantâneo.

**Cantos arredondados:** Dei uma arredondada nos cards, botões e no formulário. Ficou mais moderno.

**Responsividade extra:** No Bootstrap já é responsivo, mas ajustei manualmente a altura do carrossel no celular e tablet.

# 📝 Observações finais
**Semântica:** Usei header, main, section, article e footer. Nada de div vazia sem sentido.

**Validação:** O formulário tem o atributo required, então o navegador já avisa se faltar campo.

**Imagens:** Peguei tudo do Unsplash, banco gratuito, pra não ter problema com direitos autorais.

**Consistência:** As três páginas compartilham o mesmo header e footer, então a identidade visual fica igual em todo o site.