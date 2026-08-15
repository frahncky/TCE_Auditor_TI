# TCE-MA 2026 — Auditor Estadual de Controle Externo — Tecnologia da Informação

Apostila de preparação para o **Concurso Público do Tribunal de Contas do Estado do Maranhão (TCE-MA), Edital nº 1, de 6 de julho de 2026**, cargo **Auditor Estadual de Controle Externo — Especialidade: Tecnologia da Informação (Cargo 15)**.

## Base oficial

- Banca: **Cebraspe**.
- Prova de Auditor/TI: **29/11/2026**.
- Objetiva: **40 questões de conhecimentos gerais + 60 questões de conhecimentos específicos**.
- Pontuação: conhecimentos gerais = 1 ponto por questão; conhecimentos específicos = 2 pontos por questão.
- Discursiva: **1 peça de natureza técnica (até 60 linhas) + 2 questões discursivas (até 30 linhas cada)**.
- Vagas imediatas: **4**.
- Remuneração inicial indicada no edital: **R$ 20.112,20**.
- Jornada: **30 h semanais**.

Edital consultado: https://www.cebraspe.org.br/concursos/tce_ma_26

> **Corte de atualização do conteúdo:** 14/08/2026. O edital admite jurisprudência dos tribunais superiores publicada até 30 dias antes da prova. Por isso, a pasta `atualizacoes/` deve ser revisada até 30/10/2026 e novamente na semana da prova.

## Estrutura da apostila

```text
TCE_Auditor_TI/
├── main.tex
├── config/
│   └── preambulo.tex
├── capitulos/
├── questoes/
├── solucoes/
├── atualizacoes/
└── .github/workflows/build-pdf.yml
```

## Padrão obrigatório de profundidade teórica

A apostila **não deve ser escrita como resumo, fichamento ou lista de definições**. Cada tópico do edital deve ser tratado até o nível necessário para o candidato:

1. compreender o fundamento e a motivação do conceito;
2. conhecer estrutura, componentes, funcionamento e relações internas;
3. distinguir conceitos próximos e reconhecer exceções;
4. aplicar o conteúdo em situações concretas;
5. analisar riscos, controles, evidências e consequências quando houver relação com Auditoria/TI;
6. resolver questões conceituais, interpretativas, quantitativas e situacionais no nível de concurso;
7. redigir resposta discursiva tecnicamente fundamentada.

Quando o assunto exigir, a teoria deve incluir **deduções, equações, algoritmos, protocolos, arquitetura, fluxos, tabelas comparativas, casos completos, limitações, trade-offs, falhas recorrentes e pegadinhas de prova**. Um conceito não deve aparecer apenas em um parágrafo se sua compreensão exigir desenvolvimento maior.

## Padrão obrigatório do banco de questões

O objetivo do banco não é preencher quantidade. **Toda questão precisa treinar uma competência real de prova.** Questões óbvias, tautológicas ou puramente decorativas devem ser removidas, mesmo que isso reduza temporariamente a quantidade do capítulo.

### O que os níveis significam

Os níveis classificam **complexidade cognitiva e integração**, não uma escala de “questão fácil para questão difícil”. **Todas as questões devem estar em nível de concurso.**

- **N1 — Fundamento competitivo:** conceito fundamental cobrado com precisão terminológica, exceção, distinção ou pegadinha real de banca. Não usar perguntas triviais de definição isolada.
- **N2 — Aplicação:** exige aplicar conceito a cenário, cálculo, saída de código, arquitetura, norma, tabela ou pequeno estudo de caso.
- **N3 — Integração de concurso:** combina dois ou mais tópicos, traz distratores tecnicamente plausíveis, assertivas encadeadas ou interpretação de situação semelhante às provas de controle/TI.
- **N4 — Auditoria/avançado:** exige julgamento técnico, análise de evidência, risco, controle, arquitetura, priorização, falha sistêmica ou decisão entre alternativas imperfeitas.

### Perfis de banca

O banco deve preparar o candidato para o **Cebraspe e para o repertório das principais bancas**, porque questões de alto nível de FGV, FCC, Vunesp, AOCP e outras são úteis para aprofundamento. Devem aparecer, conforme o assunto:

- itens **Certo/Errado** com uma única palavra ou condição capaz de alterar o julgamento;
- múltipla escolha com **distratores próximos e tecnicamente defensáveis à primeira leitura**;
- conjuntos de assertivas I, II, III e combinações;
- estudo de caso com logs, tabelas, métricas, trechos de configuração, SQL, código ou arquitetura;
- questões quantitativas com cálculo necessário, não apenas substituição direta de fórmula;
- questões de norma em que o candidato diferencia princípio, requisito, exceção, papel, fase ou consequência;
- questões de auditoria em que a resposta correta depende de **suficiência da evidência**, não de preferência tecnológica.

### Critério para manter uma questão

Uma questão só entra no banco se cumprir pelo menos um destes objetivos:

1. explorar confusão recorrente de banca;
2. obrigar o candidato a aplicar um conceito;
3. integrar assuntos que costumam ser cobrados juntos;
4. testar exceção ou limite importante;
5. exigir interpretação de evidência, código, gráfico, tabela ou arquitetura;
6. simular decisão de Auditor/TI;
7. revisar ponto de alta probabilidade ou alto impacto no edital.

Questões do tipo “qual protocolo é X?”, “AES é simétrico?” ou “o que significa a sigla Y?” **não devem permanecer isoladamente** quando o mesmo conteúdo puder ser cobrado por um cenário mais sofisticado.

### Quantidade

A referência de produção continua sendo:

- N1: pelo menos 10;
- N2: pelo menos 15;
- N3: pelo menos 15;
- N4: pelo menos 10.

Esses números são metas de cobertura, **não obrigação de fabricar questões**. Qualidade prevalece. Se o capítulo ainda não possuir quantidade de questões realmente boas, ele deve ser marcado como incompleto até que questões de nível adequado sejam produzidas.

### Gabarito

As respostas **não aparecem após cada questão**. O capítulo apresenta primeiro todo o banco e os treinos discursivos. **Somente no final** aparece a seção de gabarito e resoluções comentadas, explicando:

- fundamento da resposta correta;
- por que cada distrator está errado ou incompleto;
- qual pegadinha/competência de banca foi explorada;
- quando pertinente, qual evidência adicional um auditor precisaria obter.

## Padrão obrigatório dos mapas mentais

Mapa mental não pode ser uma figura radial com palavras soltas. Ele deve funcionar como **ferramenta de revisão ativa**.

Cada mapa deve conter, de forma legível:

1. **núcleo conceitual** — a ideia central que organiza o assunto;
2. **hierarquia** — conceitos principais e seus desdobramentos;
3. **relações** — setas/verbos mostrando causa, dependência, contraste ou sequência;
4. **decisões de prova** — regras do tipo “se ocorrer X, pense em Y”;
5. **pegadinhas** — confusões que a banca explora;
6. **checklist de revisão** — perguntas curtas que o aluno deve conseguir responder sem consultar a teoria.

Sempre que o conteúdo for mais adequado a fluxo do que a radial, usar **mapa hierárquico, mapa de decisão, linha de processo ou quadro comparativo conectado**. O formato deve seguir o raciocínio do tema, e não uma estética fixa.

### Exemplo de mapa funcional

Em backup/continuidade, o mapa deve permitir reconstruir a decisão:

`Criticidade do serviço → BIA → RTO/RPO → estratégia de redundância/backup → teste de restauração → evidência → risco residual`.

Além do fluxo, deve lembrar: `RAID ≠ backup`, `snapshot local ≠ cópia independente`, `job concluído ≠ restore comprovado`.

## Método didático

Cada capítulo deve combinar:

1. teoria aprofundada;
2. exemplos resolvidos;
3. figuras/diagramas apenas quando melhorarem compreensão;
4. tabelas comparativas;
5. mapas mentais funcionais;
6. banco de questões N1–N4 em nível de concurso;
7. treino discursivo;
8. gabarito e resoluções somente no final.

## Conteúdo do edital coberto

### Conhecimentos gerais

- Língua Portuguesa.
- Competências Digitais e Informática Aplicada ao Setor Público.
- Raciocínio Lógico.
- Direito Administrativo.
- Direito Constitucional.
- Controle Externo.
- Legislação Específica do TCE-MA.
- História e Geografia do Estado do Maranhão.
- Noções de Direitos Humanos.

### Conhecimentos específicos — Auditor/TI

- Infraestrutura de TI.
- Engenharia de Dados.
- Engenharia de Software.
- Segurança da Informação.
- Gestão e Governança de TI.
- Fiscalização de Contratos de TI.
- Computação em Nuvem.
- Análise de Dados.
- Inteligência Artificial.
- Auditoria do Setor Público.

## Compilação

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

## Referências normativas prioritárias

A apostila trabalha com síntese e aplicação. Para revisão final, conferir fontes oficiais, especialmente Constituição Federal e Estadual, Lei nº 14.133/2021, LAI, LGPD, Lei nº 8.429/1992, Lei Orgânica e Regimento do TCE-MA, INs do TCE-MA, IN SGD/ME nº 94/2022, IN SEGES/ME nº 65/2021, COBIT 2019, ISO/IEC 38500, ITIL 4, ISO 31000, COSO, PMBOK 8ª edição, BPMN, ISO/IEC 27001/27002/27005, ISO 22301, NIST, DAMA-DMBOK, ISSAI e NBASP.
