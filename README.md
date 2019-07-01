Colaboradores: [@fepas](https://github.com/fepas), [@CaioNunes](https://github.com/caionunes), [@CarlosAragon](https://github.com/carlosaragon)
# Pokedex

Repositório dedicado a introduzir os conhecimentos de *Deep Learning* para qualquer pessoa! Com um exemplo baseado no reconhecimento de pokemons!


<p align="center">
  <img src="https://img.rankedboost.com/wp-content/uploads/2016/07/Pokemon-Go-Pok%C3%A9dex-300x229.png" alt="Pokedex" />
  <br />
  <sub>"Quem é esse pokemon?"</sub>
</p>

## Mas o que é uma ***Pokedex***?

A Pokédex é um dispositivo eletrônico projetado para catalogar e fornecer informações sobre as várias espécies de Pokémon presentes nos videogames, animes e mangás de Pokémon. O nome Pokédex é um neologismo que inclui "Pokémon" (que em si é uma junção de "bolso" e "monstro") e "índice". No anime Pokemon, ela é capaz de identificar os pokemons já catalogados com uma simples imagem.
</br>

<p align="center">
  <img src="https://imgur.com/Rq3QGJs.gif" alt="butterfree" />
  <br />
  <sub>No anime pokemon, a pokedex sendo utilizada para fornecer informações sobre uma Butterfree</sub>
</p>

E esse é um dos tipos de técnologias que um modelo de **inteligencia artificial** baseado em ***deep learning*** pode proporcionar!

## Mas o que é *Deep Learning*?

Antes de tudo, precisamos enteder os conceitos de **Inteligencia Artificial**, **Machine Learning**, **Deep Learning**.

### *Inteligência Artificial* 

É a definição mais ampla das **máquinas capazes de realizar tarefas inteligentes, no sentido humano da palavra**. A AI abrange vários métodos, técnicas e práticas com algoritmos que tornam um software inteligente, como computação cognitiva, robótica, processamento de linguagem natural, ***machine learning*** e ***deep learning***.

### *Machine Learning* 
Consiste no aprendizado das máquinas, e existe um vasto número de algoritmos e metodologias. É a prática que permite aos softwares fazer previsões mais apuradas: as máquinas usam os algoritmos para **analisar dados e aprender com eles**, podendo então **fazer previsões ou determinações** acerca de alguma situação ou cenário dos mais variados assuntos e setores do mercado.

### *Deep Learning* 
É uma técnica muito específica de ***machine learning***, e consequentemente de inteligência artificial. É uma maneira de implementar a técnica específica, que usa as chamadas ***redes neurais artificiais***, correspondentes a uma classe de algoritmos de machine learning.

<p align="center">
  <img src="http://quantcoinvestimentos.com.br/wp-content/uploads/2018/11/Processo-machine-learning.bmp" alt="Diagrama IA" />
  <br />
  <sub>Diagrama que representa os relacionamentos entre as área de IA</sub>
</p>

Dessa forma, temos que ***deep learning*, é uma técnica de ***machine learning***, baseada em ***redes neurais artificiais***.

## Mas o que são essas Redes Neurais Artificiais?

O uso de redes neurais artificiais é uma abordagem **alternativa aos métodos estatísticos tradicionais**.Apresentam um modelo matemático **inspirado na estrutura neural de organismos inteligentes** e que adquirem conhecimento através da **experiência**. 
Qualquer rede neural é basicamente uma **coleção de neurônios** e conexões entre eles. O neurônio é uma função com um monte de entradas e uma saída. Seu objetivo é pegar todos os dados de sua entrada, executar uma função neles e enviar o resultado para a saída.

<p align="center">
  <img src="https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/05/20113236/neuron-300x188.png" alt="neurônio" />
  <br />
  <sub>Comparação estrutural entre um neurônio real e um neurônio artificial"</sub>
</p>

Um exemplo de um neurônio simples, mas útil na vida real, é um que:

- **Some todos os números das entradas** 
  - Se essa soma for maior que N - **dê 1 como resultado**. 
  - Caso contrário - **dê 1 como resultado**.

Conexões são como canais entre os neurônios. Eles **conectam saídas de um neurônio com as entradas de outro** para que possam enviar dígitos uns aos outros. Cada conexão tem apenas um parâmetro, o **peso**. **O peso é como uma força de conexão para um sinal**. Quando o número 10 passa por uma conexão com um peso de 0,5, ele se transforma em 5.

Esses pesos dizem ao neurônio para responder **mais a uma entrada e menos a outra**. Os pesos são **ajustados durante o treinamento** - é assim que a rede **aprende**.
<br />
<p align="center">
  <img src="https://i.vas3k.ru/7wf.jpg" alt="neurônio" />
  <br />
  <sub>Neurônio que realiza função descrita acima</sub>
</p>

Para impedir que a rede caia na anarquia, os **neurônios são ligados por camadas**, não aleatoriamente. Dentro de uma camada os neurônios não se unem, mas **unem-se as camadas seguintes e as camadas anteriores**. Os dados desse tipo de rede vão estritamente em uma direção - **das entradas da primeira camada às saídas da última**.
<br />
<p align="center">
  <img src="http://conteudo.icmc.usp.br/pessoas/andre/research/neural/image/camadas_an.gif" alt="rede neural" />
  <br />
  <sub>Conjunto de neurônios, agrupados em camadas, formando uma rede neural</sub>
</p>

"Ok, eu entendi o que é uma rede neural, mas e agora?"

Agora é o momento de lhe apresentar a galinha dos ovos de ouro, a **rede neural convolucional**.

## Mas o que é uma Rede Neurais Convolucional?

São uma classe de rede neural artificial que vem sendo aplicada com sucesso no **processamento e análise de imagens digitais**. Eles são usados para procurar objetos em fotos e vídeos, reconhecimento de face, geração e aprimoramento de imagens, criação de efeitos como slow-motion e melhoria da qualidade de imagens.

<p align="center">
  <img src="https://i.vas3k.ru/7rz.jpg" alt="rede neural convolucional" />
  <br />
  <sub>Imagem gerada pelo Detectron, plataforma de detecção de objetos do facebook</sub>
</p>
<br />
Mais alguns exemplos de como essa tecnologia está avançando cada vez mais rapidamente:

<p align="center">
  <img src="https://www.crcv.ucf.edu/projects/3D-CNN-segmentation/blackswan.gif"/>
  <br />
  
  <img src="https://www.crcv.ucf.edu/projects/3D-CNN-segmentation/bmx-trees.gif"/>
  <br />
  
  <img src="https://www.crcv.ucf.edu/projects/3D-CNN-segmentation/drift-chicane.gif"/>
  <br />
  
  <img src="https://www.crcv.ucf.edu/projects/3D-CNN-segmentation/libby.gif"/>
  <br />
  
  <sub>Detecções de objetos realizadas em vídeos</sub>
</p>

Incrivel não é? Treinando nossa rede neural convolucional com nossa [base de fotos de pokemons](https://www.kaggle.com/brkurzawa/original-150-pokemon-image-search-results/downloads/original-150-pokemon-image-search-results.zip/1), buscamos um resultado parecido!


Referencias:
<br />
https://imasters.com.br/desenvolvimento/qual-e-diferenca-entre-ai-machine-learning-e-deep-learning
https://imasters.com.br/devsecops/redes-neurais-artificiais-o-que-sao-onde-vivem-do-que-se-alimentam
http://conteudo.icmc.usp.br/pessoas/andre/research/neural/
https://vas3k.com/blog/machine_learning/
https://pokemon.fandom.com/wiki/Pok%C3%A9dex
https://github.com/facebookresearch/Detectron
https://www.crcv.ucf.edu/projects/3D-CNN-segmentation/

