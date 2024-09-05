# Landing Page Restaurante
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/felippeximenes/landingpagerestaurante/blob/main/LICENSE) 

# Sobre o projeto

https://eclectic-khapse-fbe8e8.netlify.app/

Este projeto é uma landing page totalmente responsiva criada para um restaurante fictício. Foi desenvolvido com foco em design limpo, usabilidade e experiência do usuário, visando fornecer uma interface visualmente atraente e funcional para potenciais clientes conhecerem o restaurante e seus serviços.

# Funcionalidades Principais:

- Layout Responsivo: A página foi projetada para se adaptar a diferentes resoluções de tela, garantindo uma experiência de navegação fluida em dispositivos móveis, tablets e desktops.
- Galeria de Imagens: Uma galeria interativa onde os usuários podem visualizar imagens de alta qualidade dos pratos do restaurante.
- Integração com Redes Sociais: Links diretos para as principais redes sociais do restaurante, permitindo fácil conexão com a marca.


## Layout mobile

![Captura de tela 2024-09-05 162020](https://github.com/user-attachments/assets/171c2269-392c-4594-843f-d604ad531dc0)

![Captura de tela 2024-09-05 162031](https://github.com/user-attachments/assets/246588ca-ea98-4b67-b4f6-4e5e23700145)

## Layout web

![Captura de tela 2024-09-05 162201](https://github.com/user-attachments/assets/e089145c-cb13-4fd8-999c-b0e6e81fde33)

![Captura de tela 2024-09-05 162217](https://github.com/user-attachments/assets/907cc2ea-9b15-4e5a-9f98-7592ec1222f8)


## Layout tablet

![Captura de tela 2024-09-05 162053](https://github.com/user-attachments/assets/d8515bb2-3b55-4a51-8ad6-8a385b7c79c4)

![Captura de tela 2024-09-05 162108](https://github.com/user-attachments/assets/93d97bbc-4e1b-4256-976d-ada17a895294)

# Tecnologias utilizadas

- HTML5: Estrutura semântica e otimizada da página.
- CSS3 (Flexbox e Grid): Estilização moderna e responsiva, com uso de transições suaves e animações.
- JavaScript

# Descrição do Código:

O código utiliza principalmente jQuery e ScrollReveal.js para criar uma experiência de navegação interativa e animada. Abaixo estão os principais trechos explicados detalhadamente:

1. Interatividade do Menu Mobile:
Biblioteca Usada: jQuery
O código usa o evento click do jQuery para alternar a classe active no menu de navegação para dispositivos móveis, permitindo abrir e fechar o menu ao clicar em um botão.
Uso do toggleClass: Este método adiciona ou remove a classe active no menu mobile. Quando a classe é adicionada, o menu é exibido; quando removida, o menu é oculto.
Alteração do Ícone: O ícone dentro do botão muda dinamicamente, alternando entre o ícone de "hamburger" e o ícone de "fechar" (fa-x) através do toggleClass.

2. Mudança na Aparência do Cabeçalho com o Scroll:
O código ajusta a sombra do cabeçalho ao rolar a página. Quando o usuário está no topo da página, a sombra é removida; à medida que o usuário começa a rolar, a sombra é aplicada para melhorar a visibilidade do cabeçalho.
Uso do scrollTop() e outerHeight(): Determina a posição do scroll em relação ao topo da página e ajusta a altura externa do cabeçalho, aplicando uma sombra condicionada à rolagem.
Animação de Sombra: Adiciona ou remove a sombra (box-shadow) no cabeçalho com base na posição do scroll.

3. Destacar a Seção Ativa no Menu de Navegação:
Ao rolar a página, o código detecta a seção em que o usuário está e destaca o item de navegação correspondente no menu.
Uso do each() e offset(): O método each() percorre todas as seções da página. O offset().top retorna a posição da seção em relação ao topo da página, enquanto o outerHeight() captura a altura da seção.
Alteração do Item Ativo: A classe active é removida de todos os itens de navegação e adicionada ao item correspondente à seção visível no momento.
4. Animações com ScrollReveal.js:
Biblioteca Usada: ScrollReveal.js
A biblioteca ScrollReveal é usada para criar animações quando o usuário rola até elementos específicos na página. Cada revelação pode ser configurada para ter diferentes direções de origem, durações e distâncias.
Uso do ScrollReveal para o cta: O botão ou seção de "call-to-action" (#cta) aparece da esquerda para a direita, com uma duração de 2 segundos e percorrendo uma distância de 20% da largura da tela.
Revelação de Itens de Prato (.dish): Os elementos com a classe .dish também são animados da esquerda, com as mesmas configurações de duração e distância.
Revelação de Feedback: O feedback dos clientes (.feedback) é revelado da direita para a esquerda, criando um efeito de transição mais dinâmico para o usuário.

# Ferramentas Utilizadas:
jQuery: Facilita a manipulação do DOM e eventos de maneira simplificada. Ele é utilizado aqui para capturar eventos de clique, rolagem da página e para aplicar ou remover classes dinamicamente.

ScrollReveal.js: Biblioteca JavaScript usada para criar animações ao rolar a página. No código, ela é aplicada para introduzir elementos de forma suave e envolvente à medida que o usuário navega pelo site.

CSS e Box-Shadow Dinâmico: O uso de box-shadow no cabeçalho em combinação com o JavaScript permite uma resposta visual instantânea conforme a interação do usuário, aumentando a imersão visual.

Esse código melhora a experiência do usuário, tornando a página mais interativa e visualmente interessante com animações suaves e efeitos dinâmicos.

# Autor

Felippe Lorran Pires Ximenes

https://www.linkedin.com/in/felippe-ximenes-90848a106/
