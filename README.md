# NaiveBayesPlayTennis
Aplicação do modelo Naive Bayes utilizando a linguagem R no exercício proposto no livro Artificial Intelligence - 
A Modern Approach de Stuart Russell e Peter Norvig (Play Tennis)

Naive Bayes é um classificador probabilístico simples baseado na aplicação do teorema de Bayes (ou regra de Bayes) com
fortes pressupostos de independência (ingênuos). Mais detalhes podem ser encontrados no site da Wikipedia:
http://en.wikipedia.org/wiki/Naive_baye


Para entender como construir um modelo de NB, vamos usar o exemplo do livro  (Inteligência Artificial - Uma Abordagem Moderna). 
Dado o conjunto de dados meteorológicos para prever a condição de reprodução. Existem 14 instâncias (ou exemplos)
e 5 atributos. Todos os atributos são nominais. Segue abaixo a massa de treinamento do modelo:


<table class="table table-bordered table-hover table-condensed">
<tbody><tr>
<td>aparencia</td>
<td>temperatura</td>
<td>humidade</td>
<td>vento</td>
<td>play</td>
</tr>
<tr>
<td>ensolarado</td>
<td>quente</td>
<td>alta</td>
<td>falso</td>
<td>não</td>
</tr>
<tr>
<td>ensolarado</td>
<td>quente</td>
<td>alta</td>
<td>verdadeiro</td>
<td>não</td>
</tr>
<tr>
<td>nublado</td>
<td>quente</td>
<td>alta</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>chuvoso</td>
<td>suave</td>
<td>alta</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>chuvoso</td>
<td>frio</td>
<td>normal</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>chuvoso</td>
<td>frio</td>
<td>normal</td>
<td>verdadeiro</td>
<td>não</td>
</tr>
<tr>
<td>nublado</td>
<td>frio</td>
<td>normal</td>
<td>verdadeiro</td>
<td>sim</td>
</tr>
<tr>
<td>ensolarado</td>
<td>suave</td>
<td>alta</td>
<td>falso</td>
<td>não</td>
</tr>
<tr>
<td>ensolarado</td>
<td>frio</td>
<td>normal</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>chuvoso</td>
<td>suave</td>
<td>normal</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>ensolarado</td>
<td>suave</td>
<td>normal</td>
<td>verdadeiro</td>
<td>sim</td>
</tr>
<tr>
<td>nublado</td>
<td>suave</td>
<td>alta</td>
<td>verdadeiro</td>
<td>sim</td>
</tr>
<tr>
<td>nublado</td>
<td>quente</td>
<td>normal</td>
<td>falso</td>
<td>sim</td>
</tr>
<tr>
<td>chuvoso</td>
<td>suave</td>
<td>alta</td>
<td>verdadeiro</td>
<td>não</td>
</tr>
</tbody></table>
