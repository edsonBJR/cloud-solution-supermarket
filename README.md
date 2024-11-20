# Cloud Solution Supermarket

Arquitetura para um sistema em nuvem para um grande supermercado.

Precisamos propor uma arquitetura para um sistema em nuvem para um grande supermercado que contratou o seu serviço.

Ele necessita que você controle primeiramente, antes de qualquer envolvimento financeiro a distribuição dos produtos dentro do supermercado.

Para isso sugeriu que iniciasse pelo cadastro de produtos, que sempre são identificados pelo nome, peso, cor predominante e fornecedor.

Além destes atributos o seu cliente deseja que você faça uma adequação nestes atributos para atender possíveis futuras demandas.

Os repositores são um tipo de funcionário que faz a reposição dos produtos de cada fornecedor e eles são identificados por nome, data de admissão e outras informações que você precisa julgar pertinentes para o controle correto do trabalho.

Você precisa controlar também qual o produto de qual fornecedor está em uma das prateleiras que são divididas por sessões de produtos. As sessões de produtos têm um nome, uma gama de fornecedores e cada um deles tem uma gama de produtos em cada sessão.

O seu sistema precisa controlar as datas de validade dos produtos para emitir avisos sobre quando os produtos estarão vencidos.

Além disto, precisamos através de uma integração com o sistema de caixa, dizer qual é o produto que está acabando na prateleira para que o repositor seja acionado.

Para que este controle seja possível vai se antecipar ao seu cliente e desenvolver um módulo que contabiliza a saída dos produtos pelo caixa, gerando a nota fiscal de cada compra e cadastrando o cliente para traçar um perfil em um futuro bem próximo.

