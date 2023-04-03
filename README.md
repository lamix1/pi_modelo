# Projeto Integrador - Modelo

# Modelos de Sistemas

**Gerenciamento de vendas para um Restaurante**

    A nossa cliente, Ana Cristina, tem um restaurante chamado Chawarma na Chapa, e, devido ao grande número de pedidos, ela acabou por ter a necessidade de um sistema para gerenciá-los. É de interesse do cliente que sejam emitidos relatórios de vendas, relatórios de caixa total, relatórios de pratos vendidos, gerenciamento de pratos disponíveis.


# Situação Problema

    A empresa chamada Chawarma na Chapa atua no ramo alimentício desde 2008, variando entre 3 a 5 funcionários além da proprietária Ana Cristina. O restaurante apresenta no menu opcões de Chawarma (um lanche Árabe), porções e bebidas.
    O cliente chega ao estabelecimento e escolhe um determinado prato. O pedido é anotado e repassado para a cozinha, que começa a prepará-lo. Terminado, o cliente está autorizado para buscar, comer no local ou para ter seu pedido entregue. Em situações de delivery, o cliente efetua o seu pedido pelo número do WhatsApp, o pedido é repassado para a cozinha e, quando finalizado, estará disponível para entrega ou retirada.
    O cliente tem diversas opções de pagamento, podendo escolher entre pix, dinheiro, cartão de crédito ou cartão de débito.
    Fora encontrada uma dificuldade em manter os pedidos em papel devido a facilidade de perca de informações e excesso de arquivos em papel para serem armazenados, então, pensando no melhor funcionamento da empresa, iremos desenvolver um sistema de vendas para que haja melhor organização e simplicidade para o restaurante.
    

# Descrição da proposta

    O sistema atuará como um gerenciador de vendas para o restaurante, facilitando desde o recebimento do pedido até a contagem do valor final em caixa.
    De início, o sistema contará com o menu principal, onde o funcionário terá acesso às seguintes opções: iniciar um novo pedido; visualizar o total em caixa; visualizar todos os pedidos feitos no dia.
    -Iniciar um novo pedido: O atendente terá acesso ao cardápio com todos os produtos ofertados pelo restaurante, podendo selecionar aqueles escolhidos pelo cliente. Após essa primeira etapa, será selecionada a forma de pagamento e, em caso de delivery ou retirada, serão anotadas as informações adicionais. Feito isso, o pedido ficará disponível para impressão.
    -Visualizar o total em caixa: O atendente poderá editar o valor total em caixa no início do expediente, e, ao longo do dia, serão somados os valores recebidos de pedidos no caixa com o valor inicial, gerando, assim, o valor total.
    -Visualizar todos os pedidos feitos no dia: Logo no menu inicial, ficará disponível uma lista com todos os pedidos feitos no dia e suas informações básicas, e, com um clique no respectivo pedido, o card será ampliado e as informações completas serão mostradas.

# Regras de Negócio:

    RN001 - O sistema deve ter um menu de opções, que permita aos usuários o acesso às funcionalidades do sistema, que deverão ser: incluir um novo pedido, visualizar o total em caixa e visualizar todos os pedidos feitos no dia.
    RN002 - O sistema deve ter um cardápio completo com todos os produtos ofertados pelo restaurante, com seus preços e descrições.
    RN003 - O sistema deve permitir que os funcionários registrem pedidos de forma ráída, com a possibilidade de de selecionar os preatos escolhidos pelo cliente, forma de pagamento e informações adicionais (como o endereço para delivery).
    RN004 - O sistema deve permitir a impressão de pedidos para que os mesmos sejam repassados para a cozinha.
    RN005 - O sistema deve gerar relatórios de vendas, incluindo relatórios de caixa total e relatórios de pratos vendidos.
    RN006 - O sistema deve permitir o gerenciamento de pratos disponíveis, que poderão ser editados pelo funcionário de acordo com a necessidade da empresa.
    RN007 - O sistema deverá permitir acesso somente aos funcionários autorizados por meio de login e senha. 
