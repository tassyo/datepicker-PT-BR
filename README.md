# datepicker-PT-BR
Tradução do datepicker para "PT-BR" + Bloqueio de datas anteriores à data corrente 

Modo de uso

1º importar todos .js e .css necessários para Datepicker funcionar.

2º Importar o datepicker-br.js onde for utilizar a validação

3º Modo de uso :

$(document).ready(function () {
	$("#datepicker").datepicker(
		$.datepicker.setDefaults( $.datepicker.regional['BR'])
	);	
});



