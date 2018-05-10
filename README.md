# NaiveBayesPlayTennis
Aplicação do modelo Naive Bayes utilizando a linguagem R no exercício proposto no livro Artificial Intelligence - 
A Modern Approach de Stuart Russell e Peter Norvig (Play Tennis)

Naive Bayes é um classificador probabilístico simples baseado na aplicação do teorema de Bayes (ou regra de Bayes) com
fortes pressupostos de independência (ingênuos). Mais detalhes podem ser encontrados no site da Wikipedia:
http://en.wikipedia.org/wiki/Naive_baye


Para entender como construir um modelo de NB, vamos usar o exemplo do livro  (Inteligência Artificial - Uma Abordagem Moderna). 
Dado o conjunto de dados meteorológicos para prever a condição de reprodução. Existem 14 instâncias (ou exemplos)
e 5 atributos. Todos os atributos são nominais.

aparencia,temperatura,humidade,vento,play
ensolarado,quente,alta,falso,não
ensolarado,quente,alta,verdadeiro,não
nublado,quente,alta,falso,sim
chuvoso,suave,alta,falso,sim
chuvoso,frio,normal,falso,sim
chuvoso,frio,normal,verdadeiro,não
nublado,frio,normal,verdadeiro,sim
ensolarado,suave,alta,falso,não
ensolarado,frio,normal,falso,sim
chuvoso,suave,normal,falso,sim
ensolarado,suave,normal,verdadeiro,sim
nublado,suave,alta,verdadeiro,sim
nublado,quente,normal,falso,sim
chuvoso,suave,alta,verdadeiro,não
