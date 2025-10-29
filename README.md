# iot-entrada-escola-static-demo
Demonstração estática (simulada) da interface de usuário para o sistema (real) composto pelos repositórios a seguir:

- [iot-entrada-escola](https://github.com/Zidrewndacht/iot-entrada-escola)
- [servidor-entrada-escola](https://github.com/Zidrewndacht/servidor-entrada-escola)

Esta demonstração visa *apenas* apresentar os recursos e características da interface de usuário, como estilo, animações, layout responsivo, etc. O conteúdo pode não ser condizente com a implementação real (com banco de dados, servidor PHP, etc.). Por exemplo, ações como criar ou remover registros são ignoradas e páginas de "detalhes de responsável" podem não corresponder ao responsável selecionado. Essas limitações não ocorrem na implementação real.

Para visualização via GitHub Pages [aqui](https://zidrewndacht.github.io/iot-entrada-escola-static-demo/login).

Para visualizar a interface de administrador, faça "login" com email e senha em branco, ou clique [aqui](https://zidrewndacht.github.io/iot-entrada-escola-static-demo).

É possível visualizar o processo de gravação de cartões ao clicar em "gravar nova tag" para qualquer aluno. A interação de "gravação" é simulada com timers. A tela de splash é também simulada por um timer, a aplicação real pode ser mais rápida ou mais devagar que isso a depender da velocidade da rede.

Para visualizar a página de responsável clique [aqui](https://zidrewndacht.github.io/iot-entrada-escola-static-demo/resp.html) ou faça "login" usando qualquer email (exceto em branco). 

Envio de formulários ainda precisa ser corrigido. Causam falha na animação de fechamento do modal pois o servidor responde ao envio com 405. preventDefault() será implementado para que modais de formulário sejam apenas fechados sem nenhuma solicitação ao servidor.
