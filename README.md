
# Assistente TCC

Chatbot capaz de interpretar e analisar documentos acadêmicos em PDF sobre privacidade e LGPD, permitindo aos usuários interagir com o conteúdo de forma natural e otimizada.



## Introdução

A implementação da Lei Geral de Proteção de Dados (LGPD) no Brasil trouxe desafios para pesquisadores e profissionais que precisam entender e aplicar seus princípios. Este projeto busca desenvolver um chatbot baseado em LLM que possa analisar PDFs de projetos acadêmicos, extrair informações relevantes e fornecer respostas com alto grau de precisão. Para garantir eficiência e escalabilidade, o sistema será desenvolvido no Azure Foundry e utilizará GPT-4.0 como modelo de linguagem e Embedded-3-Large como indexador semântico.


## Objetivos específicos

 - Implementar o GPT-4.0 como base para compreensão semântica e geração de respostas.
 - Integrar o modelo Embedded-3-Large para indexação eficiente dos documentos acadêmicos.
 - Desenvolver uma API conversacional, hospedada no Azure Foundry, para interação dinâmica com os usuários.
 - Testar e validar o chatbot com diferentes documentos acadêmicos sobre LGPD.




## Metodologia

O projeto deve seguir as seguintes etapas:

   
    1. Coleta e Pré-processamento de Dados: Seleção de projetos de TCC focados em privacidade e proteção de dados.
    2. Implementação do Modelo de Linguagem (LLM): Integração do GPT-4.0 para análise semântica dos textos extraídos.
    3. Indexação e Recuperação de Informações: a)Uso do Embedded-3-Large para organização e consulta rápida dos documentos. b)Ingestão de PDFs em texto estruturado.
    4. Testes e Ajustes: Validação com documentos reais e ajuste dos parâmetros para melhoria contínua.


## Justifcativa da escolha dos modelos

GPT-4.0
- Alto desempenho na compreensão semântica e geração de respostas coerentes.
- Capacidade de interpretar textos longos e complexos, ideal para documentos acadêmicos.
- Segurança e confiabilidade, já que é um modelo treinado com rigorosos padrões de qualidade.


Embedded-3-Large

- Eficiência na indexação e recuperação de informações com baixa latência.
- Precisão na associação semântica entre documentos, garantindo melhor contexto nas respostas.
- Otimização do armazenamento e busca de grandes volumes de informações acadêmicas.


## Resultados Esperados

- O chatbot foi capaz de analisar e responder questões sobre documentos acadêmicos de privacidade e LGPD.
- Trouxe facilidade de acesso à informação para estudantes e pesquisadores.
- Foi possível fazer a validação do uso de LLMs em análise documental dentro de ambientes acadêmicos.


## Testes & Resultados 

#### Questão 1: Indique quais são as principais violações de direitos analisados pela ANPD.

**Resposta 1:** 

As principais violações de direitos analisadas pela Autoridade Nacional de Proteção de Dados (ANPD) estão relacionadas a descumprimentos da Lei Geral de Proteção de Dados (LGPD). Entre as situações identificadas, destacam-se:
- Vazamento de Dados Pessoais: A ANPD atua em casos de vazamento de dados, analisando e autuando os responsáveis pelo ocorrido.
- Acessos Indevidos a Dados Pessoais: O órgão fiscaliza e toma providências contra acessos não autorizados a informações pessoais.
- Descumprimento de Direitos dos Titulares de Dados: A ANPD pode ser contatada pelos titulares quando seus direitos previstos na LGPD não são atendidos pelos controladores dos dados.
- Tratamento Automatizado com Viés Discriminatório: Conforme o artigo 20, § 3º da LGPD, a ANPD tem o poder de realizar auditorias para identificar aspectos discriminatórios no uso automatizado de dados pessoais.
- Infrações às Diretrizes de Segurança e Governança: A ANPD fiscaliza a estruturação dos sistemas de tratamento de dados, verificando se eles atendem aos requisitos de segurança, boas práticas e governança previstos na LGPD.

Essas violações podem levar a sanções que variam desde advertências simples até multas de até 2% do faturamento da empresa, bloqueio ou exclusão dos dados envolvidos, e suspensão ou proibição do tratamento de dados pessoais.

**3 referências**
- MATHEUS BRAGA BENEDI... COMPUTAÇÃO 2021.pdf - Part 1
- DIREITOSDOTITULARDED...DENAMENTOJURDICO.pdf - Part 1
- TCCKARINACARVALHO.pdf - Part 1


#### Questão 2: O que fala o artigo: A contribuição das Ouvidorias na Adequação a LGPD ? Resuma os principais pontos e traga os aspéctos negativos citados pela ANPD como principais erros no atendimento.

**Resposta 2:**
O artigo "A contribuição das Ouvidorias na Adequação à LGPD" destaca os seguintes principais pontos:

Principais Pontos Positivos:
- Atuação das Ouvidorias na Proteção de Dados: As Ouvidorias desempenham atividades que envolvem tratamento de dados pessoais, como coleta, armazenamento, transmissão e eliminação de informações. Por isso, estão sujeitas às regras da LGPD e devem se adequar aos processos de proteção de dados.
- Impacto na Governança de Privacidade: As Ouvidorias contribuem para a governança de privacidade ao registrar reclamações, atender clientes e analisar demandas. Esses processos utilizam dados pessoais e, portanto, são diretamente impactados pela LGPD.
- Contribuição para a Conformidade das Organizações: A adequação das Ouvidorias à LGPD pode ajudar as empresas a cumprir suas obrigações legais, fortalecendo a relação de confiança com os titulares e promovendo melhores práticas no tratamento de dados.

Aspectos Negativos Citados pela ANPD:

Embora o artigo não mencione diretamente os erros citados pela ANPD, ele implica alguns desafios que podem levar a problemas no atendimento, como:
- Falta de Adequação aos Processos da LGPD: Caso as Ouvidorias não se adaptem às normas da LGPD, podem ocorrer falhas no tratamento de dados pessoais, como coleta inadequada ou armazenamento inseguro.
- Desafios na Gestão de Dados Pessoais: A utilização de dados coletados por meio de formulários, telefone ou sites de terceiros pode gerar riscos de vazamento ou uso indevido, caso as práticas de segurança não sejam robustas.
- Inadequação na Resolução de Demandas: Erros no registro ou análise das reclamações podem comprometer a eficácia do atendimento e prejudicar a satisfação dos titulares de dados.

Resumo Geral:

O artigo evidencia que as Ouvidorias são fundamentais para a conformidade das organizações com a LGPD, mas também alerta para a necessidade de adequação e cuidado no tratamento de dados pessoais para evitar falhas que possam resultar em sanções. Assim, a implementação de boas práticas e governança é essencial para uma atuação eficiente e segura.

**1 referência:**
- 8_A_Contribuição_das...a_de_Privacidade.pdf - Part 1

