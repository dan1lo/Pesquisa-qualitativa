# Pesquisa Qualitativa em Computação

Material didático dos módulos M1 e M2 da disciplina **Pesquisa Qualitativa em Computação**, do Programa de Mestrado e Doutorado Profissional em Engenharia de Software da **CESAR School**.

| Módulo | Fim de semana | Tema | Professor |
| --- | --- | --- | --- |
| M1 | FDS1 | Fundamentos e desenho de estudos qualitativos | Prof. Danilo Monteiro Ribeiro |
| M2 | FDS2 | Entrevistas, observação e diários de pesquisa | Prof. Danilo Monteiro Ribeiro |
| M3 | FDS3 | Análise documental, codificação e ferramentas | Profa. Suzanna |
| M4 | FDS4 | Rigor, validade, escrita e apresentação final | Profa. Suzanna |

Ao longo da disciplina, cada aluno constrói um **protocolo de pesquisa qualitativa** aplicado ao próprio projeto de dissertação ou tese. A avaliação é feita por apresentações do projeto em todos os fins de semana a partir do segundo.

## Estrutura do repositório

O material está organizado por aula. Cada aula tem sua própria pasta, com os textos e recursos usados naquele encontro.

```
Pesquisa qualitativa/
├── README.md
└── aula-01/
    ├── artigos fakes/
    │   ├── artigo_fake_01_estudo_de_caso.docx
    │   ├── artigo_fake_02_etnografia.docx
    │   ├── artigo_fake_03_grounded_theory.docx
    │   ├── artigo_fake_04_pesquisa_acao.docx
    │   └── artigo_fake_05_pesquisa_qualitativa_basica.docx
    ├── artigos reais/
    │   ├── actionresearch.pdf
    │   ├── estudo de caso.pdf
    │   ├── etnografia_true.pdf
    │   ├── icse17sedano_gt.pdf
    │   └── paul_quali.pdf
    ├── definicao/
    │   ├── artigo carolyn 1999.pdf
    │   └── artigo carolyn.pdf
    └── IA/
        └── Demonstração ao vivo: um LLM lê uma fala de entrevista.docx
```

| Pasta | Aula | Situação |
| --- | --- | --- |
| `aula-01/` | M1, FDS1: fundamentos, desenhos de pesquisa e IA | Disponível |
| `aula-02/` | M2, FDS2: entrevistas, observação e diários | Em preparação |

# Aula 1: fundamentos, desenhos de pesquisa e IA

## `aula-01/definicao/`

Textos de base sobre o que é pesquisa qualitativa em engenharia de software, usados na leitura dirigida da sexta do M1.

| Arquivo | Referência |
| --- | --- |
| `artigo carolyn 1999.pdf` | Seaman, C. B. (1999). Qualitative methods in empirical studies of software engineering. *IEEE Transactions on Software Engineering*, 25(4), 557-572. |
| `artigo carolyn.pdf` | Seaman, C., Hoda, R., & Feldt, R. (2025). Qualitative research methods in software engineering: past, present, and future. *IEEE Transactions on Software Engineering*. |

## `aula-01/artigos fakes/`

Cinco artigos **fictícios**, escritos para fins didáticos, que estudam **o mesmo fenômeno** com desenhos diferentes: a adoção de assistentes de código baseados em IA em times de desenvolvimento de empresas fictícias do Porto Digital, no Recife. Como só o desenho muda entre eles, as diferenças entre os métodos ficam visíveis.

| Arquivo | Desenho | O que o artigo mostra |
| --- | --- | --- |
| `artigo_fake_01_estudo_de_caso` | Estudo de caso | Caso único com duas unidades incorporadas, proposições iniciais, triangulação e explicação rival |
| `artigo_fake_02_etnografia` | Etnografia | Imersão de 7 meses, perspectiva êmica, notas de campo descritivas e reflexivas, planta do espaço |
| `artigo_fake_03_grounded_theory` | Grounded Theory | Amostragem teórica em ondas, memorandos, codificação até a categoria central |
| `artigo_fake_04_pesquisa_acao` | Pesquisa-ação | Três ciclos de intervenção, incluindo um que fracassa e vira o principal aprendizado |
| `artigo_fake_05_pesquisa_qualitativa_basica` | Survey qualitativo | Entrevistas com amostra definida no início e análise temática reflexiva |

Todos seguem a mesma estrutura: questões de pesquisa, caixas de decisão metodológica, figura com bloco “Como ler”, o que o método não pode responder, critérios de qualidade, perguntas para reflexão e um anexo com antipadrões.

> Os artigos são inteiramente fictícios. Empresas, pessoas, falas e resultados foram inventados e não devem ser citados como evidência.

## `aula-01/artigos reais/`

Um artigo real para cada desenho, de preferência com cerca de 10 páginas e listado como exemplar nos [ACM SIGSOFT Empirical Standards](https://www2.sigsoft.org/EmpiricalStandards/). Cada grupo lê o artigo real do seu desenho antes do FDS1 e o compara, em sala, com o artigo fictício correspondente.

| Arquivo | Desenho | Referência |
| --- | --- | --- |
| `estudo de caso.pdf` | Estudo de caso | [confirmar referência] |
| `etnografia_true.pdf` | Etnografia | [confirmar referência] |
| `actionresearch.pdf` | Pesquisa-ação | [confirmar referência] |
| `paul_quali.pdf` | Survey qualitativo | [confirmar referência] |
| `icse17sedano_gt.pdf` | Grounded Theory | Sedano, T., Ralph, P., & Péraire, C. (2017). Software development waste. *ICSE 2017*, 130-140. |

Para avaliar os artigos reais, use o checklist do padrão correspondente no site dos Empirical Standards: *Case Study and Ethnography*, *Action Research*, *Qualitative Survey* e *Grounded Theory*.

## `aula-01/IA/`

Material do bloco sobre inteligência artificial na pesquisa qualitativa (sexta do M1).

| Arquivo | Conteúdo |
| --- | --- |
| `Demonstração ao vivo: um LLM lê uma fala de entrevista.docx` | Roteiro da demonstração: fala fictícia com armadilhas deliberadas, pedidos em duas rodadas, sequência de 20 minutos, preparação técnica e guia para a crítica |

## Como usar em sala (sábado da aula 1)

1. **Antes do FDS1:** cada grupo lê o artigo real do seu desenho, com a ficha de anotação.
2. **9h00:** cada grupo lê o artigo fake do mesmo desenho e responde às perguntas de reflexão.
3. **10h15:** o grupo compara o fake com o real, usando o checklist SIGSOFT do desenho.
4. **11h15:** cada grupo ensina seu desenho à turma, e a turma monta o quadro comparativo.
5. **Entre FDS1 e FDS2:** cada aluno lê os quatro artigos fake dos outros grupos.

## Uso e direitos

Os artigos fictícios e o roteiro da demonstração são material original da disciplina. Os arquivos em `definicao/` e `artigos reais/` de cada aula são publicações de terceiros, incluídas apenas para uso interno da turma. Se este repositório for público, substitua esses PDFs por links para as versões oficiais ou de acesso aberto.

Os gabaritos dos artigos fictícios são de uso exclusivo do professor e não fazem parte deste repositório.
