# VerdadeClimática: Chatbot de Combate à Desinformação sobre Mudanças Climáticas

![VerdadeClimática](https://github.com/WagnerCorrey/Aula_pratica_Alura_Google/assets/169559380/e251c655-6890-4022-b9a0-8be5885bbf67)


### Descrição

Este projeto desenvolve um chatbot interativo no Instagram chamado **VerdadeClimática**, com o objetivo de combater a desinformação sobre mudanças climáticas e desmistificar teorias da conspiração. O chatbot utiliza técnicas de processamento de linguagem natural (PNL), embeddings de texto e um banco de dados de informações confiáveis para fornecer respostas precisas e relevantes às perguntas dos usuários. 

### Funcionalidades

* **Base de Dados Confiável:** Construída a partir de documentos científicos do IPCC e da NASA, além de fontes confiáveis que desmascaram teorias da conspiração como HAARP, Blue Beam e outras.
* **Geração de Embeddings:** Utiliza embeddings de texto para encontrar as respostas mais relevantes na base de dados, com base na similaridade semântica com a pergunta do usuário.
* **Integração com Instagram:** Permite interação direta com os usuários através de mensagens diretas (DMs) na plataforma.
* **Expansão Contínua:** A base de dados pode ser facilmente expandida com novas informações e perguntas, garantindo a atualização do chatbot frente a novas fake news.

### Tecnologias Utilizadas

* **Python:** Linguagem de programação principal do projeto.
* **PyPDF2:** Biblioteca para extrair texto de documentos PDF.
* **Beautiful Soup:** Biblioteca para web scraping, extraindo informações do site da NASA.
* **Sentence Transformers:** Biblioteca para gerar embeddings de texto.
* **Pandas:** Biblioteca para manipulação e análise de dados, utilizada para criar e gerenciar o banco de dados.
* **Rasa:** Framework para desenvolvimento de chatbots (opcional). 
* **Instabot:** Biblioteca para interagir com a API do Instagram.

### Como Executar

1. **Clonar o Repositório:** 
`git clone https://github.com/seu_usuario/seu_repositorio.git`

2. **Instalar as Dependências:**
``pip install -r requirements.txt``
3. **Baixar os Documentos:** Baixe os PDFs do IPCC e da NASA.

4. **Executar o Script:**
``python main.py``

Python
Estrutura do Projeto
~~~python
└── data
    └── base_conhecimento.csv

└── scripts
    └── extract_data.py
    └── create_database.py
    └── chatbot.py
    └── instagram_bot.py

└── requirements.txt

└── README.md
~~~

``/data:``  Pasta para armazenar os documentos PDF e o banco de dados.

``/scripts:``  Pasta para armazenar os scripts Python do projeto.

``extract_data.py:``  Script para extrair informações dos PDFs e do site da NASA.

``create_database.py:``  Script para criar e preencher o banco de dados.

``chatbot.py:``  Script para executar o chatbot (opcional, se utilizar o Rasa).

``instagram_bot.py:``  Script para integrar o chatbot ao Instagram.

``requirements.txt:``  Arquivo que lista as dependências do projeto.

``README.md:``  Arquivo com a descrição do projeto.

### Próximos Passos

* Aprimorar o sistema de processamento de linguagem natural para lidar com perguntas mais complexas.
* Implementar um sistema de feedback para receber avaliações dos usuários e aprimorar o chatbot.
* Expandir a base de dados com informações sobre outros tópicos relacionados à sustentabilidade e meio ambiente.

### Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

*Contato*
[Wagner Correa](https://github.com/WagnerCorrey) - [wagnerccardoso@gmail.com]
