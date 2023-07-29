#Case 1

Acredito que a melhor forma de saber o feedback do cliente sobre a eficiência da
equipe de suporte através de uma análise de dados, seria com um sistema de contato direto
com o cliente, ou seja, um help desk. Por exemplo, através de pesquisas de satisfação após
a conclusão do suporte, caso exista um sistema de chamado poderia se colocar esse
sistema de feedback na conclusão do chamado, algo que fosse rápido e eficiente para não
ocupar tempo do cliente e trazer dados valiosos para a empresa. Além das informações
coletadas através dos clientes, ainda teremos as que o próprio chamado nos informaria
como tempo de atendimento.
Os dados que considero importantes para a coleta seriam sem dúvidas, a velocidade em
que a equipe de suporte atendeu o chamado, o tempo necessário para a sua conclusão,
com qual eficiência o problema foi solucionado e se houve a necessidade de refazer o
chamado.

#Case 3

Acredito que uma, se não a melhor forma para manter a segurança e integridade do
sistema de gestão de acesso seja realizar a organização da estrutura do banco de dados no
formato blockchain, essa tecnologia poderia ser utilizada para a criação de registros
imutáveis de identidades e permissões de acesso. Ou seja, ao utilizar a descentralização e
criptografia, os dados de acesso se tornam muito mais seguros e transparentes, reduzindo
assim o risco de fraudes e violações.

#Case 5

SELECT *
FROM users_emails
WHERE data_cadastro >= DATE_SUB(CURRENT_DATE(), INTERVAL 30 DAY);
Primeiramente utilizamos o SELECT para selecionar todas as colunas da tabela
"users_emails.
No WHERE nós filtramos os registros de acordo com a data.
Suponhamos que a coluna com a variável DATA se chame "data_cadastro".
Usamos o CURRENT_DATE é uma função que retorna a data atual do sistema no
formato "YYYY-MM-DD".
O DATE_SUB é uma função que vai subtrair um intervalo de tempo de uma data, no
nosso caso 30 dias da data atual para se obter a data limite dos últimos 30 dias.
O INTERVAL 30 DAY está apenas demarcando que o intervalo para a função
DATE_SUB é de 30 dias.

Dessa forma a consulta retornará todos os registros da tabela onde a data de
cadastro está dentro dos últimos 30 dias.
