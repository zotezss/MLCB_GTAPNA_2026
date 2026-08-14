--- RESULTADOS DO LAB 01 ---
Mensagem: 'Quero consultar quanto dinheiro tenho' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Pode me ajudar a fazer um pix?' ==> Intenção Predita: [fazer_pix]
Mensagem: 'Gostaria de cancelar meu cartão de crédito' ==> Intenção Predita: [cancelar_conta]

#========== PRODUÇÃO DO RELATÓRIO:==============
# Para a entrega completa deste LAB01 você precisa copiar a saída do código (output) e adicionar as repostas das perguntas abaixo:
# 1 - Avaliem os resultados e verifiquem se os resultados foram corretos ou incorretos. Coloque a resposta no arquivo do relatório do laboratório. r: Esta incorreto, pois os codigos podem gerar resultados com muita incoerencia, dependendo da frase no qual ela indica

# 2 - Detectado algum erro, qual seria a maneira mais correta de melhorar o resultado do algoritmo? r: É recomendado que se melhore primeiro o dataset e a divisao de dados.

# 3 - Detalhe a função do LogisticRegression no algorítmo. R:Essa função serve para relacionar as as palavras com suas intenções.



--- RESULTADOS DO LAB 02 ---
Mensagem de Teste: 'Gostaria de devolver o produto que comprei'
Intenção Predita: troca_devolucao

--- Distribuição de Probabilidades por Classe ---
Classe [duvida_frete]: 27.99%
Classe [rastrear_pedido]: 24.54%
Classe [troca_devolucao]: 47.46%

# Para a entrega completa deste LAB02 você precisa copiar a saída do código (output) e adicionar as repostas das perguntas abaixo:
# 1 - Avaliem os resultados e verifiquem se os resultados foram corretos ou incorretos. Coloque a resposta no arquivo do relatório do laboratório R: Correto.
# 2 - Detectado algum erro, qual seria a maneira mais correta de melhorar o resultado do algoritmo? R: Não tem erro.
# 3 - Detalhe a função do Naive Bayes no algorítmo. R: Aonde o modelo aprende os exemplos do dataset.


--- RESULTADOS DO LAB 03---

# Para a entrega completa deste LAB03 você precisa colar o código corrigido com os TODOs preenchidos, a acurácia obtida e responder:
# 1 - Qual foi a acurácia obtida pelo modelo no conjunto de teste e por que, em um dataset tão pequeno (9 exemplos), essa métrica pode ser enganosa? Acurácia do Modelo: 0.00%
# 2 - Como o modelo de Árvore de Decisão (DecisionTreeClassifier) toma a decisão de separar as intenções do usuário? R: Decide de separar as intenções analisando as palavras presentes nas mensagens.
# 3 - Qual é o risco de utilizar uma Árvore de Decisão sem limite de profundidade (max_depth) em datasets de texto maiores?
r: Ela cria divisôes demais para um sistema não é nescessario.






