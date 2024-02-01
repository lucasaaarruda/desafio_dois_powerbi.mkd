# Desafio Dois Power BI
Segundo desafio de Dados Power BI DIO
## Descrição
Cabeçalhos verificados, e tipos de dados atualizados se necessário.

Valores monetários atualizados de acordo com a necessidade.

O único valor nulo existente seria o James da tabela employee, em Super_ssn, por conta de ele já ser um gerente.

Não existem colaboradores sem gerente.

Não existem departamentos sem gerente.

Verificando os números de horas de alguns projetos, podemos perceber que alguns estão sobrecarregados, podendo ser dividido entre outros projetos de uma forma mais adequada.

A coluna complexa como endereço foi separada em linha de endereço 1 e 2, Cidade e Estado.

A coluna Fname e Lname foram mescladas, gerando uma nova coluna chamada FullName.

A tabela employee e departament foram mescladas, ficando visível quais departamentos estão associados aos colaboradores. Foi utilizado a forma de mesclar consulta para os dados não serem adversos, utilizando a ferramenta de mesclar, podemos associar os dados de uma tabela a outra, o que não pode ser feito na ferramenta combinar.

Por fim, não consegui executar os outros passos por conta de falta de dados, tive diversos problemas na hora de adicionar os dados a Azure ou até no Workbench...
