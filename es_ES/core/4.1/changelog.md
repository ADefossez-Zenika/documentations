# Registro de cambios Jeedom V4.1

## 4.1.0

- **Síntesis** : Agregar una nueva página **Inicio → Resumen** ofreciendo una síntesis visual global de las partes.
- **Buscar** : Adición de un motor de búsqueda en **Herramientas → Buscar**.
- **Salpicadero** : El modo de edición ahora inserta el mosaico movido.
- **Salpicadero** : Modo de edición: Los iconos de actualización del equipo se reemplazan por un icono que permite acceder a su configuración, gracias a un nuevo modal simplificado.
- **Salpicadero** : Ahora podemos hacer clic en el *tiempo* widgets de acciones de tiempo para abrir la ventana del historial del comando de información vinculada.
- **Salpicadero** : El tamaño del mosaico de un equipo nuevo se adapta a su contenido.
- **Salpicadero** : Agregar (¡atrás!) Un botón para filtrar los elementos mostrados por categoría.
- **Salpicadero** : Ctrl Click en una información abre la ventana de historial con todos los comandos historizados del equipo visibles en el mosaico. Ctrl Haga clic en una leyenda para mostrar solo esta, Alt Haga clic para mostrarlas todas.
- **Salpicadero** : Posibilidad de desenfocar imágenes de fondo (Configuración -> Interfaz).
- **Herramientas / widgets** : La funcion *Aplicar en* muestra los comandos vinculados marcados, al desmarcar uno se aplicará el widget principal predeterminado a este comando.
- **Reproductores** : Agregar un widget principal *deslizador vertical*.
- **Centro de actualizaciones** : Las actualizaciones se verifican automáticamente cuando se abre la página si tiene 120 minutos de antigüedad.
- **Centro de actualizaciones** : La barra de progreso ahora está en la pestaña *Core y plugins*, y el registro se abre por defecto en la pestaña *Información*.
- **Centro de actualizaciones** : Si abre otro navegador durante una actualización, la barra de progreso y el registro lo indican.
- **Centro de actualizaciones** : Si la actualización finaliza correctamente, se muestra una ventana que solicita volver a cargar la página.
- **Actualizaciones principales** : Implementación de un sistema para limpiar viejos archivos Core no utilizados.
- **Guión** : Agregar un motor de búsqueda (a la izquierda del botón Ejecutar).
- **Guión** : Adición de la función de edad (da la edad del valor del pedido).
- **Guión** : *stateChanges()* ahora acepta el periodo *Hoy* (medianoche hasta ahora), *ayer* y *dia* (por 1 día).
- **Guión** : Funciones *estadísticas (), promedio (), máximo (), mínimo (), tendencia (), duración()* : Bugfix durante el período *ayer*, y acepta ahora *dia* (por 1 día).
- **Guión** : Posibilidad de desactivar el sistema de cotización automática (Configuración → Sistema → Configuración : Commandes).
- **Guión** : Viendo un *Advertencia* si no se configura ningún activador.
- **Guión** : Corrección de errores de seleccionar en el bloque copiar / pegar.
- **Guión** : Copiar / pegar bloque entre diferentes escenarios.
- **Guión** : Las funciones de deshacer / rehacer ahora están disponibles como botones (al lado del botón de creación de bloque).
- **Guión** :  adición de "Exportación histórica" (exportHistory)
- **Ventana de variables de escenario** : Clasificación alfabética en la apertura.
- **Ventana de variables de escenario** : Ahora se puede hacer clic en los escenarios utilizados por las variables, con la apertura de la búsqueda en la variable.
- **Análisis / Historia** : Ctrl Haga clic en una leyenda para mostrar solo este historial, Alt Haga clic para mostrarlos todos.
- **Análisis / Historia** : Las opciones *agrupación, tipo, variación, escalera* están activos solo con una sola curva mostrada.
- **Análisis / Historia** : Ahora podemos usar la opción *Area* con la opción *Escalera*.
- **Análisis / Historia** : Posibilidad de comparar un historial durante varios períodos.
- **Análisis / Registros** : Nueva fuente tipo monoespacio para registros.
- **Vista** : Posibilidad de poner escenarios.
- **Vista** : El modo de edición ahora inserta el mosaico movido.
- **Vista** : Modo de edición: Los iconos de actualización del equipo se reemplazan por un icono que permite acceder a su configuración, gracias a un nuevo modal simplificado.
- **Vista** : El orden de visualización ahora es independiente del que se muestra en el Panel de control.
- **Línea de tiempo** : Separación de páginas de historia y cronología.
- **Línea de tiempo** : Integración de la línea de tiempo en DB por razones de confiabilidad.
- **Línea de tiempo** : Gestión de múltiples líneas de tiempo.
- **Línea de tiempo** : Rediseño gráfico completo de la línea de tiempo (Escritorio / Móvil).
- **Resumen global** : Vista de resumen, soporte para resúmenes de un objeto diferente o con un objeto raíz vacío (escritorio y aplicación web).
- **Resumen de domótica** : Equipos de complementos desactivados y sus controles ya no tienen los iconos a la derecha (configuración de equipos y configuración avanzada).
- **Resumen de domótica** : Posibilidad de buscar en categorías de equipos.
- **Resumen de domótica** : Posibilidad de mover varios equipos de un objeto a otro.
- **Resumen de domótica** : Posibilidad de seleccionar todo el equipo de un objeto.
- **Motor de tareas** : En la pestaña *Demonio*, los complementos deshabilitados ya no aparecen.
- **Reporte** : Uso de chronium si está disponible.
- **Reporte** : Posibilidad de exportar cronogramas.
- **Configuración** : La pestaña *Información* ahora está en la pestaña *Principal*.
- **Configuración** : La pestaña *Comandos* ahora está en la pestaña *Dispositivos*.
- **Ventana de configuración avanzada del equipo** : Cambio dinámico de la configuración de la centralita.
- **Dispositivos** : Nueva categoría *Apertura*.
- **Dispositivos** : Posibilidad de invertir comandos tipo cursor (info y acción)
- **Dispositivos** : Posibilidad de agregar clase css a un mosaico (consulte la documentación del widget).
- **Sobre ventana** : Adición de accesos directos al registro de cambios y preguntas frecuentes.
- Widgets / Objetos / Escenarios / Interacciones / Páginas de complementos :
	- Ctrl Clic / Clic Center en un widget, objeto, escenarios, interacción, equipo de complemento : Se abre en una pestaña nueva.
	- Ctrl Clic / Clic Center también disponible en sus menús contextuales (en las pestañas).
- Nueva página ModalDisplay :
	- Menú de análisis : Ctrl Click / Click Center en *Tiempo real* : Abra la ventana en una pestaña nueva, en pantalla completa.
	- Menú de herramientas : Ctrl Click / Click Center en *Notas*, *Probador de expresión*, *Las variables*, *Buscar* : Abra la ventana en una pestaña nueva, en pantalla completa.
- Bloque de código, Editor de archivos, Personalización avanzada : Adaptación del tema oscuro.<br/><br/>
- **Aplicación web** : Integración de la nueva página de resumen.
- **Aplicación web** : Página de escenarios, un clic en el título del escenario muestra su registro.
- **Aplicación web** : Ahora podemos seleccionar / copiar parte de un registro.
- **Aplicación web** : En la búsqueda en un registro, agregue un botón x para cancelar la búsqueda.
- **Aplicación web** : Persistencia del cambio de tema (8h).
- **Aplicación web** : En un diseño, un clic con tres dedos vuelve a la página de inicio.
- **Aplicación web** : Visualización de escenarios por grupo.
- **Aplicación web** : Nueva fuente tipo monoespacio para registros.
- **Aplicación web** : Muchas correcciones de errores (UI, vertical / horizontal iOS, etc.).<br/><br/>
- **Documentación** : Adaptaciones en línea con v4 y v4.1.
- **Documentación** : Nueva página *Atajos de teclado / mouse* incluyendo un resumen de todos los atajos en Jeedom. Accesible desde el Dashboard doc o las preguntas frecuentes.
- **Lib** : Actualizar HighStock v7.1.2 a v8.2.0.
- **Lib** : Actualizar jQuery v3.4.1 a v3.5.1.
- **Lib** : Actualizar Font Awesome 5.9.0 a 5.13.1.
- Asegurando solicitudes Ajax.
- Correcciones de errores.
- Numerosas optimizaciones de rendimiento de escritorio / móvil.


>**Importante**
>
> La inversión de los comandos binarios ya no solo invierte el widget sino el valor del comando, por lo que será necesario reconfigurar correctamente los escenarios y los resúmenes que utilizan comandos del tipo binario invertido
