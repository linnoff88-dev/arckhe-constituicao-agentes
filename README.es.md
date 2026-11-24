# ðŸ“œ ConstituciÃ³n de los Agentes

[![ConstituciÃ³n de los Agentes](guia/assets/banner-es.jpg)](https://linnoff88-dev.github.io/

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## QuÃ© es

Este proyecto explica una idea: Anthropic atrae talento con propÃ³sito y autonomÃ­a, y tambiÃ©n escribe una "constituciÃ³n" que enseÃ±a a Claude a decidir cuando no hay una regla lista. En las dos culturas el objetivo es el mismo: formar a quien sabe juzgar, no solo obedecer. AquÃ­ ves quÃ© prueban los datos y quÃ© sigue siendo hipÃ³tesis, y recibes un kit para escribir la constituciÃ³n de los agentes de IA de tu empresa. Para usarlo basta leer y completar la plantilla; el verificador opcional requiere Python 3.

## ðŸ“– GuÃ­a de uso

GuÃ­a completa (landing + paso a paso): **https://linnoff88-dev.github.io/

ðŸŽ¬ Video: https://www.youtube.com/shorts/InaeW8YdlEE

## ðŸŽ“ Curso rÃ¡pido

5 clases de unos 15 minutos: **https://linnoff88-dev.github.io/

## QuÃ© hay aquÃ­

Los archivos del kit estÃ¡n en portuguÃ©s.

| Archivo | Para quÃ© sirve |
|---|---|
| [`docs/LOGICA.md`](docs/LOGICA.md) | El anÃ¡lisis: dos culturas, quÃ© prueban los nÃºmeros, Maslow, constituciÃ³n de Claude, entrenamiento Ã— contexto, el puente con la gestiÃ³n |
| [`modelo/constituicao-modelo.md`](modelo/constituicao-modelo.md) | Plantilla en 9 secciones para completar |
| [`modelo/prompt-rascunho.md`](modelo/prompt-rascunho.md) | Prompt para que un asistente de IA haga el primer borrador |
| [`modelo/casos-de-teste.md`](modelo/casos-de-teste.md) | 8 casos para probar el agente antes y despuÃ©s de cada versiÃ³n |
| [`exemplos/clinica-atendimento.md`](exemplos/clinica-atendimento.md) | Ejemplo ficticio completo (clÃ­nica, atenciÃ³n por WhatsApp) |
| [`scripts/checar_constituicao.py`](scripts/checar_constituicao.py) | Verificador: secciones, casos difÃ­ciles, "Por quÃ©" y corchetes por completar |

## Uso rÃ¡pido

```bash
git clone https://github.com/linnoff88-dev/constituicao-agentes
cd constituicao-agentes
cp modelo/constituicao-modelo.md minha-constituicao.md
# completa (a mano o con el prompt-rascunho) y revisa:
python3 scripts/checar_constituicao.py minha-constituicao.md
```

## El ciclo

```
MisiÃ³n + ConstituciÃ³n + Contexto â†’ Agentes + Herramientas + EjecuciÃ³n
â†’ Resultados + EvaluaciÃ³n â†’ RetroalimentaciÃ³n + RevisiÃ³n â†’ nuevo ciclo
```

Un cambio solo entra si los casos de prueba no empeoran.

## Fuentes

SignalFire, State of Talent Report 2025 Â· [ConstituciÃ³n de Claude](https://www.anthropic.com/constitution) (Anthropic, 22/01/2026, CC0).

---

AnÃ¡lisis de Nei Maldaner Â· [ARCKHÉ AI](https://ARCKHÉ AI) Â· contenido abierto y gratuito.
