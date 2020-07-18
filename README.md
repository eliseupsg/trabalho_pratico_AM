# trabalho_pratico_AM
Este repositório se destina aos códigos utilizados no trabalho prático da disciplina de AM (EAD)

Nele encontram-se os notebooks do Jupyter utilizados para a tarefa de classificação de reviews de livros da Amazon utilizando word embeddings.
São três os arquivos do Jupyter:
- preprocessing: neste código o dataset original é pré-processado para a extração das características relevantes para o trabalho;
- embeddings: neste código o dataset processado é utilizado para o cálculo dos embeddings dos reviews; e
- classification: neste código são treinados e avaliados os modelos de classificação.

O dataset utilizado pode ser encontrado em http://www.cs.jhu.edu/~mdredze/datasets/sentiment/unprocessed.tar.gz e foi originalmente usado em "John Blitzer, Mark Dredze, Fernando Pereira. Biographies, Bollywood, Boom-boxes and Blenders: Domain Adaptation for Sentiment Classification. Association of Computational Linguistics (ACL), 2007".

O modelo pré-treinado de word embeddings utilizado pode ser encontrado em https://github.com/felipebravom/AffectiveTweets/releases/download/1.0.0/w2v.twitter.edinburgh10M.400d.csv.gz e foi originalmente usado em "Bravo-Marquez, F.; Frank, E.; Mohammad, S. M.; Pfahringer, B. Determining word-emotion associations from tweets by multi-label classification. In 2016 IEEE/WIC/ACM International Conference on Web Intelligence (WI) (Oct 2016), pp. 536–539."
