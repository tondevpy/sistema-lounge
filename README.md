# sistema-lounge

Este projeto é um registro de consumo em um lounge de uma tabacaria chamada "Smoke". A aplicação permite adicionar mesas, onde cada mesa representa um cliente, e registrar os produtos consumidos, o valor total gasto e a forma de pagamento.

A página inicial exibe uma seção para adicionar mesas, onde o usuário pode inserir o nome do cliente, os produtos consumidos, o valor total gasto e selecionar a forma de pagamento. Ao adicionar uma mesa, ela é exibida na área de mesas abertas.

Cada mesa possui um formulário para preencher as informações do cliente e registrar o consumo. Após preencher todos os campos, o usuário pode fechar a mesa, o que remove a mesa da lista de mesas abertas e gera um relatório com os dados da mesa fechada.

O resumo diário exibe o total de mesas abertas e o valor total ganho no dia até o momento. Há também um botão para limpar o relatório, removendo todos os registros de mesas fechadas.

O projeto utiliza JavaScript para manipular o DOM e armazenar os dados localmente utilizando o recurso de LocalStorage do navegador. Dessa forma, os dados são preservados mesmo após recarregar a página ou fechar o navegador.

