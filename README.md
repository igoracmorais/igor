# Processamento de linguagem natural

O termo, também conhecido como NLP (Natural Language Processing) é entendido como uma área de inteligência artificial direcionada para o estudo e extração de informações de texto. Essa técnica também inclui o reconhecimento de voz, a criação de textos, análise de sentimento, tradução e diversas outras aplicações. Recentemente aumentou a aplicação dessas técnicas exatamente porque ficou mais fácil usar as diversas bibliotecas que estão disponíveis, em especial no Python. Particularmente gosto de trabalhar com a NLTK (Natural Language Toolkit) que já contém diversas funções que facilitam a análise como, por exemplo, para fazer stemming, lemmatization, parsing e tokenization, apesar do pacote não oferecer ferramentas de redes neurais. Mas, além do NLTK, também há outros que podem ser usados e que possuem diferentes funcionalidades, como o spaCy, scikit Learn, gensim, Pattern e Polyglot. Cada um desses pacotes possui uma funcionalidade diferente e ferramentas que podem ser úteis para determinados problemas. A questão é que, ao escolher um pacote para aplicar em NLP, tenha em mente a a disponibilidade da língua no qual pretende trabalhar, isso porque, em agluns pacotes não é possível usar o dicionário de português. <br>
Há diversas transformações que são feitas nas palavras em uma análise de NLP. Uma delas contempla o que se denomina de "embeded words". Nesse processo as palavras são colocadas em vetores, facilitando a interpretação de palavras iguais ou similares. Por exmeplo, podemos ter um vetor de animais, onde todos possuem dois olhos, quatro patas, rabo, unhas, focinho dentre outras característias. Outro vetor seria um que classificasse pessoas, com duas pernas, dois pés, dois braços, dois olhos, com cabelo e por ai vai. Dentre as diversas técnicas para lidar com esse procedimento em palavras, destaque para word2vec e Glove. O primeiro é um algoritmo criado pelo Google que atua de duas formas: i) continuous Bag-of-words - usado para preencher palavras faltantes em frases; ii) skip-gram - utilizado para prever o contexto da frase. Já o Glove atua no sentido de trabalhar com probabilidades de ocorrência de palavras a partir da razão entre as palavras fornecidas. br>

