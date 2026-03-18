# Relatório Operacional de Pré-Decolagem de uma Nave Fictícia

Projeto acadêmico desenvolvido para a Atividade Integradora da Fase 1 de Ciência da Computação. O trabalho foi organizado em um notebook com foco em telemetria, verificação algorítmica de pré-decolagem, implementação em Python, análise energética e análise assistida por IA em um cenário fictício.

## Objetivo

Simular a avaliação operacional de uma nave fictícia antes da decolagem, utilizando dados de telemetria e regras de decisão para determinar se a missão está:

- `PRONTO PARA DECOLAR`
- `DECOLAGEM ABORTADA`

## Estrutura do repositório

```text
.
├── README.md
├── notebooks/
│   └── relatorio_pre_decolagem_nave.ipynb
├── docs/
│   └── relatorio_pre_decolagem_nave.pdf
└── assets/
    └── imagens_utilizadas/
```

## Conteúdo do notebook

O notebook está organizado nas seguintes seções:

1. Introdução
2. Organização e descrição da telemetria
3. Algoritmo de verificação (pseudocódigo)
4. Implementação em Python
5. Análise energética
6. Análise assistida por IA
7. Reflexão crítica
8. Conclusão

## Dados de telemetria monitorados

Os sensores da nave fornecem os seguintes dados antes da decolagem:

| Variável | Descrição |
|---|---|
| `temperatura_interna_c` | Temperatura interna da cabine (°C) |
| `temperatura_externa_c` | Temperatura externa da nave (°C) |
| `integridade_estrutural` | Integridade do casco (1 = íntegro / 0 = comprometido) |
| `nivel_energia_percentual` | Nível de carga do sistema de energia (%) |
| `pressao_tanque_kpa` | Pressão dos tanques de propelente (kPa) |
| `modulo_propulsao_ok` | Status do módulo de propulsão |
| `modulo_navegacao_ok` | Status do módulo de navegação |
| `modulo_suporte_vida_ok` | Status do módulo de suporte à vida |

## Como executar

1. Clone o repositório ou faça o download do arquivo `.ipynb`.
2. Abra o arquivo `notebooks/relatorio_pre_decolagem_nave.ipynb` no [Google Colab](https://colab.research.google.com) ou no Jupyter Notebook local.
3. Execute as células em ordem sequencial (de cima para baixo).
4. Observe os resultados da verificação operacional e da análise energética.

## Observação metodológica

Este projeto utiliza uma simulação fictícia com finalidade didática. Os limites e valores adotados foram definidos como premissas de simulação e não representam parâmetros reais de engenharia aeroespacial.

## Tecnologias utilizadas

- Python 3
- Jupyter Notebook / Google Colab
- Markdown
