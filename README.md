# ê°Å¸âÅ ConstituiêÂ§êÂ£o dos Agentes

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![ConstituiêÂ§êÂ£o dos Agentes](guia/assets/banner.jpg)](https://linnoff88-dev.github.io/

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

## O que êÂ©

Este projeto explica uma ideia: a Anthropic atrai talentos com propêÂ³sito e autonomia, e tambêÂ©m escreve uma "constituiêÂ§êÂ£o" que ensina o Claude a decidir quando nêÂ£o hêÂ¡ regra pronta. Nas duas culturas, o objetivo êÂ© o mesmo: formar quem sabe julgar, nêÂ£o sêÂ³ obedecer. Aqui vocêÂª vêÂª o que os dados provam e o que ainda êÂ© hipêÂ³tese, e recebe um kit para escrever a constituiêÂ§êÂ£o dos agentes de IA da sua empresa. Para usar, basta ler e preencher o modelo; o verificador opcional pede Python 3.

## ê°Å¸ââ Guia de uso

Guia completo (landing + passo a passo): **https://linnoff88-dev.github.io/

ê°Å¸Å½Â¬ VêÂ­deo: https://www.youtube.com/shorts/InaeW8YdlEE

## ê°Å¸Å½â Curso rêÂ¡pido

5 aulas de uns 15 minutos (formato v6.2): **https://linnoff88-dev.github.io/

## O que tem aqui

| Arquivo | Para quêÂª |
|---|---|
| [`docs/LOGICA.md`](docs/LOGICA.md) | A anêÂ¡lise: duas culturas, o que os nêÂºmeros provam, Maslow, constituiêÂ§êÂ£o do Claude, treino êâ contexto, a ponte com a gestêÂ£o |
| [`modelo/constituicao-modelo.md`](modelo/constituicao-modelo.md) | Modelo em 9 seêÂ§êÂµes para preencher |
| [`modelo/prompt-rascunho.md`](modelo/prompt-rascunho.md) | Prompt para um assistente de IA fazer o primeiro rascunho |
| [`modelo/casos-de-teste.md`](modelo/casos-de-teste.md) | 8 casos para testar o agente antes e depois de cada versêÂ£o |
| [`exemplos/clinica-atendimento.md`](exemplos/clinica-atendimento.md) | Exemplo fictêÂ­cio preenchido (clêÂ­nica, atendimento no WhatsApp) |
| [`scripts/checar_constituicao.py`](scripts/checar_constituicao.py) | Verificador: seêÂ§êÂµes, casos difêÂ­ceis, "Por quêÂª" e colchetes por preencher |

## Uso rêÂ¡pido

```bash
git clone https://github.com/linnoff88-dev/constituicao-agentes
cd constituicao-agentes
cp modelo/constituicao-modelo.md minha-constituicao.md
# preencha (êÂ  mêÂ£o ou com o prompt-rascunho) e confira:
python3 scripts/checar_constituicao.py minha-constituicao.md
```

## O ciclo

```
MissêÂ£o + ConstituiêÂ§êÂ£o + Contexto ê¢â â Agentes + Ferramentas + ExecuêÂ§êÂ£o
ê¢â â Resultados + AvaliaêÂ§êÂ£o ê¢â â Feedback + RevisêÂ£o ê¢â â novo ciclo
```

Uma mudanêÂ§a sêÂ³ entra se os casos de teste nêÂ£o pioram.

## Fontes

SignalFire, State of Talent Report 2025 êÂ· [ConstituiêÂ§êÂ£o do Claude](https://www.anthropic.com/constitution) (Anthropic, 22/01/2026, CC0).

---

AnêÂ¡lise de Nei Maldaner êÂ· [ARCKHê AI](https://ARCKHê AI) êÂ· conteêÂºdo aberto e gratuito.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>