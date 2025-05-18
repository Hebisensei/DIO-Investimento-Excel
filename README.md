# DIO-Investimento-Excel
Repositório para envio de desafio atrelado ao uso de Excel para a criação de uma planilha de investimentos.

A planilha Excel vinculada a este repositório contém campos calculados para auxiliar e prever, de forma automática, resultados hipotéticos com base no valor a ser investido e as taxas (em %) informadas.

Como utilizar:

0. Noções Gerais:<br>
a) Campos com a cor de fundo cinza não devem ser alterados; são títulos fixos para outros campos;<br>
b) Campos com a cor de fundo azul claro são campos a serem preenchidos pelo usuário com suas próprias informações;
---------------------------------------------------------------------------------------------------------------
1. Tabela Configurações:<br>
	- Na tabela "Configurações", informe o salário percebido pelo investidor no campo a direita de "Salário".<br>
	- Abaixo do campo anterior, informe a taxa (em %) do rendimento em análise (ex.: 1,079% ou 15%); o campo a ser escrito em porcentagem aceita até 3 casas decimais.<br>
	- O campo "Sugestão de Investimento" retorna a quantia monetária sugerida, em termos gerais, a partir dos valores previamente informados.<br><br>
 
2. Tabela Investimento Mensal:<br>
	- No campo "Quanto investir por mês?", insira o valor que o investidor deseja investir mensalmente; não é vinculado ao resultado do item 1.3, podendo ser inserido valor diverso ao mesmo;<br>
	- No campo "Quantos anos?", insira quantos anos o investidor pretende investir a quantia informada no passo 2.1; insira anos completos (ex.: 1, 5, 10) e não os converta para meses; a conversão já é feita de forma automática onde é relevante;<br>
	- No campo "Taxa de rendimento mensal", informe a taxa de rendimento escrita em porcentagem (ex.: 1,079%, 1%, 0,081%);<br>
	- No campo "Patrimônio acumulado", o investidor poderá ver o quanto de patrimônio ele terá acumulado ao término do período de investimento (2.2) com base no valor investido mensalmente (2.1) e na taxa informada (2.3);<br>
	- No campo "Dividendos mensais", o investidor poderá ver o retorno monetário mensal que receberá ao seguir o investimento mensal (2.1) pelo período previamente especificado no passo 2.2.<br>

3. Tabela Cenários: A tabela "Cenários" ilustra, de maneira hipotética, o retorno financeiro que o investidor teria após preencher as lacunas na tabela 2 ("Investimento Mensal"); estes cálculos são automáticos e não devem ser alterados diretamente.<br>

4. Tabela "Investimentos com Base em Perfis":<br>
	- Primeiramente, escolha um tipo de perfil ao qual você melhor se encaixa (as opções são "conservador", "moderado" e "agressivo") utilizando a lista pré-estabelecida no campo; utilize o ícone da seta para baixo na lateral do campo a ser preenchido para ativar a lista;<br>
	- Insira no campo "Valor Mensal a ser investido" o quanto você pretende investir mensalmente; este campo não é vinculado a outros preenchidos anteriormente, permitindo maior flexbilidade na comparação de rendimentos;<br>
	- No caso das porcentagens pré-estabelecidas não serem adequadas ao tipo de perfil do investidor, siga os seguintes passos para alterá-los:<br>
		- Na parte inferior do documento Excel, vá para a planilha "Apoio_Perfis";<br>
		- Na nova planilha, altere os valores do campo "%" e apenas estes; escreva em porcentagem com o sinal matemático ao fim do número (ex.: 0,52%, 1%, 15%, 75%);<br>
   	- Retorne à planilha "Investimentos" e veja os novos cálculos após a modificação das porcentagens na planilha de apoio.<br><br>
