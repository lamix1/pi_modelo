# Projeto Integrador - Modelo

# Modelos de Sistemas

**Gerenciamento de vendas para um Restaurante**

A nossa cliente, Ana Cristina, tem um restaurante chamado Chawarma na Chapa, e, devido ao grande número de pedidos, ela acabou por ter a necessidade de um sistema para gerenciá-los. É de interesse do cliente que sejam emitidos relatórios de vendas, relatórios de caixa total, relatórios de pratos vendidos, gerenciamento de pratos disponíveis.


# Situação Problema

A empresa chamada Chawarma na Chapa atua no ramo alimentício desde 2008, variando entre 3 a 5 funcionários além da proprietária Ana Cristina. O restaurante apresenta no menu opcões de Chawarma (um lanche Árabe), porções e bebidas.

O cliente chega ao estabelecimento, se dirige a uma das mesas e escolhe um determinado prato. O pedido é anotado pelo garçom e repassado para a cozinha, que começa a prepará-lo. Terminado, o cliente recebe seu pedido.

O cliente tem diversas opções de pagamento, podendo escolher entre pix, dinheiro, cartão de crédito ou cartão de débito.

Fora encontrada uma dificuldade em manter os pedidos em papel devido a perca de informações e excesso de notas de papel para serem armazenadas, então, pensando no melhor funcionamento da empresa, iremos desenvolver um sistema de vendas para que haja melhor organização e simplicidade para o restaurante.
    

# Descrição da proposta

O sistema atuará como um gerenciador de vendas para o restaurante, facilitando desde a criação do pedido até a contagem do valor final em caixa. 

Sendo composto por um site utilizando Vue js e um app em React Native, o sistema ofertará, no app:
-Login exclusivo para cada garçom;

-Visualização dos pedidos em aberto;

-Criação de um novo pedido (com mesa, nome do cliente e itens do pedido).

Já o site ofertará: 

-Controle de logins de funcionários (adicionar, editar e remover);

-Visualização do histórico de pedidos;

-Visualizar cardápio (sendo possível tornar itens indisponíveis);

-Edição de cardápio (remover, adicionar e editar itens).

# Regras de Negócio:

RN01 - Autenticação: 
Apenas administradores têm acesso ao site;
Funcionários (garçons) têm acesso apenas ao aplicativo;
Cada funcionário deve ter um login exclusivo no aplicativo.

RN02 - Gerenciamento de Funcionários (Site): 
Apenas administradores podem acessar o site e editar, remover ou adicionar funcionários.

RN03 - Pedidos (App):
Garçons podem visualizar apenas os pedidos em aberto;
Cada pedido deve conter informações como mesa, nome do cliente e itens do pedido;
Garçons podem adicionar itens aos pedidos, editar a mesa ou o nome do cliente e marcar o pedido como concluído;
Pedidos concluídos não podem ser editados;

RN04 - Cardápio (Site):
Apenas administradores podem visualizar e editar o cardápio;
O cardápio deve conter informações sobre os itens, como nome, descrição, preço e disponibilidade;
Administradores podem adicionar, editar e remover itens do cardápio.

RN05 - Histórico de Pedidos (Site):
O site deve manter um histórico de todos os pedidos realizados, incluindo detalhes como data, mesa, nome do cliente e itens do pedido;
O histórico deve ser acessível apenas para administradores;

RN06 - Controle de Disponibilidade de Itens (Site):
Administradores podem marcar itens do cardápio como disponíveis ou indisponíveis;
Itens indisponíveis não podem ser adicionados aos pedidos.

RN07 - Cálculo do Valor Total (App): 
O aplicativo deve calcular automaticamente o valor total de cada pedido com base nos itens selecionados e seus preços.


# Requisitos Funcionais:

RF 01 - Autenticação: Apenas administradores têm acesso ao site.
        Funcionários (garçons) têm acesso apenas ao aplicativo.
        Cada funcionário deve ter um login exclusivo no aplicativo.

RF 02 - Gerenciamento de Funcionários (Site): Apenas administradores podem acessar o site e editar, remover ou adicionar funcionários.

RF 03 - Pedidos (App): Garçons podem visualizar apenas os pedidos em aberto.
        Cada pedido deve conter informações como mesa, nome do cliente e itens do pedido.
        Garçons podem adicionar itens aos pedidos, editar a mesa ou o nome do cliente e marcar o pedido como concluído.
        Pedidos concluídos não podem ser editados.

RF 04 - Cardápio (Site): Apenas administradores podem visualizar e editar o cardápio.
        O cardápio deve conter informações sobre os itens, como nome, descrição, preço e disponibilidade.    
        Administradores podem adicionar, editar e remover itens do cardápio.

RF 05 - Histórico de Pedidos (Site): O site deve manter um histórico de todos os pedidos realizados, incluindo detalhes como data, mesa, nome do cliente e itens do pedido.
        O histórico deve ser acessível apenas para administradores.

RF 06 - Controle de Disponibilidade de Itens (Site): Administradores podem marcar itens do cardápio como disponíveis ou indisponíveis.
        Itens indisponíveis não podem ser adicionados aos pedidos.

RF 07 - Cálculo do Valor Total (App): O aplicativo deve calcular automaticamente o valor total de cada pedido com base nos itens selecionados e seus preços.

# Requisitos Não funcionais:

R.N.F. 01 - Segurança: O sistema deve garantir a segurança dos dados dos clientes. Isso pode incluir o uso de criptografia, autenticação de usuário e protocolos de segurança. 

R.N.F. 02 - Atuação: O sistema deve ser rápido e eficaz na execução de tarefas, desde o processamento de pedidos até a exibição de informações dos produtos e disponibilidade.

R.N.F. 03 - Manutenção: O sistema deve ser fácil de manter e atualizar, com um código bem estruturado e documentado.

R.N.F. 04 - Confiabilidade: O sistema deve ser capaz de lidar com erros sem impactar a experiência do usuário e deve ser capaz de recuperar dados em caso de perda.

R.N.F. 05 - Usabilidade: O sistema deve ser fácil de usar e intuitivo para seus usuários, com um layout bem claro e informações relevantes apresentadas de forma clara.

R.N.F. 06 - Compatibilidade: O sistema deve ser capaz de se integrar com outros sistemas.

R.N.F. 07 - Disponibilidade: O sistema deve estar disponível para os usuários sempre que necessário, sem interrupções ou grandes falhas.

R.N.F. 08 - Banco de Dados: O sistema será implementado com MySQL.

R.N.F. 09 - Framework: Os frameworks utilizados para o desenvolvimento do sistema serão o VueJs e o React Native.

R.N.F. 10 - Linguagens: O sistema deverá ser desenvolvido com as linguagens JavaScript, HTML5, e CSS3.
