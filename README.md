# Análise sobre aprendizado contínuo em sistemas conversacionais
Atividade referente à ponderada de programação da semana 9 do Módulo 7

## Contextualização do tema
A era digital tem testemunhado uma revolução silenciosa, mas profundamente significativa, na forma como nos comunicamos e interagimos com as máquinas. Em meio a esse fenômeno, a inteligência artificial (IA) emergiu como uma força motriz, moldando nossa interação com a tecnologia de maneiras que antes só poderiam ser vistas em obras de ficção científica. Nesse contexto, os chatbots, sistemas de conversação alimentados por IA, desempenharam um papel notável ao facilitar nossa vida diária e proporcionar uma nova dimensão à comunicação humano-máquina.


Os chatbots, muitas vezes relegados a meros assistentes virtuais em seu início, evoluíram para se tornar verdadeiros parceiros de conversação, capazes de compreender e responder a nuances da linguagem humana. Eles se infiltraram em setores como atendimento ao cliente, saúde, comércio eletrônico e educação, promovendo eficiência, personalização e acessibilidade. A chave para essa evolução está na capacidade dos chatbots de processar linguagem natural (NLP), uma conquista monumental da IA que permitiu a comunicação fluida entre humanos e máquinas.


No entanto, apesar dos avanços impressionantes, os chatbots enfrentam desafios significativos para se manterem relevantes em um mundo onde a linguagem é fluida e em constante evolução. O aprendizado contínuo dos mecanismos de processamento de linguagem natural é essencial para acompanhar as mudanças na forma como os seres humanos se comunicam. Vamos explorar alguns exemplos desses desafios que continuam a moldar o futuro dos chatbots e a experiência do usuário.

### Exemplo 1: Gírias e Jargões


A linguagem humana é rica em gírias, jargões e neologismos que surgem constantemente. Os chatbots enfrentam o desafio de compreender e responder a essas formas de expressão não convencionais. Por exemplo, a gíria "tá ligado" pode ser interpretada de maneira literal por um chatbot, quando na verdade significa "você entende" ou "você sabe". A capacidade de reconhecer e se adaptar a essas nuances é fundamental para manter uma comunicação eficaz.

### Exemplo 2: Evolução dos Significados


As palavras e frases não apenas adquirem novos significados ao longo do tempo, mas também podem variar de acordo com o contexto. Um exemplo clássico é a palavra "legal", que pode significar algo positivo em um contexto informal, mas não tem relação direta com a justiça. Os chatbots precisam aprender e contextualizar essas mudanças de significado para evitar mal-entendidos.

### Exemplo 3: Ironia e Figuras de Linguagem

A linguagem humana é repleta de figuras de linguagem, como ironia e metáforas, que podem ser desafiadoras para os chatbots interpretarem corretamente. Uma afirmação irônica pode ser confundida com uma declaração literal, resultando em respostas inadequadas.

---

Esses exemplos vívidos destacam a urgência da necessidade contínua de aprendizado dos mecanismos de processamento de linguagem natural (NLP) no mundo dos chatbots. A fluidez da linguagem e as mudanças constantes na forma como os seres humanos se comunicam são desafios intrincados que não podem ser subestimados. A capacidade de interpretar gírias, captar nuances de significado e reconhecer figuras de linguagem são marcos cruciais para a eficácia dos chatbots e sua aceitação na sociedade.

## Solução Proposta

Em resposta aos desafios enfrentados na adaptação contínua dos chatbots às mudanças na linguagem e na comunicação humana, foi proposto a implementação de um sistema de web crawler avançado para coletar e analisar postagens diárias de diversos usuários nas redes sociais. Esse sistema servirá como uma fonte rica de dados que permitirá uma compreensão em tempo real de como as pessoas se comunicam atualmente na internet.

Essa proposto tem como objetivo trazer os seguintes benefícios:

**Coleta de Dados em Tempo Real:** O web crawler será projetado para buscar e coletar postagens de diferentes plataformas de redes sociais, como Twitter, Facebook, Instagram e Reddit, em tempo real.

**Análise Semântica:** Os dados coletados serão submetidos a uma análise semântica avançada, usando técnicas de Compreensão de Linguagem Natural (NLU). Isso incluirá a detecção de gírias, identificação de mudanças de significado e interpretação de figuras de linguagem.

**Acompanhamento de Tendências:** O sistema será capaz de identificar e rastrear tendências emergentes na comunicação online, incluindo o uso de novas palavras, hashtags e tópicos populares.

**Atualização de Chatbots:** Com base nas informações coletadas e nas análises realizadas, os chatbots podem ser atualizados continuamente para melhor refletir a linguagem e as preferências de comunicação atuais dos usuários.

<img src="https://github.com/jordan-acs/aprendizado-continuo-jordan/blob/main/fluxogramaS9.png">

### Explicação da arquitetura

* **Bloco 1** : Representa a API Central da Aplicação, que irá realizar a conexão entre o chatbox, o base de dados e o Web Crawler.

* **Bloco 2**: Web Crawler responsável por realizar a busca por postagem nas mais diversas plataformas de comunicação entre comunidades digitais, obtendo dessa forma uma base de dados sempre atualizada com as diversas gírias e expresões que podem surgir e/ou se modificar ao longo do tempo.

* **Bloco 3**: Software de NLU responsável por interpretar os significados por trás de cada postagem, o que o usuário quis dizer com isso e como cada elemento constrói o raciocinío em torno daquela sentença.

* **Bloco 4**: Data Lake responsável por fornecer dados de treinamento para o chat bot, que estará diarimanete atualizando e otimizando sua base de dados com base nas novas tendências linguísticas que surgem nas redes socias.

## Conclusão

Neste artigo, exploramos a crescente importância da inteligência artificial, especialmente no contexto dos chatbots, na transformação da nossa forma de comunicação e interação com as máquinas. Desde o seu surgimento, os chatbots têm se estabelecido como parceiros de conversação cada vez mais sofisticados, permitindo uma comunicação mais eficaz e personalizada em diversos setores.

No entanto, identificamos desafios cruciais que ainda precisam ser superados para que os chatbots possam continuar a evoluir e oferecer experiências de usuário cada vez melhores. Estes desafios estão intrinsecamente ligados à necessidade de aprendizado contínuo dos mecanismos de processamento de linguagem natural (NLP), uma vez que a linguagem humana é fluida e em constante mudança.

Exploramos exemplos concretos desses desafios, incluindo gírias e jargões, a evolução dos significados das palavras e figuras de linguagem. Esses exemplos destacaram a complexidade da linguagem humana e a necessidade de sistemas de IA, como chatbots, compreenderem essas nuances.

Em resposta a esses desafios, propusemos a implementação de um sistema de web crawler avançado para coletar e analisar postagens diárias nas redes sociais. Esse sistema, alimentado por técnicas de processamento de linguagem natural, serviria como uma fonte rica de dados em tempo real, permitindo uma compreensão mais profunda de como as pessoas se comunicam na internet. Isso, por sua vez, contribuiria para o aprendizado contínuo dos chatbots, permitindo que eles se adaptem às mudanças na linguagem e na cultura online.

Em última análise, a IA e os chatbots estão desempenhando um papel crucial na evolução da nossa interação com a tecnologia. A capacidade de compreender e se adaptar à linguagem humana em constante mutação é fundamental para garantir que essas tecnologias continuem a melhorar nossas vidas e aprimorar nossas experiências digitais. À medida que avançamos nessa jornada, é essencial que continuemos a investir em pesquisa e desenvolvimento para enfrentar os desafios da comunicação em evolução e aproveitar todo o potencial da inteligência artificial.

## Referências

[Referência ](https://dl.acm.org/doi/abs/10.1145/3411564.3411647)

