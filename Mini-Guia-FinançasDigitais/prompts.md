**Demonstração dos testes de prompts no final deste arquivo!*

# Preferência de Respostas

**Todas as respostas devem começar com uma frase receptiva, por exemplo:**

"Sua questão é muito relevante, vamos conferir!"
"Ótima dúvida, veja:"
"Fico feliz em te ajudar com isso."
- Depois da frase receptiva, coloque um emoji feliz, pule uma linha e prossiga com resposta. A resposta deve vir de forma clara e objetiva.

**Quero que as respostas sejam:**

- Sem explicações muito longas.
- Faça uma breve analogia após a frase receptiva.
- Sempre trazendo exemplos práticos quando possível.
- Usando listas ou tópicos em vez de parágrafos extensos.
- Faça um breve resumo sobre [assunto] antes de finalizar.
- Dê **apenas** os pontos principais sobre [assunto], **se** for solicitado uma explicação profunda, **faça**.

**Quero que todas as respostas terminem com:**

"Gostaria que eu aprofunde mais algum ponto?"
"Quer explorar outro aspecto desse tema?"
"Estarei disponível para ajudar sempre que precisar!"

# Linha do Tempo das Finanças Digitais - Top 10 Eventos

- 2009: Criação do Bitcoin (primeira criptomoeda descentralizada).
- 2011: Primeiras altcoins (Litecoin e outras surgem como alternativas ao Bitcoin).
- 2015: Lançamento do Ethereum (introduz contratos inteligentes e amplia o uso do blockchain).
- 2017: Boom das ICOs (empresas levantam capital com ofertas iniciais de tokens).
- 2019: Stablecoins ganham força (ex: Tether, atreladas a moedas tradicionais).
- 2020: Popularização das DeFi (finanças descentralizadas, empréstimos e trocas sem intermediários).
- 2021: NFTs entram em destaque (tokenização de arte digital e colecionáveis).
- 2022: Avanço das CBDCs globais (China testa o Yuan Digital, outros países iniciam projetos).
- 2023: Início do DREX (Real Digital) no Brasil (projeto oficial de moeda digital do Banco Central).
- 2025: Expansão da tokenização de ativos reais (imóveis, títulos e commodities passam a ser negociados em blockchain).

# Reutilização de Prompts

"Compare [tecnologia A] e [tecnologia B]."
"Explique [termo] em linguagem simples (PLN)."
"Dê um exemplo prático de [conceito]."
"Monte um caso fictício de uso de [tecnologia] em um banco."
"Liste vantagens e desvantagens de [estratégia financeira]."
"Quais são os riscos e oportunidades de [tema]?"
"Quais são as limitações de [conceito] no mercado atual?"
"Liste 3 termos mais relevantes relacionados a [tema] e explique cada um."

# REGISTRO DOS TESTES DE PROMPTS

**Teste 1 -** Pergunta inicial com respostas baseadas apenas nas fontes abertas (links web e PDFs).

    Prompt 1: "Explique em linguagem simples o conceito de tokenização de ativos"

        - Resposta: Detalhada e dividida em conceitos. Resumo conclusivo no final.
        - Fonte: links web e PDFs.

**Teste 2 -** Pergunta feita pela própria sugestão do chat e respostas ainda baseadas apenas nas fontes abertas.

    Prompt 2: "Quais são as limitações da tokenização de ativos no mercado atual?"

        - Resposta: Ainda detalhada e dividida em conceitos. Sem resumo conclusivo no final.
        - Fonte: links web e PDFs.

**Teste 3 -** Segunda pergunta feita pela própria sugestão do chat e respostas ainda baseadas apenas nas fontes abertas.

    Prompt 3: "Como o Drex ajudará a resolver a falta de liquidez?"

        - Resposta: Continua detalhada e dividida em conceitos. Resumo conclusivo no final.
        - Fonte: links web e PDFs.

**Teste 4 -** Simples solicitação de resposta resumida.

    Prompt 4: "De forma resumida, o que é o Drex?"

        - Resposta: Definição por tópicos dos pontos principais. Sem resumo conclusivo no final.
        - Fonte: links web e PDFs.

**A partir do 5° teste é incluso a Seção "Preferência de Respostas" que criei no Estúdio do NotebookLM, a qual define como quero que as respostas sejam (focando em respostas objetivas, separadas em tópicos e, preferencialmente, citando os pontos principais do determinado assunto).*

**Teste 5 -** Repetição da pergunta inicial, porém, incluindo a fonte "Preferência de Respostas" (mensagem receptiva antecipando a resposta).

    Prompt 5: "Explique em linguagem simples o conceito de tokenização de ativos. Use tom receptivo."

        - Resposta: "Que bom que você perguntou! Vamos explorar o conceito de tokenização de ativos de forma simples e direta." [continua]. A continuação da resposta foi detalhada, definiu a Tokenização e mencionou em tópicos os pontos principais de como funciona. Citou exemplos para finalizar.
        - Fonte: links web, PDFs e Seção "Preferência de Respostas".

**Teste 6 -** Pergunta solicitando para resumir um determinado assunto e finalizar com uma pergunta agradável. 

    Prompt 6: "Resuma os principais usos da IA em bancos. Finalize perguntando se a pessoa quer saber mais e diga que está disponível."

        - Resposta: "Que bom que você perguntou! Vamos explorar os principais usos da Inteligência Artificial (IA) no setor bancário." [continua]. A resposta iniciou-se com a frase receptiva, deu uma explicação inicial, destacou em tópicos os pontos principais e os explicou. Finalizou com a frase: "Gostaria que eu aprofunde mais algum ponto? Estarei disponível para ajudar sempre que precisar!"
        - Fonte: links web, PDFs e Seção "Preferência de Respostas".

**Teste 7 -** Pergunta simples solicitando a diferença entre dois tipos de Bancos (testando minha lista completa da Seção "Preferências de Respostas")

    Prompt 7: "Como a IA diferencia um banco tradicional de um digital?"

        - Resposta: Iniciada com a frase receptiva reforçando a pergunta feita: "Que bom que quer saber sobre como a IA diferencia esses tipos de bancos!" [continua]. O restante da resposta foi focada nos pontos principais, os quais aparecem em tópicos bem explicados. Finaliza com a pergunta agradável: "Gostaria que eu aprofunde mais algum ponto?"
        - Fonte: links web, PDFs e Seção "Preferência de Respostas".

**Teste 8 -** Pergunta simples (testando a atualização que fiz dentro da fonte "Preferência de Respostas" - Respostas com definição inicial, pontos principais, exemplos e resumo geral no final)

    Prompt 8: "Como faço para investir em criptomoedas?"

        - Resposta: Iniciou com a frase receptiva, fez uma breve definição, citou os pontos principais em tópicos, incluindo os exemplos logo depois. Finalizou com o resumo geral e uma frase agradável.
        - Fonte: links web, PDFs e Seção " Preferência de Respostas".

**Teste 9 -** Criei uma nova Seção nomeada Linha do Tempo das Finanaças Digitais (lista cronológica com os 10 eventos mais relevantes de finanças) e adicionei nas fontes.

    Prompt 9: "Compare a importância do Bitcoin em 2009 com o DREX em 2023"

        - Resposta: Iniciou com a frase receptiva, fez uma breve analogia, citou os pontos principais de cada um, diferenciou ambos na prática, mencionou um exemplo e resumiu. Finalizou com uma pergunta agradável.
        - Fonte: links web, PDFs, Seções "Preferência de Resposta" e "Linha do Tempo das Finanças".