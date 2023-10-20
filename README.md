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

RN01 - Autenticação: Somente funcionários autorizados poderão entrar no sistema por meio de login e senha.

RN02 - Cadastro de Produtos: Todos os pratos e bebidas cadastrados no sistema devem possuir descrição com suas informações.

RN03 - Relatórios: Somente o administrador poderá ter acesso aos relatórios finais de vendas e de caixa.

RN04 -  Edições de Pedidos: Os pedidos poderão ser editados por funcionários somente enquanto ainda estiverem em aberto. Após o fechamento do pedido, este poderá ser editado apenas pelo administrador.

RN05 - Delivery: Pedidos com delivery somente poderão ser registrados se informações básicas para contato com o cliente constarem no pedido.

# Requisitos Funcionais:

R.F. 01 - Menu de Opções: O sistema deve ter um menu de opções, que permita aos usuários o acesso às funcionalidades do sistema, que deverão ser: incluir um novo pedido, visualizar o total em caixa e visualizar todos os pedidos feitos no dia.

R.F. 02 - Cardápio: O sistema deve ter um cardápio completo com todos os produtos ofertados pelo restaurante, com seus preços e descrições.

R.F. 03 - Registro de Pedidos: O sistema deve permitir que os funcionários registrem pedidos de forma ráída, com a possibilidade de de selecionar os pratos escolhidos pelo cliente, forma de pagamento e informações adicionais (como o endereço para delivery).

R.F. 04 - Impressão: O sistema deve permitir a impressão de pedidos para que os mesmos sejam repassados para a cozinha.

R.F. 05 - Relatórios: O sistema deve gerar relatórios de vendas, incluindo relatórios de caixa total e relatórios de pratos vendidos.

R.F. 06 - Gerenciamentos de produtos: O sistema deve permitir o gerenciamento de pratos e bebidas disponíveis, que poderão ser editados pelo funcionário de acordo com a necessidade do restaurante.

R.F. 07 - Login e Senha: O sistema deverá permitir acesso somente aos funcionários autorizados por meio de login e senha.
    
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
