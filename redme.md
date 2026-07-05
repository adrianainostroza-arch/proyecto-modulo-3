# SmartBudget - Justificación Técnica y Metodológica

## 1. Organización del Código CSS: Metodología BEM
Para este desarrollo se seleccionó la metodología **BEM (Block, Element, Modifier)**. 
* **Justificación:** Su uso reduce drásticamente los problemas de especificidad en CSS al mantener clases planas y descriptivas (ej: .hero__title). Esto facilita el desacoplamiento de los estilos y permite identificar con precisión a qué componente visual pertenece cada regla desde el propio archivo HTML[cite: 1].

## 2. Preprocesador y Modularización: Patrón SASS 7-1
Se estructuró el proyecto utilizando el preprocesador **SASS** bajo una arquitectura simplificada del **Patrón 7-1**[cite: 1].
* **Justificación:** Al separar el código en carpetas independientes (`/abstracts`, `/layout`, `/components`), se evita tener un único archivo CSS masivo e ilegible[cite: 1]. El uso de variables para los colores institucionales y mixins para las media queries garantiza consistencia visual y facilita cambios globales en segundos[cite: 1].

## 3. Layout, Modelo de Cajas y Bootstrap 4
* **Diseño Responsivo:** Se integró **Bootstrap 4** mediante su sistema de rejilla flexbox (`.row`, `.col-md-4`) para resolver la distribución del contenido de forma fluida y nativa[cite: 1].
* **Modelo de Cajas:** Se respetaron las clases utilitarias de espaciado de Bootstrap (`py-5`, `mb-4`) para mantener márgenes y rellenos equilibrados en dispositivos móviles y de escritorio, optimizando la integridad visual sin sobreescrituras críticas de código[cite: 1].