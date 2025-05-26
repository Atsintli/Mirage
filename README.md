# Mirage: Modelo de Lenguaje para Composición Musical Asistida por IA

## Descripción

Mirage es un proyecto que tiene por objetivo modelar un sistema capaz de replicar diferentes estilos musicales de diversas épocas utilizando grandes modelos de lenguaje (LLM), redes LSTM (Long Short Term Memory), técnicas de aprendizaje por transferencia (transfer learning) y redes neuronales basadas en atención. El sistema genera composiciones completas en archivos ABC que posteriormente pueden orquestarse o instrumentarse con instrumentos virtuales.

La iniciativa abarca el estudio de hitos significativos en la historia de la música para lograr una comprensión sólida de los desarrollos musicales más complejos del siglo XX y la época actual.

### Períodos Musicales Contemplados

**Ars Nova**: La cuna de la polifonía, donde el motete y el organum se desarrollaron mediante la adición de una o más voces a una melodía gregoriana preexistente, empleando los pies rítmicos de la escuela de Notre Dame.

**Barroco y Clásico**: Períodos que vieron el auge de la polifonía y las modulaciones facilitadas por el temperamento igual de instrumentos de teclado como el clavecín y el piano. Se desarrollaron formas musicales sofisticadas como el preludio, la fuga y la fantasía en el barroco, así como la sonata y la sinfonía en el clasicismo.

**Jazz**: Desde el jazz temprano con raíces en el blues hasta el jazz contemporáneo con múltiples vertientes. Se caracteriza por la improvisación musical dentro de estructuras armónicas y melódicas, evolucionando hacia subgéneros como Bebop, Hardbop y Jazz experimental.

## Metodología

El proyecto abstrae y analiza las reglas técnicas de cada época para definir el estilo y la forma musical mediante programación experta. Se emplean recursos de LLM, LSTM, aprendizaje por transferencia y redes neuronales basadas en atención a través de modelos previamente entrenados y de código abierto como Rave y Magenta Music Transformer.

El análisis abarca fundamentos musicales como altura, duración, dinámica, movimientos melódicos, cambios de tempo, patrones rítmicos, armonía, enfoques de modulación, desarrollo temático, formas y expresión emocional.

## Antecedentes

El proyecto se basa en experiencias previas de recreación del estilo compositivo de J.S. Bach, específicamente las Variaciones Goldberg, mediante extracción de datos MIDI y análisis con redes LSTM. Este enfoque previo permitió comprender conceptos fundamentales del aprendizaje automático aplicado a series temporales musicales.

La propuesta actual integra código, análisis de bases de datos y conformación de instrucciones con descripciones musicales textuales. En el paradigma de los grandes modelos de lenguaje, el aprendizaje por transferencia permite especializar modelos previamente entrenados en aspectos específicos de la composición musical.

## Objetivos

- Analizar y abstraer los estilos musicales del Ars Antiqua, Barroco, Clásico y Jazz
- Compilar y estructurar una base de datos con datos MIDI representativos de diferentes estilos
- Aplicar técnicas de LSTM, LLM, aprendizaje por transferencia y redes neuronales basadas en atención para modelar estilos musicales
- Desarrollar un modelo capaz de componer música integrando varios estilos musicales
- Ajustar prompts y semillas iniciales del sistema para obtener resultados musicales específicos
- Generar 10 composiciones musicales en formato WAV, incorporando técnicas de orquestación e instrumentación MIDI

## Licencia

Mirage será liberado como software libre bajo licencias Creative Commons para promover la colaboración y el libre acceso, invitando a la comunidad a contribuir al proyecto.
