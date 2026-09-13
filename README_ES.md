<div align="center">

# Valheim: compatibilidad y atajos de trainers

Organiza versiones del juego, trainers y teclas asignadas. Es una referencia independiente, no una descarga oficial de FLiNG ni un trainer verificado.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="54" alt="Descargar — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Valheim: compatibilidad y atajos de trainers — Vista de la aplicación">
</p>

## Por qué existe esta herramienta

Organiza versiones del juego, trainers y teclas asignadas. Es una referencia independiente, no una descarga oficial de FLiNG ni un trainer verificado.

El repositorio contiene documentación y un concepto de interfaz, no un lanzamiento funcional verificado. Las notas y las imágenes no son pruebas de ejecución ni demuestran autoría oficial, compatibilidad o protección de cuenta.

## Antes de empezar

- Prepara **Construcción de juego + construcción de entrenador** y confirma que corresponde al perfil o sesión de Valheim que quieres usar.
- Anota la build actual del juego/cliente o la fecha de los datos antes de cambiar un perfil.
- Decide dónde guardar **Registro de diagnóstico** para no sobrescribir el resultado anterior.
- Prueba primero **Matriz de versión de entrenador y juego** en una sesión corta y conserva al lado la partida, el perfil o la comparación original.

## Qué hace

### 01 · Matriz de versión de entrenador y juego

Hace coincidir la versión del entrenador con el ejecutable detectado y la compilación del juego.

### 02 · índice de opciones y teclas de acceso rápido

Enumera grupos de opciones, estados actuales y teclas de acceso rápido sin ocultar conflictos.

### 03 · guardar recordatorios de copia de seguridad

Registra errores de opciones y archivos adjuntos con suficiente contexto para reproducirlos.

## Recorrido por la interfaz

- **01.** Matriz de compatibilidad de versiones de juego y entrenador.
- **02.** Tarjeta de detección de procesos con estado ejecutable y privilegios.
- **03.** Índice de opciones agrupadas por función.
- **04.** Lista de teclas de acceso rápido con advertencias de conflictos.
- **05.** Registro de diagnóstico y recordatorio de copia de seguridad antes de realizar la prueba.

## Primera sesión completa

1. Abre **Valheim: compatibilidad y atajos de trainers** y comprueba la build o la fuente de datos de Valheim.
2. Elige la entrada o el perfil y configura **Matriz de versión de entrenador y juego** sin tocar los valores que no formen parte de la prueba.
3. Revisa **índice de opciones y teclas de acceso rápido** en la vista previa o el panel de estado y corrige cualquier aviso de versión, filtro o detección.
4. Ejecuta una sola acción controlada. Compara el resultado visible con la vista previa antes de cambiar otro ajuste.
5. Guarda el perfil o exporta el resultado; conserva **guardar recordatorios de copia de seguridad** para comparar o recuperar.

## De un vistazo

| Función | Resultado |
|---|---|
| **Entrada** | Construcción de juego + construcción de entrenador |
| **Resultado** | Matriz de compatibilidad y teclas de acceso rápido |
| **Salida** | Registro de diagnóstico |

## Cómo interpretar el resultado

La compatibilidad viene antes que el recuento de opciones. Un proceso detectado con una compilación que no coincide no es un archivo adjunto exitoso. Habilite una opción, obsérvela a través de un cambio de escena y registre el resultado; esa secuencia separa los conflictos de teclas de acceso rápido, los valores temporales y los punteros no admitidos.

## Pensado para

- Versiones de juego y entrenador de partidos.
- Buscar teclas de acceso rápido de opciones
- Diagnosticar la detección de procesos

## Después de actualizar el juego

- [ ] Compare el ejecutable del juego y la versión del entrenador antes de la detección del proceso.
- [ ] Resuelva los cambios de privilegios y nombres de archivos ejecutables antes de probar las teclas de acceso rápido.
- [ ] Habilite una opción reversible y obsérvela durante la recarga de una escena.
- [ ] Guarde el registro de diagnóstico anterior y guarde una copia de seguridad hasta que se confirme el nuevo emparejamiento.

## Solución de problemas

> **Problema habitual:** el entrenador no puede encontrar el proceso de Valheim.

### El proceso no se encuentra.

Verifique el nombre del ejecutable, el nivel de privilegio y si el juego ha alcanzado el estado compatible.

### Las teclas de acceso rápido no hacen nada

Resuelva enlaces duplicados y confirme que la versión del entrenador seleccionada coincida con el juego.

### Una opción se apaga entre escenas.

Lea la nota de persistencia y pruébela por separado de las opciones que reescribe el juego.

## Datos y recuperación

Haga una copia de seguridad de los archivos guardados antes de realizar la prueba y habilite una opción a la vez. Los detalles de compilación, proceso y teclas de acceso rápido deben permanecer en el registro de diagnóstico para una reversión limpia.

<sub>Usa automatizaciones y modificaciones solo cuando las reglas del juego y el tipo de sesión lo permitan.</sub>

## Preguntas frecuentes

<details>
<summary><strong>¿Qué debe incluir un informe de compatibilidad?</strong></summary>

Anota la versión exacta del juego y de la herramienta o datos, la entrada usada y el resultado observado. Conserva lo desconocido como tal; otra versión no demuestra compatibilidad actual.
</details>

<details>
<summary><strong>¿Se incluye un ejecutable o script funcional?</strong></summary>

El repositorio contiene documentación y un concepto de interfaz, no un lanzamiento funcional verificado. Las notas y las imágenes no son pruebas de ejecución ni demuestran autoría oficial, compatibilidad o protección de cuenta.
</details>

---

<div align="center">

## Descargar

Revisa el alcance y la compatibilidad documentados antes de elegir una versión.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="50" alt="Descargar — Windows"></a>

</div>

---

Concepto de interfaz generado con IA; no se ha verificado una versión funcional.

