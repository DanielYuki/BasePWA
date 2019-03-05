# Base para criação de um PWA(Progressive Web App)

### Elementos de um PWA:
- Uma página de entrada com referências aos demais arquivos do projeto (index.html)
- Um **manifest** (manifest.json)
- Um **service-worker** (service-worker.js)
- Um arquivo de **script** com o código para registro do service-worker (main.js)

#### Elementos Extras
- Um arquivo de de estilo **CSS** (main.css)
- Imagens de ícone

#### Notas:
- Este Repositório é apenas uma **BASE** para aplicações em PWA, e é possível adicionar mais coisas para fazer com que seu WebApp fique melhor
- 95% Pronto -> "git clone" -> necessário fazer alguns pequenos ajustes dependendo da aplicação
- Manifest é responsável por prover informações sobre o App, tais como o Nome, ícone e Descrição
- Service-Worker basicamente é uma API que permite o WebApp funcionar **OFFLINE**, e oferecendo um controle melhor aos Desenvolvedores