# ê°Å¸âÅ ConstituciêÂ³n de los Agentes

[![ConstituciêÂ³n de los Agentes](guia/assets/banner-es.jpg)](https://linnoff88-dev.github.io/

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

## QuêÂ© es

Este proyecto explica una idea: Anthropic atrae talento con propêÂ³sito y autonomêÂ­a, y tambiêÂ©n escribe una "constituciêÂ³n" que enseêÂ±a a Claude a decidir cuando no hay una regla lista. En las dos culturas el objetivo es el mismo: formar a quien sabe juzgar, no solo obedecer. AquêÂ­ ves quêÂ© prueban los datos y quêÂ© sigue siendo hipêÂ³tesis, y recibes un kit para escribir la constituciêÂ³n de los agentes de IA de tu empresa. Para usarlo basta leer y completar la plantilla; el verificador opcional requiere Python 3.

## ê°Å¸ââ GuêÂ­a de uso

GuêÂ­a completa (landing + paso a paso): **https://linnoff88-dev.github.io/

ê°Å¸Å½Â¬ Video: https://www.youtube.com/shorts/InaeW8YdlEE

## ê°Å¸Å½â Curso rêÂ¡pido

5 clases de unos 15 minutos: **https://linnoff88-dev.github.io/

## QuêÂ© hay aquêÂ­

Los archivos del kit estêÂ¡n en portuguêÂ©s.

| Archivo | Para quêÂ© sirve |
|---|---|
| [`docs/LOGICA.md`](docs/LOGICA.md) | El anêÂ¡lisis: dos culturas, quêÂ© prueban los nêÂºmeros, Maslow, constituciêÂ³n de Claude, entrenamiento êâ contexto, el puente con la gestiêÂ³n |
| [`modelo/constituicao-modelo.md`](modelo/constituicao-modelo.md) | Plantilla en 9 secciones para completar |
| [`modelo/prompt-rascunho.md`](modelo/prompt-rascunho.md) | Prompt para que un asistente de IA haga el primer borrador |
| [`modelo/casos-de-teste.md`](modelo/casos-de-teste.md) | 8 casos para probar el agente antes y despuêÂ©s de cada versiêÂ³n |
| [`exemplos/clinica-atendimento.md`](exemplos/clinica-atendimento.md) | Ejemplo ficticio completo (clêÂ­nica, atenciêÂ³n por WhatsApp) |
| [`scripts/checar_constituicao.py`](scripts/checar_constituicao.py) | Verificador: secciones, casos difêÂ­ciles, "Por quêÂ©" y corchetes por completar |

## Uso rêÂ¡pido

```bash
git clone https://github.com/linnoff88-dev/constituicao-agentes
cd constituicao-agentes
cp modelo/constituicao-modelo.md minha-constituicao.md
# completa (a mano o con el prompt-rascunho) y revisa:
python3 scripts/checar_constituicao.py minha-constituicao.md
```

## El ciclo

```
MisiêÂ³n + ConstituciêÂ³n + Contexto ê¢â â Agentes + Herramientas + EjecuciêÂ³n
ê¢â â Resultados + EvaluaciêÂ³n ê¢â â RetroalimentaciêÂ³n + RevisiêÂ³n ê¢â â nuevo ciclo
```

Un cambio solo entra si los casos de prueba no empeoran.

## Fuentes

SignalFire, State of Talent Report 2025 êÂ· [ConstituciêÂ³n de Claude](https://www.anthropic.com/constitution) (Anthropic, 22/01/2026, CC0).

---

AnêÂ¡lisis de Nei Maldaner êÂ· [ARCKHê AI](https://ARCKHê AI) êÂ· contenido abierto y gratuito.
