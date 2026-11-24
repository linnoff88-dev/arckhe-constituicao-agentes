# ðŸ“œ ConstituiÃ§Ã£o dos Agentes

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![ConstituiÃ§Ã£o dos Agentes](guia/assets/banner.jpg)](https://linnoff88-dev.github.io/

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

Este projeto explica uma ideia: a Anthropic atrai talentos com propÃ³sito e autonomia, e tambÃ©m escreve uma "constituiÃ§Ã£o" que ensina o Claude a decidir quando nÃ£o hÃ¡ regra pronta. Nas duas culturas, o objetivo Ã© o mesmo: formar quem sabe julgar, nÃ£o sÃ³ obedecer. Aqui vocÃª vÃª o que os dados provam e o que ainda Ã© hipÃ³tese, e recebe um kit para escrever a constituiÃ§Ã£o dos agentes de IA da sua empresa. Para usar, basta ler e preencher o modelo; o verificador opcional pede Python 3.

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo): **https://linnoff88-dev.github.io/

ðŸŽ¬ VÃ­deo: https://www.youtube.com/shorts/InaeW8YdlEE

## ðŸŽ“ Curso rÃ¡pido

5 aulas de uns 15 minutos (formato v6.2): **https://linnoff88-dev.github.io/

## O que tem aqui

| Arquivo | Para quÃª |
|---|---|
| [`docs/LOGICA.md`](docs/LOGICA.md) | A anÃ¡lise: duas culturas, o que os nÃºmeros provam, Maslow, constituiÃ§Ã£o do Claude, treino Ã— contexto, a ponte com a gestÃ£o |
| [`modelo/constituicao-modelo.md`](modelo/constituicao-modelo.md) | Modelo em 9 seÃ§Ãµes para preencher |
| [`modelo/prompt-rascunho.md`](modelo/prompt-rascunho.md) | Prompt para um assistente de IA fazer o primeiro rascunho |
| [`modelo/casos-de-teste.md`](modelo/casos-de-teste.md) | 8 casos para testar o agente antes e depois de cada versÃ£o |
| [`exemplos/clinica-atendimento.md`](exemplos/clinica-atendimento.md) | Exemplo fictÃ­cio preenchido (clÃ­nica, atendimento no WhatsApp) |
| [`scripts/checar_constituicao.py`](scripts/checar_constituicao.py) | Verificador: seÃ§Ãµes, casos difÃ­ceis, "Por quÃª" e colchetes por preencher |

## Uso rÃ¡pido

```bash
git clone https://github.com/linnoff88-dev/constituicao-agentes
cd constituicao-agentes
cp modelo/constituicao-modelo.md minha-constituicao.md
# preencha (Ã  mÃ£o ou com o prompt-rascunho) e confira:
python3 scripts/checar_constituicao.py minha-constituicao.md
```

## O ciclo

```
MissÃ£o + ConstituiÃ§Ã£o + Contexto â†’ Agentes + Ferramentas + ExecuÃ§Ã£o
â†’ Resultados + AvaliaÃ§Ã£o â†’ Feedback + RevisÃ£o â†’ novo ciclo
```

Uma mudanÃ§a sÃ³ entra se os casos de teste nÃ£o pioram.

## Fontes

SignalFire, State of Talent Report 2025 Â· [ConstituiÃ§Ã£o do Claude](https://www.anthropic.com/constitution) (Anthropic, 22/01/2026, CC0).

---

AnÃ¡lise de Nei Maldaner Â· [ARCKHÉ AI](https://ARCKHÉ AI) Â· conteÃºdo aberto e gratuito.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>