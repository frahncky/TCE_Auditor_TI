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
│   ├── 00_estrategia.tex
│   ├── 01_portugues.tex
│   ├── 02_competencias_digitais.tex
│   ├── 03_raciocinio_logico.tex
│   ├── 04_direito_administrativo.tex
│   ├── 05_direito_constitucional.tex
│   ├── 06_controle_externo.tex
│   ├── 07_legislacao_tce_ma.tex
│   ├── 08_historia_geografia_ma.tex
│   ├── 09_direitos_humanos.tex
│   ├── 10_infraestrutura_ti.tex
│   ├── 11_engenharia_dados.tex
│   ├── 12_engenharia_software.tex
│   ├── 13_seguranca_informacao.tex
│   ├── 14_gestao_governanca_ti.tex
│   ├── 15_fiscalizacao_contratos_ti.tex
│   ├── 16_computacao_nuvem.tex
│   ├── 17_analise_dados.tex
│   ├── 18_inteligencia_artificial.tex
│   ├── 19_auditoria_setor_publico.tex
│   ├── 20_discursivas.tex
│   └── 21_simulados.tex
├── atualizacoes/
│   └── README.md
└── .github/workflows/build-pdf.yml
```

## Padrão obrigatório de profundidade

A apostila **não deve ser escrita como resumo, fichamento ou lista de definições**. Cada tópico do edital deve ser tratado até o nível necessário para o candidato:

1. compreender o fundamento e a motivação do conceito;
2. conhecer estrutura, componentes, funcionamento e relações internas;
3. distinguir conceitos próximos e reconhecer exceções;
4. aplicar o conteúdo em situações concretas;
5. analisar riscos, controles, evidências e consequências quando houver relação com Auditoria/TI;
6. resolver questões conceituais, interpretativas, quantitativas e situacionais no nível Cebraspe;
7. redigir resposta discursiva tecnicamente fundamentada.

Quando o assunto exigir, a teoria deve incluir **deduções, equações, algoritmos, protocolos, arquitetura, fluxos, tabelas comparativas, casos completos, limitações, trade-offs, falhas recorrentes e pegadinhas de prova**. Um conceito não deve aparecer apenas em um parágrafo se sua compreensão exigir desenvolvimento maior.

## Método didático

Cada capítulo é estruturado, conforme a natureza do assunto, com:

1. **Teoria aprofundada e orientada ao Cebraspe**, sem superficialidade.
2. **Exemplos resolvidos** e situações de auditoria/controle público.
3. **Figuras, fluxos e diagramas** em TikZ quando agregam entendimento.
4. **Tabelas comparativas** para normas, modelos, protocolos e frameworks.
5. **Mapas mentais de revisão** ao fim das unidades.
6. **Banco de questões N1–N4**, sempre com **diversas questões por nível**, em progressão:
   - **N1 — Fundamentos:** reconhecimento, conceitos essenciais e relações básicas;
   - **N2 — Aplicação:** combinação de conceitos, cálculo e interpretação;
   - **N3 — Concurso:** nível esperado da prova, com distratores fortes e integração de tópicos;
   - **N4 — Avançado/Auditoria:** estudos de caso, integração entre áreas, risco, evidência, decisão e julgamento técnico.
7. **As respostas não aparecem após cada questão.** Todas as questões são apresentadas primeiro, sem gabarito visível.
8. **Gabarito e resoluções comentadas ficam somente no final do capítulo**, em seção própria, explicando:
   - por que a resposta correta está correta;
   - por que cada alternativa errada está errada;
   - qual conceito ou pegadinha a questão explora;
   - quando pertinente, qual seria a conclusão de auditoria.
9. **Blocos “Cebraspe pode cobrar assim”**, com pegadinhas e distinções conceituais.
10. **Treino discursivo**, incluindo peça técnica e respostas de até 30 linhas.

### Meta mínima de questões por capítulo

A quantidade depende da extensão do assunto, mas o padrão de produção é:

- **N1:** mínimo de 10 questões;
- **N2:** mínimo de 15 questões;
- **N3:** mínimo de 15 questões;
- **N4:** mínimo de 10 questões.

Esses valores são **mínimos, não máximos**. Capítulos extensos ou de maior peso podem excedê-los. Questões já existentes não devem ser removidas apenas para ajustar quantidade.

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

Localmente:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

O workflow do GitHub Actions também compila `main.tex` e publica o PDF como artefato.

## Referências normativas prioritárias

A apostila trabalha com síntese e aplicação, não reprodução integral de normas protegidas ou manuais. Para revisão final, confira sempre as fontes oficiais:

- Constituição Federal e Constituição do Estado do Maranhão.
- Lei nº 14.133/2021.
- Lei nº 12.527/2011 (LAI).
- Lei nº 13.709/2018 (LGPD).
- Lei nº 8.429/1992.
- Lei Estadual nº 8.258/2005 (Lei Orgânica do TCE-MA).
- Lei Estadual nº 9.936/2013.
- Regimento Interno do TCE-MA.
- IN TCE-MA nº 50/2017 e alterações.
- IN TCE-MA nº 82/2025.
- IN SGD/ME nº 94/2022.
- IN SEGES/ME nº 65/2021.
- COBIT 2019; ISO/IEC 38500; ITIL 4; ISO 31000; COSO; PMBOK 8ª edição; BPMN; ISO/IEC 27001/27002/27005; ISO 22301; NIST; DAMA-DMBOK.
- ISSAI 100, 200, 300 e 400; NBASP.

## Princípio de atualização

Como a prova está marcada para 29/11/2026, o material separa **conteúdo estável** de **conteúdo sujeito a atualização**. Jurisprudência, atos do TCE-MA, normas de contratação, segurança, nuvem e IA devem passar por revisão final antes da prova.
