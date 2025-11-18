Utilize o texto pré-processado na Atividade 1, ou encontre outro, para utilizar a análise de sentimentos baseada em léxicos. Será preciso incorporar conceitos próprios desta área como negação, intensificadores, adaptação de léxicos e regras linguísticas.

- Bibliotecas: NLTK, Pandas

Construa um dicionário manual com algumas palavras positivas e negativas encontradas no texto, também é possível utilizar dicionários existentes (como o SentiWordNet ou VADER, lembrando das particularidades ligadas a usá-los). Anote as palavras que foram utilizadas e quais ficaram de fora (sem polaridade).

Lembre que em caso de negação existe uma mudança na polaridade das palavras relacionadas, se um termo de negação aparece até 3 palavras antes de uma adjetivo ou advérbio é provável que o sinal será invertido. 

Crie listas para intensificadores (muito, extremamente, super, bastante) e outra para atenuadores (pouco, quase, meio), atribuindo valores que afetarão a polaridade (3/2 e 1/2).

Lembre que emojis também denotam emoções.

Aplicar algum cálculo para a polaridade final:
- Soma ponderada: $$\sum_{i=1}^n (pol(w_i) \times peso(w_i))$$
- Média: $$\frac1n \sum_{i=1}^n pol(w_i) $$
- Soma simples: $$\sum_{i=1}^n pol(w_i)$$
Obs.: Não fazer stemming, informações ão perdidas nesta forma.

- Resultados:
	-  A negação teve impacto? Foi o esperado?
	- Intensificadores realmente fizeram diferença?
	- Alguma palavra que pareceu importante ficou de fora?
	- Quais foram as dificuldades técnicas?
	- O que mais lhe chamou a atenção?
