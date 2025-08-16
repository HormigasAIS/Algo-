## 🌱 El corazón `.humano` 

Este repositorio incluye un archivo **.humano**, que funciona como **manifiesto narrativo-técnico** dentro del ecosistema **HormigasAIS**. 

El `.humano` define:
- La **filosofía** y el **tono** del proyecto.
- Las **integraciones** que utiliza.
- La **forma** en que el flujo de trabajo se ejecuta (ritmo, pausas, estilo).
- Metadatos que permiten a herramientas automáticas interpretar y adaptar su comportamiento. 

### Ejemplo del `.humano`
```yaml
meta:
  version: 1.0
  author: Cristhiam Quiñonez
  identity: HormigasAIS
  motto: "Cada línea de código es una raíz; cada idea, una semilla." 

flow:
  pacing: "orgánico"
  pauses: true
  automation_sense: true 

integrations:
  - n8n
  - GitHub Actions
  - Slack
  - Discord 

narrative:
  role: "guía simbólico-técnico"
  tone: "curioso y colaborativo"
