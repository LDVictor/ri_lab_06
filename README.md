# Recuperação da Informação e Busca na Web
## Laboratório 06: Modelo Vetorial

### Descrição

Nessa atividade você vai implementar várias instanciações do modelo vetorial. Para essa atividade, use esses dados.

De forma mais específica, você vai realizar as seguintes atividades:

1. Reconstruir o índice considerando o conjunto de dados que indicamos. Esses são os dados coletados por Bernardi e os estaremos usando para facilitar a correção da atividade. Se você já estiver usando esses dados não precisa reconstruir o índice;
2. Refinar o índice invertido de forma a também incluir o IDF (inverse document frequency) de cada termo do dicionário; (10 pts)
3. Implementar as seguintes versões do modelo vetorial:(10 pts)
  - Representação binária;
  - TF (lembre-se que esse modelo já está implementado);
  - TF-IDF;
  - BM25* (não usaremos Okapi já que os documentos não tem grande variação de tamanho).
4. Execute os algoritmos separadamente em 3 consultas de sua escolha e retorne os top-5 documentos mais similares à cada consulta; (10 pts)
5. Compare os resultados encontrados e responda. (20 pts)
  - Quais modelos você acha que trouxe os melhores resultados? Por que? Inspecione os documentos retornados para melhor embasar sua resposta.
  - Calcule e reporte o overlap par-a-par entre os resultados de cada modelo (usando o índice de Jaccard).

### Como entregar

Link no github para o Jupyter do Lab ou Colab. Além do código deve haver descrições textuais explicando o que foi feito. 

### Critérios de Avaliação

- Corretude da solução
- Clareza do código e organização do documento
- 5 pontos por dia de atraso

