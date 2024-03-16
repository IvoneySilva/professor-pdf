# professor-pdf

Introdução

O Professor PDF é um aplicativo desenvolvido em Python, projetado para responder às suas perguntas sobre uma variedade de documentos PDFs. Utilizando linguagem natural, você pode fazer perguntas diretamente sobre o conteúdo dos PDFs. O aplicativo, então, fornece respostas relevantes baseadas no conteúdo desses documentos, graças ao uso de um sofisticado modelo de linguagem.
Por favor, note que o aplicativo está restrito a responder perguntas que estejam diretamente relacionadas aos PDFs carregados. Perguntas que não estejam contidas nos documentos carregados não serão respondidas. Portanto, certifique-se de fazer perguntas pertinentes ao conteúdo dos seus PDFs para obter as respostas mais precisas.


Como funciona



O aplicativo segue estas etapas para fornecer respostas às suas perguntas:
Carregamento de PDF: O aplicativo lê vários documentos PDF´s e extrai seu conteúdo de texto.
Fragmento de texto: O texto extraído é dividido em pedaços menores que podem ser processados de forma eficaz.
Modelo de linguagem: O aplicativo utiliza um modelo de linguagem para gerar representações vetoriais (incorporação) dos pedaços de texto.
Correspondência de similaridade: quando você faz uma pergunta, o aplicativo a compara com os blocos de texto e identifica os mais semanticamente semelhantes.
Geração de Resposta: Os pedaços selecionados são passados para o modelo de linguagem, que gera uma resposta baseada no conteúdo relevante dos PDFs.
Dependências e instalação

Para instalar o aplicativo Professor PDF, siga estas etapas:
Clone o repositório em sua máquina local.
Instale as dependências necessárias executando o seguinte comando:
pip install -r requisitos.txt


Obtenha uma chave API do OpenAI e adicione-a ao arquivo .env no diretório do projeto.
OPENAI_API_KEY=sua_chave_api_secreta

Uso

Para usar o aplicativo Professor PDF, siga estas etapas:
Certifique-se de ter instalado as dependências necessárias e adicionado a chave da API OpenAI ao arquivo .env.
Execute o arquivo main.py usando o Streamlit CLI. Execute o seguinte comando:
streamlit run app.py


O aplicativo será iniciado em seu navegador padrão, exibindo a interface do usuário.
Carregue vários documentos PDF no aplicativo seguindo as instruções fornecidas.
Faça perguntas em linguagem natural sobre os PDFs carregados usando a interface de chat.
Contribuindo

Este repositório tem a finalidade de ajudar universitários e pessoas afins  de cunho educacional. Serve como material de apoio para os estudantes. Sinta-se à vontade para utilizar e aprimorar seus estudos com o aplicativo professor PDF..
Licença

O aplicativo é lançado sob a licença MIT.
