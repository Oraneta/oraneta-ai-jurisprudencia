
<div align="center">

<h1>ORANETA AI | JURISPRUDENCIA SCJN</h1>

<h2>Inteligencia artificial aplicada a la investigación jurídica en México</h2>

<p><strong>Solución desarrollada por Oraneta AI para Inteligencia Jurídica.</strong></p>

<p>Consulta tesis aisladas y jurisprudencia de la Suprema Corte de Justicia de la Nación mediante inteligencia artificial y lenguaje natural.</p>

<img src="https://img.shields.io/badge/Inteligencia-Artificial-168BFF?style=for-the-badge" alt="Inteligencia Artificial">
<img src="https://img.shields.io/badge/LegalTech-643BFF?style=for-the-badge" alt="LegalTech">
<img src="https://img.shields.io/badge/Actualización-Semanal-C329F4?style=for-the-badge" alt="Actualización semanal">

<br><br>

<a href="https://inteligenciajuridica.mx/jurisprudencia/">
<img src="https://img.shields.io/badge/PROBAR_APLICACIÓN_GRATIS-168BFF?style=for-the-badge" alt="Probar aplicación">
</a>

</div>

---

## Acerca del proyecto

**Oraneta AI | Jurisprudencia SCJN** es una solución tecnológica desarrollada por **Oraneta** para **Inteligencia Jurídica**, orientada a facilitar la investigación y consulta de criterios judiciales mexicanos.

La plataforma integra procesos de extracción de información oficial, actualización de bases de datos, búsqueda semántica e inteligencia artificial generativa.

Su objetivo es transformar una colección de información jurídica estructurada en una herramienta de consulta accesible mediante preguntas formuladas en español.

La aplicación está disponible gratuitamente en:

**https://inteligenciajuridica.mx/jurisprudencia/**

---

## El desafío

La investigación jurisprudencial requiere localizar, consultar e interpretar información publicada por los órganos jurisdiccionales mexicanos.

Entre los principales desafíos se encuentran:

- Identificar tesis y jurisprudencia relevantes para una cuestión jurídica.
- Localizar criterios sin conocer necesariamente su registro digital o número de identificación.
- Consultar información distribuida entre numerosos registros.
- Mantener actualizada una base de conocimiento jurídico.
- Relacionar distintos criterios judiciales para responder preguntas complejas.

---

## La solución

Oraneta desarrolló una arquitectura que combina ingeniería de datos, automatización e inteligencia artificial.

### 1. Extracción de información jurídica

Un proceso desarrollado en Python consulta la API del repositorio de tesis de la SCJN.

El sistema identifica los registros disponibles, los compara con la base de datos existente y recupera la información de las tesis que todavía no han sido incorporadas.

### 2. Actualización de la base de conocimiento

La solución contempla un proceso de actualización semanal para incorporar nuevas publicaciones.

Los registros se normalizan, se validan y se integran a PostgreSQL, preservando la información existente y evitando duplicados mediante identificadores únicos.

### 3. Indexación semántica

Los documentos jurídicos se transforman en representaciones vectoriales mediante modelos de embeddings de OpenAI.

Estas representaciones se almacenan utilizando PostgreSQL y pgvector, permitiendo recuperar información por similitud semántica.

### 4. Motor inteligente de consultas

La aplicación utiliza una arquitectura de inteligencia artificial de dos etapas:

**Planificación de búsqueda:** un modelo interpreta la pregunta del usuario y determina qué búsquedas realizar.

**Generación de respuestas:** un segundo modelo analiza los registros recuperados y elabora una respuesta fundamentada en su contenido.

### 5. Consulta conversacional

El usuario puede formular preguntas en lenguaje natural y realizar consultas de seguimiento.

La plataforma conserva temporalmente el contexto de la conversación para facilitar la continuidad de la investigación.

---

## Funcionalidades principales

### Búsqueda semántica

Permite encontrar criterios jurídicos relacionados con una pregunta, incluso cuando no se utilizan exactamente las mismas palabras que aparecen en los documentos.

### Búsqueda estructurada

Permite localizar información mediante campos como:

- Registro digital.
- Número de tesis.
- Rubro.
- Época.
- Materia.
- Instancia y órgano jurisdiccional.
- Año y mes.

### Búsqueda híbrida

Combina filtros estructurados con recuperación semántica para identificar registros relevantes.

### Respuestas fundamentadas

El asistente está diseñado para responder utilizando los registros jurídicos recuperados, identificar las tesis relevantes y distinguir entre jurisprudencia y tesis aisladas.

### Actualización incremental

Los procesos de incorporación identifican registros nuevos y evitan reemplazar o duplicar información previamente almacenada.

---

---

## Tecnologías utilizadas

| Tecnología | Aplicación |
|---|---|
| Python | Extracción, procesamiento y actualización de información |
| Playwright | Acceso automatizado al repositorio de la SCJN |
| PostgreSQL | Almacenamiento estructurado de información jurídica |
| pgvector | Indexación y recuperación vectorial |
| OpenAI API | Embeddings, planificación de búsquedas y generación de respuestas |
| Flask | Servicio backend de consultas |
| Redis | Gestión temporal del historial conversacional |
| Microsoft Azure | Infraestructura de base de datos PostgreSQL |
| API SCJN | Fuente oficial de información jurídica |

---

## Prueba la aplicación

La plataforma se encuentra disponible públicamente y puede utilizarse sin acceder al código fuente ni instalar dependencias.

<div align="center">

<a href="https://inteligenciajuridica.mx/jurisprudencia/">
<img src="https://img.shields.io/badge/ABRIR_DEMOSTRACIÓN_GRATUITA-168BFF?style=for-the-badge" alt="Abrir demostración gratuita">
</a>

</div>

### Ejemplos de consultas

**Consulta conceptual**

> ¿Qué criterios jurisprudenciales existen sobre el interés superior de la niñez?

**Consulta temática**

> Busca tesis relacionadas con la responsabilidad patrimonial del Estado.

**Consulta laboral**

> ¿Qué jurisprudencia existe sobre el despido injustificado?

**Consulta de seguimiento**

> ¿Cuáles son los criterios más relevantes de los resultados anteriores?

Las respuestas dependen de los registros disponibles en la base de conocimiento.

---

## Aplicación desarrollada para Inteligencia Jurídica

**Inteligencia Jurídica** es una plataforma mexicana especializada en información y conocimiento legal.

La implementación de Oraneta AI permite ofrecer una experiencia de consulta jurídica basada en inteligencia artificial, utilizando información proveniente del repositorio oficial de la SCJN.

**Plataforma:** [Inteligencia Jurídica](https://inteligenciajuridica.mx)

**Aplicación:** [Consulta de Jurisprudencia](https://inteligenciajuridica.mx/jurisprudencia/)

---

## Sobre Oraneta

**Oraneta** desarrolla soluciones empresariales de inteligencia artificial, automatización y asistentes digitales especializados.

Este proyecto demuestra la aplicación de tecnologías de IA generativa, recuperación aumentada de información (RAG), bases de datos vectoriales e integración de sistemas para resolver necesidades concretas del sector jurídico.

---

## Documentación y propiedad intelectual

Este repositorio tiene fines exclusivamente informativos y de portafolio profesional.

El código fuente, los componentes internos, las credenciales, la infraestructura y los procesos operativos de la aplicación son propietarios y no se distribuyen públicamente.

La documentación describe las capacidades y la arquitectura general de una solución desarrollada e implementada por Oraneta.

La información jurídica consultada por la plataforma proviene de fuentes oficiales. Oraneta e Inteligencia Jurídica no representan ni forman parte de la Suprema Corte de Justicia de la Nación.

---

<div align="center">

<h2>Conoce Oraneta e Inteligencia Jurídica</h2>

<a href="https://oraneta.com">
<img src="https://img.shields.io/badge/Oraneta-168BFF?style=for-the-badge" alt="Oraneta">
</a>

<a href="https://inteligenciajuridica.mx">
<img src="https://img.shields.io/badge/Inteligencia_Jurídica-643BFF?style=for-the-badge" alt="Inteligencia Jurídica">
</a>

<a href="https://www.linkedin.com/company/oraneta/">
<img src="https://img.shields.io/badge/LinkedIn-C329F4?style=for-the-badge" alt="LinkedIn">
</a>

<p><strong>Oraneta AI — Inteligencia artificial aplicada a soluciones reales.</strong></p>

</div>
