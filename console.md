index.html:422 Console was cleared
index.html:423 --- Iniciando importação ---
index.html:463 Campo de destino do contato: contactId
index.html:464 Campo de origem do e-mail: ufCrm9_1762370891691 (do cabeçalho 'Email')
index.html:486 E-mails únicos para processar: (3) ['adrianomr21@gmail.com', 'adrianomr22@gmail.com', 'adrianomr23@gmail.com']
index.html:499 Enviando requisição para verificar contatos existentes... {adrianomr21@gmail.com: 'crm.contact.list?filter[EMAIL]=adrianomr21%40gmail.com&select[]=ID', adrianomr22@gmail.com: 'crm.contact.list?filter[EMAIL]=adrianomr22%40gmail.com&select[]=ID', adrianomr23@gmail.com: 'crm.contact.list?filter[EMAIL]=adrianomr23%40gmail.com&select[]=ID'}
index.html:506 Resposta da verificação de contatos: {result: {…}, time: {…}}result: result: adrianomr21@gmail.com: Array(1)0: {ID: '61'}length: 1[[Prototype]]: Array(0)adrianomr22@gmail.com: []adrianomr23@gmail.com: [][[Prototype]]: Objectresult_error: []result_next: []result_time: {adrianomr21@gmail.com: {…}, adrianomr22@gmail.com: {…}, adrianomr23@gmail.com: {…}}result_total: {adrianomr21@gmail.com: 1, adrianomr22@gmail.com: 0, adrianomr23@gmail.com: 0}[[Prototype]]: Objecttime: {start: 1764080426, finish: 1764080426.717469, duration: 0.7174689769744873, processing: 0, date_start: '2025-11-25T17:20:26+03:00', …}[[Prototype]]: Object
index.html:515 Contato existente encontrado para adrianomr21@gmail.com: ID 61
index.html:518 Nenhum contato encontrado para adrianomr22@gmail.com. Será criado.
index.html:518 Nenhum contato encontrado para adrianomr23@gmail.com. Será criado.
index.html:533 Enviando requisição para criar novos contatos... {adrianomr22@gmail.com: 'crm.contact.add?fields[NAME]=adrianomr22&fields[EM…r22%40gmail.com&fields[EMAIL][0][VALUE_TYPE]=WORK', adrianomr23@gmail.com: 'crm.contact.add?fields[NAME]=adrianomr23&fields[EM…r23%40gmail.com&fields[EMAIL][0][VALUE_TYPE]=WORK'}adrianomr22@gmail.com: "crm.contact.add?fields[NAME]=adrianomr22&fields[EMAIL][0][VALUE]=adrianomr22%40gmail.com&fields[EMAIL][0][VALUE_TYPE]=WORK"adrianomr23@gmail.com: "crm.contact.add?fields[NAME]=adrianomr23&fields[EMAIL][0][VALUE]=adrianomr23%40gmail.com&fields[EMAIL][0][VALUE_TYPE]=WORK"[[Prototype]]: Object
index.html:540 Resposta da criação de contatos: {result: {…}, time: {…}}result: result: {adrianomr22@gmail.com: 105, adrianomr23@gmail.com: 107}result_error: []result_next: []result_time: {adrianomr22@gmail.com: {…}, adrianomr23@gmail.com: {…}}result_total: [][[Prototype]]: Objecttime: {start: 1764080427, finish: 1764080427.518, duration: 0.5179998874664307, processing: 0, date_start: '2025-11-25T17:20:27+03:00', …}[[Prototype]]: Object
index.html:548 Novo contato criado para adrianomr22@gmail.com: ID 105
index.html:548 Novo contato criado para adrianomr23@gmail.com: ID 107
index.html:564 Mapa final de E-mail -> ID do Contato: Map(3) {'adrianomr21@gmail.com' => '61', 'adrianomr22@gmail.com' => 105, 'adrianomr23@gmail.com' => 107}[[Entries]]0: {"adrianomr21@gmail.com" => "61"}1: {"adrianomr22@gmail.com" => 105}2: {"adrianomr23@gmail.com" => 107}size: 3[[Prototype]]: Map
index.html:568 --- Preparando itens para importação ---
index.html:614 Linha 2: Payload do item a ser criado: {title: 'FD | ALGORITMO', ufCrm9_1760981163802: '02252122', contactId: '61', ufCrm9_1762370891691: 'adrianomr21@gmail.com', opened: 'Y'}contactId: "61"opened: "Y"title: "FD | ALGORITMO"ufCrm9_1760981163802: "02252122"ufCrm9_1762370891691: "adrianomr21@gmail.com"[[Prototype]]: Object
index.html:614 Linha 3: Payload do item a ser criado: {title: 'FD | INGLÊS', ufCrm9_1760981163802: '02222133', contactId: 105, ufCrm9_1762370891691: 'adrianomr22@gmail.com', opened: 'Y'}
index.html:614 Linha 4: Payload do item a ser criado: {title: 'PG AI | GESTÃO INTERNACIONAL', ufCrm9_1760981163802: '00222254', contactId: 107, ufCrm9_1762370891691: 'adrianomr23@gmail.com', opened: 'Y'}
index.html:632 --- Enviando 3 itens para o Bitrix ---
index.html:633 Comandos em lote: (3) ['crm.item.add?entityTypeId=1068&fields[title]=FD%20…0891691]=adrianomr21%40gmail.com&fields[opened]=Y', 'crm.item.add?entityTypeId=1068&fields[title]=FD%20…0891691]=adrianomr22%40gmail.com&fields[opened]=Y', 'crm.item.add?entityTypeId=1068&fields[title]=PG%20…0891691]=adrianomr23%40gmail.com&fields[opened]=Y']
index.html:645 Resposta do lote de itens [0-2]: {result: {…}, time: {…}}
index.html:652 Item do lote 0 criado com sucesso: {id: 299, xmlId: '', title: 'FD | ALGORITMO', createdBy: 13, updatedBy: 13, …}
index.html:652 Item do lote 1 criado com sucesso: {id: 301, xmlId: '', title: 'FD | INGLÊS', createdBy: 13, updatedBy: 13, …}
index.html:652 Item do lote 2 criado com sucesso: {id: 303, xmlId: '', title: 'PG AI | GESTÃO INTERNACIONAL', createdBy: 13, updatedBy: 13, …}
index.html:677 --- Importação concluída ---
