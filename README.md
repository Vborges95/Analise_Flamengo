# Análise Forense — Clube de Regatas do Flamengo

**Exercícios 2022–2025 | Projeção 2026–2027 | Quarto e último capítulo da série Rio**

O Flamengo fechou 2025 com receita operacional de R$ 1,5 bilhão consolidado — três a quatro vezes os pares do Rio — e quarto exercício consecutivo de patrimônio líquido em alta. Foi tetracampeão no ano em que disputou simultaneamente o Mundial de Clubes FIFA e a Copa Intercontinental. Mas a operação por dentro enfraqueceu: o EBITDA Recorrente Puro caiu para R$ 83 milhões na Controladora, o pior dos últimos quatro exercícios, com folha ampliada saltando de 45% para 54% da receita recorrente. A tese central desta análise é que o Flamengo não tem problema de solvência nem de fragilidade aguda, mas opera em hegemonia condicional — sustentada por um ciclo virtuoso que se manteve girando dentro do espectro histórico do clube, com vulnerabilidade efetiva concentrada na decisão estratégica de magnitude superior que atravessa os próximos vinte anos: financiar o estádio próprio no Gasômetro, projeto de R$ 3 a R$ 5 bilhões.

*Para ler a tese central, vá ao Substack. Para a análise completa com premissas, ao PDF. Para testar cenários alternativos, à planilha.*

---

## Conteúdo do projeto

📋 **[Executive Summary em PDF](Executive_Summary_Flamengo.pdf)** — Filtro de leitura de 2-3 minutos com tese central, números-âncora, cenários compactos, riscos rankeados e implicações por público. Para quem precisa decidir se vai mergulhar no resto do material.

📰 **[Versão resumida no Substack]([LINK_SUBSTACK](https://substack.com/profile/258523613-vinicius-borges/note/c-265687151))**

📄 **[Análise completa em PDF](Flamengo_analise_completa.pdf)** — Documento de 22 páginas com diagnóstico 2022-2025, projeção 2026-2027 nos três cenários, definição numérica de competitividade financeira, leitura aprofundada dos dois caminhos (Caminho A associativo vs. Caminho B SAF estrutural para o estádio), e conclusão por público. Cinco modelos de financiamento do estádio próprio discutidos individualmente.

📊 **[Planilha consolidada](flamengo_planilha_consolidada.xlsx)** — Modelo financeiro completo com 16 abas e 993 fórmulas. Inclui Balanço Patrimonial, DRE, decomposição forense de receita, DFC, análise operacional pura (EBITDA Recorrente Puro), painel de indicadores com formatação condicional das quatro condições, modelo de projeção 2026-2027 com três cenários totalmente editáveis pelo leitor, e seis abas anexas sobre temas específicos do caso Flamengo (Hilton, PROFUT/PERSE, Gasômetro, Fla-Flu Serviços, exposição cambial, recebíveis e inadimplências).

📘 **[Manual da planilha em PDF](Manual_da_planilha_Flamengo.pdf)** — Guia operacional standalone para quem baixou o repositório e quer entender as convenções visuais, anatomia das abas, glossário das métricas-chave, limitações da análise e como adaptar a planilha para outros clubes brasileiros.

📁 **[dados_brutos/](dados_brutos/)** — PDFs originais das Demonstrações Financeiras auditadas pela Ernst & Young, exercícios 2022, 2023, 2024 e 2025, com pareceres do auditor. Material público disponibilizado pelo próprio clube.

---

## Principais conclusões

- **EBITDA reportado de R$ 569 milhões em 2025 vs. EBITDA Recorrente Puro de R$ 83 milhões na Controladora.** A distorção de R$ 486 milhões é o tamanho do filtro de leitura que separa o tetracampeonato do diagnóstico operacional.

- **A folha deixou de PASSAR pela primeira vez na série.** Relação folha ampliada sobre receita recorrente saiu de 45% em 2024 para 54% em 2025, e permanece em APERTADO entre 55% e 58% em todos os seis cenários projetados (3 cenários × 2 anos). É o primeiro vetor a se acomodar em zona de pressão estrutural permanente.

- **Parecer EY 2025 saiu limpo, sem ênfases.** Primeira vez na história recente do clube. Efeito direto da homologação completa dos parcelamentos PROFUT e PERSE durante o exercício — a ênfase de "PROFUT em homologação" presente em 2022, 2023 e 2024 simplesmente deixou de fazer sentido em 2025.

- **R$ 174 milhões em premiações FIFA não se repetem em 2026, 2027 nem 2028.** Mundial só em 2029; Intercontinental depende de ganhar Libertadores anterior. Sem isolar os efeitos não-recorrentes, a leitura do balanço 2025 fica significativamente enviesada.

- **Em nenhum dos cenários historicamente realistas o caixa entra em zona crítica.** Mesmo no Pessimista 2027 (Brasileirão Top 6 e Libertadores oitavas em dois anos consecutivos), o Flamengo termina com R$ 186 milhões em caixa e margem EBITDA Recorrente Puro de 10,4%. A hegemonia se mantém em diferentes velocidades.

- **A decisão central dos próximos dois anos é sobre o estádio, não sobre o elenco.** Capex estimado de R$ 3 a R$ 5 bilhões é matematicamente incompatível com financiamento interno integral. Cinco modelos discutidos: interno, bancário sindicalizado, debêntures incentivadas Lei 12.431/2011, OUC sobre potencial construtivo do terreno (precedente em construção pelo Vasco em São Januário), e SAF dedicada ao estádio. Combinação é o desenho mais provável.

- **SAF integral não se aplica ao Flamengo — SAF do estádio sim.** Diferentemente dos casos Cruzeiro, Botafogo, Vasco e Atlético-MG, o clube não precisa de capital de salvação. Mas a constituição de uma SAF separada juridicamente, dedicada exclusivamente ao projeto do Gasômetro, preserva o controle da associação sobre as decisões esportivas e abre acesso a capital institucional de infraestrutura.

---

## Metodologia

- **Validações cruzadas obrigatórias.** Ativo = Passivo + Patrimônio Líquido em todas as seis colunas (Controladora 2022, 2023, 2024 e 2025; Consolidado 2024 e 2025); conciliação Δ Caixa = Caixa Final − Caixa Inicial fechada em 2024 e 2025; soma da decomposição analítica da linha "Participação, exposição, performance" fechando com o reportado em todos os exercícios. Limitações de 2022 e 2023 documentadas explicitamente nas notas.

- **Reapresentação 2022 e 2023 sob ITG 2003 R2.** Vendas de atletas isoladas para "Outras receitas operacionais" para comparabilidade direta com 2024 e 2025. A norma foi formalmente revogada em 01/01/2025, mas a apresentação contábil dos clubes brasileiros mantém o tratamento por aplicação dos CPCs 47 e 04.

- **EBITDA Recorrente Puro como métrica analítica central.** Parte do EBITDA reportado e desconta sequencialmente todos os efeitos não-recorrentes: ganhos com venda de atletas, ganhos com a liquidação do Hilton Rio By Yoo, equivalência patrimonial Fla-Flu, prêmios FIFA Mundial e Intercontinental, reversão líquida de contingências, desconto PERSE em Outras receitas operacionais (2023), acordo BACEN líquido (2022). Prioriza consistência intra-série em vez de fidelidade ao EBITDA divulgado pelo clube.

- **Quatro condições numéricas de competitividade financeira:** folha ampliada ≤ 65% da receita recorrente; margem EBITDA Recorrente Puro ≥ 5%; Capex em atletas ≤ 1,0x vendas de atletas; caixa total ≥ 1 mês de saídas operacionais. Cada condição classificada em PASSA / APERTADO / FALHA com critérios numéricos explícitos e formatação condicional automática na planilha.

- **Cenários calibrados pelo histórico recente do clube.** Premissas esportivas dos três cenários (Otimista, Base, Pessimista) ancoradas no histórico 2020-2025 do Flamengo no Brasileirão (campeão 2020 e 2025, vice 2021, 3º 2024, 4º 2023, 5º 2022). Top 2 / Top 4 / Top 6 como referências razoáveis para o espectro histórico do clube.

- **Capex de estádio fora do modelo principal.** O Modelo Runway projeta operação corrente sem incluir Capex de construção do estádio próprio. Decisão metodológica explícita — a magnitude do projeto (R$ 3 a R$ 5 bilhões) sobrescreveria a análise da operação corrente. A discussão estratégica está isolada na Seção 6.7 da análise completa, e o leitor pode adicionar o Capex extraordinário na aba Premissas Runway se quiser modelar o impacto.

---

## Série completa

Esta análise é o quarto e último capítulo da Série Rio sobre governança financeira do futebol carioca:

- ✅ **Vasco da Gama SAF** — publicado
- ✅ **Botafogo SAF** — publicado
- ✅ **Fluminense FC** — publicado
- ✅ **Clube de Regatas do Flamengo** — publicado (este repositório)

A metodologia é consistente entre os quatro estudos: mesmas convenções visuais, mesmas validações cruzadas, mesmas quatro condições de competitividade financeira (calibradas conforme as especificidades de cada clube), mesmo padrão de separação entre recorrente e não recorrente. Os quatro clubes da capital fluminense foram analisados sob a mesma régua, permitindo comparação direta entre os modelos de governança financeira. Quem leu qualquer um dos posts anteriores encontra estrutura familiar aqui — o que muda é o caso clínico, e ele muda bastante: do menor (Vasco) ao maior (Flamengo) clube por receita operacional, passando por uma SAF em recuperação judicial (Botafogo) e por um clube em discussão de SAF (Fluminense), o conjunto cobre a maior amplitude de configurações de governança possível dentro de um mesmo ecossistema regional.

---

## Autor e contato

**Vinicius Borges** — profissional de Financial Planning & Analysis baseado no Rio de Janeiro. Escreve sobre a intersecção entre finanças e esportes no Substack e no LinkedIn.

---

## Nota sobre os dados brutos

Os PDFs disponibilizados na pasta `dados_brutos/` são material público do Clube de Regatas do Flamengo, divulgado pelo próprio clube em cumprimento às obrigações de transparência aplicáveis a entidades desportivas profissionais. Os pareceres de auditoria são de responsabilidade da Ernst & Young Auditores Independentes S/S (auditor responsável: Marcelo Felipe L. de Sá, CRC RJ-094644/O), que mantém os direitos autorais sobre seu conteúdo técnico. Este repositório agrega os documentos para facilitar a reprodutibilidade da análise por outros pesquisadores.

A análise, planilha, manual e demais materiais derivados neste repositório são de autoria própria. Reprodução parcial é permitida com atribuição. A análise não constitui recomendação de investimento, parecer jurídico ou aconselhamento financeiro — é leitura analítica de dados públicos para fins de divulgação informativa.
