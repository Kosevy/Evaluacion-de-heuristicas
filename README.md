**UX Heuristics & Principles Evaluation**  
**Usability – Inclusive Design – Information Architecture**

**CARRERA		:** Ingeniería de Software  
**CURSO		:** Aplicaciones Web  
**SECCIÓN		:** 17953  
**PROFESORES		:** Todos  
**AUDITOR		:** PircaIndustries  
**CLIENTE		:** Francia Torres, Jhony Manuel, Montoya Nina, Paula Fernanda, Palacios Tinoco Adrian Fernando, Ramos Hinostroza, Diego Antonio y Ramos Mera, Neo Daniel.

## 

## **SITE o APP A EVALUAR:**

## AutoService

## **TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Landing Page  
2. Registro e Inicio Sesión  
3. Panel Principal  
4. Clientes  
5. Vehículos  
6. Inventario y Repuestos

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Notificaciones  
2. Configuraciones de accesibilidad

## **ESCALA DE SEVERIDAD:**

*Los errores serán puntuados tomando en cuenta la siguiente escala de severidad*

| *Nivel* | *Descripción* |
| :---- | :---- |
| *1* | *Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.* |
| *2* | *Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase* |
| *3* | *Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.* |
| *4* | *Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.* |

## **TABLA RESUMEN:**

| *\#* | *Problema* | *Escala de severidad* | *Heurística/Principio violada(o)* |
| :---: | ----- | :---: | ----- |
| 1 | Logotipo de tamaño muy reducido en encabezado y pie de página | 2 | Diseño estético y minimalista |
| 2 | Imagen descentrada con margen inferior desproporcionado | 1 | Diseño estético y minimalista |
| 3 | Inconsistencia en la altura de los botones de navegación | 1 | Heurística 4: Consistencia y estándares |
| 4 | Botones de navegación (flechas) inactivos | 3 | Control y libertad del usuario |
| 5 | Envío de formulario sin validación de campos vacíos | 3 | Prevención de errores |
| 6 | Falta de traducción en el título del portal de seguimiento | 2 | Consistencia y estándares |
| 7 | Texto del marcador de posición (placeholder) cortado | 2 | Diseño estético y minimalista |
| 8 | Ausencia de logotipo o nombre comercial en vistas de autenticación | 2 | Reconocimiento antes que recuerdo |
| 9 | Ausencia de mensajes de error al enviar formularios vacíos | 3 | Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores |
| 10 | Duplicidad de registros por falta de control de peticiones simultáneas en el formulario de creación de vehículo | 3 | Usability: “Prevención de errores” y “Visibilidad del estado del sistema” |
| 11 | Distorsión visual y recorte inadecuado en la previsualización de la imagen del vehículo | 2 | Usability: “Relación entre el sistema y el mundo real” y “Estética y diseño minimalista” |
| 12 | Ausencia de mensajes de validación y feedback visual ante el envío de campos obligatorios vacíos | 3 | Usability: “Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores” y “Visibilidad del estado del sistema” |
| 13 | Presencia de etiquetas de traducción sin procesar (raw keys) en la pantalla de detalle del vehículo | 2 | Information Architecture: “Rotulado” |
| 14 | Duplicidad en el registro de clientes debido a la falta de bloqueo en peticiones simultáneas del formulario de registro de cliente | 3 | Usability: “Prevención de errores” y “Visibilidad del estado del sistema” |
| 15 | Presencia de claves de localización rotas (raw translation keys) en modales de edición y eliminación de clientes | 2 | Information Architecture: “Rotulado” |
| 16 | Despliegue de errores críticos mediante diálogos de alerta nativos del navegador | 2 | Usability: “Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores” y “Consistencia y estándares”. |
| 17 | Sobreposición de los inputs para ingresar nuevo artículo | 2 | Diseño estético y minimalista |
| 18 | Overflow en el formulario no controlado | 2 | Diseño estético y minimalista |
| 19 | Internacionalización a medias | 2 | Relación entre el sistema y el mundo real  |
| 20 | Interfaz duplicada y sin respetar espacios | 2 | Prevención de errores (Heurística \#5) / Flexibilidad y eficiencia de uso (Heurística \#7)  |
| 21 | Selector de filtrado por mecánico vacío y sin estado inicial claro | 2 | Prevención de errores (Heurística \#5) / Visibilidad del estado del sistema (Heurística \#1)   |
| 22 | Falta de control de estados vacíos (Empty States) cuantitativos en el Panel Principal | 1 | Reconocimiento antes que recuerdo (Heurística \#6) / Estética y diseño minimalista (Heurística \#8) |

## 

## **DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA \#1: Logotipo de tamaño muy reducido en encabezado y pie de página**

Severidad: 2

Heurística violada: Diseño estético y minimalista 

Problema: El logotipo de la empresa presenta dimensiones muy reducidas, lo que dificulta su correcta apreciación tanto en el encabezado (header) como en el pie de página (footer) de la plataforma.

<img width="886" height="125" alt="Image" src="https://github.com/user-attachments/assets/6ec32309-fc93-4185-b245-c90197783347" />

<img width="886" height="158" alt="Image" src="https://github.com/user-attachments/assets/e6df9516-42a5-4174-82be-12c511c1b39a" />

Recomendación; Aumentar el tamaño y la proporción del logotipo para asegurar la legibilidad y reforzar la identidad visual de la marca en todas las pantallas.

**PROBLEMA \#2: Imagen descentrada con margen inferior desproporcionado**

Severidad: 1

Heurística violada: Diseño estético y minimalista

Problema: La imagen ilustrativa en la sección que presenta el problema y la solución no se encuentra centrada, presentando un espacio vacío desproporcionado en su parte inferior. 

<img width="886" height="513" alt="Image" src="https://github.com/user-attachments/assets/7f93766f-ae09-4e4c-b704-0298f31a0ee7" />

Recomendación;  Ajustar los estilos CSS de la imagen y su contenedor para asegurar una alineación simétrica y eliminar el espacio residual innecesario. 

**PROBLEMA \#3: Inconsistencia en la altura de los botones de navegación**

Severidad: 1

Heurística violada: Consistencia y estándares

Problema: Los botones de acción ubicados en la barra de navegación ("Login" y el selector de idioma "ES") presentan alturas diferentes, lo cual rompe la consistencia visual de la interfaz. 

<img width="886" height="60" alt="Image" src="https://github.com/user-attachments/assets/f3aee22c-2183-4fd5-b700-894959929e0e" />

Recomendación;  Homogeneizar las dimensiones (altura y padding) de todos los elementos interactivos dentro de la barra de navegación para mantener un estándar visual.

**PROBLEMA \#4: Botones de navegación (flechas) inactivos**

Severidad: 3

Heurística violada: Control y libertad del usuario

Problema: En la sección "Designed for simplicity and real workshop needs", los controles de navegación (flechas direccionales) no ejecutan ninguna acción ni retroalimentación al ser presionados por el usuario.

<img width="886" height="431" alt="Image" src="https://github.com/user-attachments/assets/2a6e9455-9df3-4585-b81c-2fb520d574f5" />

Recomendación;  Implementar la interactividad correspondiente al carrusel de imágenes, o en su defecto, ocultar dichos controles hasta que la funcionalidad esté completamente desarrollada. 

**PROBLEMA \#5: Envío de formulario sin validación de campos vacíos**

Severidad: 3

Heurística violada: Prevención de errores

Problema: El formulario de contacto permite el envío de datos completamente vacíos, mostrando erróneamente un mensaje modal de confirmación exitosa ("Message sent\!"). 

<img width="886" height="629" alt="Image" src="https://github.com/user-attachments/assets/66448cbf-e6ec-4c29-99d4-2affc1d5563c" />

Recomendación;  Establecer validaciones obligatorias en los campos del formulario y deshabilitar el botón de envío ("Send Message") hasta que todos los datos requeridos sean ingresados correctamente.

**PROBLEMA \#6: Falta de traducción en el título del portal de seguimiento**

Severidad: 2

Heurística violada: Consistencia y estándares

Problema: Al interactuar con el inicio de sesión y seleccionar el idioma inglés ("EN"), al navegar hacia la sección "Are you a customer of the workshop?", el título principal ("Portal de Seguimiento") permanece en español, generando inconsistencia en la localización.

<img width="427" height="661" alt="Image" src="https://github.com/user-attachments/assets/610b7426-d2fd-4a2b-a707-54d841c2aac9" />

<img width="700" height="488" alt="Image" src="https://github.com/user-attachments/assets/76651783-e552-49c0-8f9a-710498b98bd3" />

Recomendación;  Revisar y asegurar que las variables de internacionalización (i18n) cubran la totalidad de los elementos de texto en las vistas cuando se alterna entre idiomas.

**PROBLEMA \#7: Texto del marcador de posición (placeholder) cortado**

Severidad: 2

Heurística violada: Diseño estético y minimalista

Problema: En el portal de seguimiento, el texto indicativo (placeholder) dentro del campo de texto en la versión en español excede el límite visible y se recorta ("Ingresa el código de tu orc...").

<img width="886" height="663" alt="Image" src="https://github.com/user-attachments/assets/3ec813cd-f8b0-4596-96ab-f5195d080521" />

Recomendación;  Reducir la longitud del texto del marcador de posición o incrementar el ancho del campo de entrada para garantizar que las instrucciones sean completamente visibles.

**PROBLEMA \#8: Ausencia de logotipo o nombre comercial en vistas de autenticación**

Severidad: 2

Heurística violada: Reconocimiento antes que recuerdo

Problema: Las pantallas destinadas al inicio de sesión y al registro carecen de elementos de identidad corporativa, no encontrándose presente ni el logotipo ni el nombre del producto de manera explícita. 

<img width="886" height="473" alt="Image" src="https://github.com/user-attachments/assets/b52d4341-41e6-42de-b894-7f70b301f2bb" />

Recomendación;  Incorporar el logotipo o el nombre comercial de la plataforma en la parte superior del formulario de autenticación para otorgar contexto inmediato al usuario. 

**PROBLEMA \#9: Ausencia de mensajes de error al enviar formularios vacíos**

Severidad: 3

Heurística violada: Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de errores

Problema: Al accionar los botones de confirmación en las vistas de inicio de sesión y registro sin haber completado la información, el sistema omite generar mensajes de advertencia o retroalimentación visual sobre la obligatoriedad de los campos.

<img width="575" height="639" alt="Image" src="https://github.com/user-attachments/assets/2dd73106-8c96-4486-8ddd-73c0a5d14a11" /><img width="575" height="639" alt="Image" src="https://github.com/user-attachments/assets/cf280474-9c46-4400-82fb-f8fa4aec52f9" />

Recomendación;  Añadir mensajes de error explícitos adyacentes a los campos vacíos (por ejemplo, textos en color rojo) y aplicar estilos de error en los bordes de las cajas de texto cuando la validación falla.

**PROBLEMA \#10: Duplicidad de registros por falta de control de peticiones simultáneas en el formulario de creación de vehículo**

Severidad: 3

Heurística violada: Usabilidad \- “Prevención de errores” y “Visibilidad del estado del sistema” 

Problema: Al hacer clic en el botón "Guardar" del modal de creación de vehículo, el sistema experimenta un tiempo de latencia sin ofrecer retroalimentación visual inmediata. Durante este intervalo, la interfaz mantiene el botón interactivo y el modal abierto. Si el usuario hace clic múltiples veces por frustración o incertidumbre, la aplicación procesa cada pulsación de manera independiente, lo que resulta en la inserción de registros duplicados en el listado de vehículos (como se observa con las dos tarjetas idénticas de placa 12345678 asociadas a Juan Pérez).

<img width="865" height="414" alt="Image" src="https://github.com/user-attachments/assets/10c267d1-4c5e-45e1-9212-a0713a8180e0" />

<img width="868" height="415" alt="Image" src="https://github.com/user-attachments/assets/106f6773-94e1-4f98-9b37-9be9d8187260" />

Recomendación:  Implementar un estado de carga visual en el botón "Guardar" al recibir el primer clic (por ejemplo, mostrando un indicador giratorio o spinner y cambiando el texto a "Guardando..."). De manera simultánea, se debe deshabilitar temporalmente el botón "Guardar" y el botón "Cancelar" para evitar interacciones repetidas mientras se procesa la solicitud. El modal solo debe cerrarse una vez que el flujo se haya completado con éxito, refrescando la vista principal.

**PROBLEMA \#11: Distorsión visual y recorte inadecuado en la previsualización de la imagen del vehículo**

Severidad: 2

Heurística violada: Usabilidad \- “Relación entre el sistema y el mundo real” y “Estética y diseño minimalista”

Problema: Al adjuntar una imagen del vehículo en el formulario de creación, la caja de previsualización de la interfaz no respeta el formato o relación de aspecto original de la fotografía. El contenedor obliga a la imagen a ajustarse a un formato extremadamente apaisado y recortado (solo visible como una franja del cielo en la primera captura). Esta distorsión dificulta que el usuario verifique visualmente si cargó la fotografía correcta antes de guardarla.

<img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/39b2bce0-783e-44a6-9b43-53078f972989" />

Recomendación:  Ajustar el contenedor de la imagen en la interfaz del frontend para que mantenga una relación de aspecto estándar (como 16:9 o 4:3) y aplique técnicas de escalado que aseguren que el automóvil quede centrado y completamente visible dentro de la caja de previsualización sin recortarse de forma drástica. Se sugiere añadir un botón para "Reemplazar imagen" o "Eliminar" directamente en la miniatura de previsualización.

**PROBLEMA \#12: Ausencia de mensajes de validación y feedback visual ante el envío de campos obligatorios vacíos**

Severidad: 3

Heurística violada: Usabilidad \- “Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores” y “Visibilidad del estado del sistema”

Problema: Cuando el usuario hace clic en el botón "Guardar" sin haber completado los campos requeridos marcados con asterisco rojo (Cliente propietario \* y Placa \*), la interfaz bloquea el registro del vehículo (comportamiento correcto), pero no proporciona ninguna indicación visual del error. El usuario no recibe notificaciones de texto, resaltados en rojo en los campos vacíos ni mensajes flotantes que indiquen qué información falta completar, lo cual genera incertidumbre sobre si el botón funciona correctamente.

<img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/bbd128be-b01b-48c3-b7c6-2fde8415e44b" />

Recomendación:  Al presionar "Guardar", si existen campos obligatorios vacíos, la interfaz debe cancelar el envío, enfocar automáticamente el primer campo con error, resaltar los bordes de los campos vacíos en color de advertencia (rojo) y mostrar un mensaje descriptivo inmediatamente debajo de ellos (ej. "Este campo es obligatorio"). Opcionalmente, se puede mostrar una alerta emergente (toast notification) en la esquina superior del panel indicando al usuario que revise el formulario.

**PROBLEMA \#13: Presencia de etiquetas de traducción sin procesar (raw keys) en la pantalla de detalle del vehículo**

Severidad: 2

Heurística violada: Arquitectura de la Información \- “Rotulado”

Problema: En la ficha informativa del propietario del vehículo, la etiqueta correspondiente al correo electrónico se muestra en la pantalla como common.email en lugar de una etiqueta amigable y legible para el usuario en su respectivo idioma (como "Correo electrónico" o "Email"). Esto denota una falta de localización en el frontend y reduce la calidad visual del producto ante el administrador.

<img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/5b2ad70c-824d-45e5-aef5-07b2101a6b78" />

Recomendación:  Reemplazar el identificador técnico de la cadena de traducción (common.email) en el frontend por su valor localizado correspondiente en español ("Correo electrónico") e inglés ("Email"), asegurando que la interfaz resuelva correctamente las propiedades del diccionario de traducción antes de renderizar la vista.

**PROBLEMA \#14: Duplicidad en el registro de clientes debido a la falta de bloqueo en peticiones simultáneas del formulario de registro de cliente**

Severidad: 3

Heurística violada: Usabilidad \- “Prevención de errores” y “Visibilidad del estado del sistema”

Problema: Al guardar un nuevo cliente ("Jhon Hernandez"), el botón "Guardar" no se deshabilita ni muestra un indicador de carga durante el proceso de almacenamiento. Si el usuario realiza múltiples clics consecutivos en el botón antes de que el servidor responda, la interfaz ejecuta múltiples peticiones de inserción. Esto se evidencia en la vista del listado de clientes, donde aparecen tres registros idénticos con el mismo DNI y datos de contacto creados en el mismo instante.

<img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/7953bbdc-d90c-4199-b16b-e3c435c87538" /><img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/c74db998-1185-4316-9963-5d25731d543d" />

Recomendación: Deshabilitar los botones de acción ("Guardar" y "Cancelar") inmediatamente después del primer clic y añadir un indicador de carga (spinner) en el interior del botón principal. El formulario debe limpiarse y cerrarse de manera automática solo cuando se confirme que la petición de guardado ha sido exitosa.

**PROBLEMA \#15: Presencia de claves de localización rotas (raw translation keys) en modales de edición y eliminación de clientes**

Severidad: 2

Heurística violada: Arquitectura de la Información \- “Rotulado”

Problema: Al interactuar con el módulo de clientes, varios textos clave de la interfaz no se renderizan correctamente y exponen nombres de variables del sistema en lugar de texto en lenguaje natural. Se identifican las siguientes etiquetas rotas:

* **Modal de edición:** “customers.form.editTitle” (Título) y “customers.form.update” (Botón de confirmación).  
* **Modal de eliminación:** “customers.delete.title” (Título), “customers.delete.description” (Descripción), “customers.delete.cancel” (Botón de cancelar) y “customers.delete.confirm” (Botón de confirmar). Esto afecta negativamente la confianza del usuario final en la madurez técnica de la aplicación.

<img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/974629b8-ff29-4144-9f80-498b240f1c24" /><img width="886" height="425" alt="Image" src="https://github.com/user-attachments/assets/468d6d47-7ab1-4cd7-a9b1-bee3ec08a2b0" />

Recomendación: Configurar y mapear adecuadamente las claves correspondientes en los archivos de localización de idiomas del frontend (español e inglés). Asegurar que la librería de traducción se inicialice antes de renderizar estos modales dinámicos.

**PROBLEMA \#16: Despliegue de errores críticos mediante diálogos de alerta nativos del navegador**

Severidad: 2

Heurística violada: Usabilidad \- “Ayuda a los usuarios a reconocer, diagnosticar y recuperarse de errores” y “Consistencia y estándares”.

Problema: Cuando ocurre un fallo técnico al intentar eliminar un cliente (por ejemplo, "Jhon Hernandez"), la interfaz de usuario delega el manejo del error a una alerta emergente nativa del navegador (window.alert) que muestra el mensaje genérico "Error al eliminar el cliente". Este tipo de alertas bloquean toda la interacción del navegador, tienen un aspecto visual ajeno a la línea gráfica de la aplicación y carecen de un formato amigable que sugiera al usuario cómo solucionar el problema o por qué ocurrió.

<img width="886" height="440" alt="Image" src="https://github.com/user-attachments/assets/b2d85c36-5142-4c27-89bf-a93b76aa43f2" />

Recomendación: Reemplazar el cuadro de alerta nativo por un componente de notificación del sistema integrado dentro de la aplicación (toast banner o una alerta modal estilizada con los colores del sistema de diseño). El mensaje debe ser descriptivo e indicar una razón clara (ej. "No se pudo eliminar el cliente porque tiene vehículos o servicios activos asociados").

**PROBLEMA \#17: Sobreposición de los inputs para ingresar nuevo artículo**

Severidad: 2

Heurística violada: Diseño estético y minimalista

Problema: Al tratar de crear un nuevo artículo, el apartado de texto para la marca está sobrepuesto en el de categoría, lo cual no resulta un problema que imposibilite al usuario ingresar los datos, sin embargo, a nivel de diseño y estético es necesario encargarse de ello.

<img width="713" height="969" alt="Image" src="https://github.com/user-attachments/assets/cbfa8155-e38e-4c54-9640-0fc1773bee09" />

Recomendación:

Manejar el diseño flexible y las media queries del formulario para que el ingreso de la información sea más óptimo.

**PROBLEMA \#18: Overflow en el formulario no controlado**

Severidad: 2

Heurística violada: Diseño estético y minimalista

Problema: El input para el stock mínimo está saliéndose de los límites del formulario, lo que está ocasionando a su vez un scroll innecesario que está sobreponiéndose al contenedor de imagen del material.

<img width="584" height="144" alt="Image" src="https://github.com/user-attachments/assets/7bd77a6e-4547-41e9-8f18-a2db2d1f2d2d" />

<img width="533" height="723" alt="Image" src="https://github.com/user-attachments/assets/21848e28-2d74-4c40-bb4d-45de5c732da5" />

<img width="563" height="202" alt="Image" src="https://github.com/user-attachments/assets/7033fa9b-9bb2-4e58-9c08-2a7ecdf7402c" />

Recomendación:

Controlar el espacio dirigido para cada apartado del formulario y mantener la flexibilidad con las media queries por posibles cambios de resolución en la pantalla.

**PROBLEMA \#19: Internacionalización a medias**

Severidad: 2

Heurística violada: Relación entre el sistema y el mundo real 

Problema: Aún existen zonas en las que la información no está recogiendo de forma correcta la traducción hacia los lenguajes de la página y solo está mostrando la dirección. Esto, para el usuario objetivo, podría resultar un problema de comprensión ya que no sabría qué es lo que la página está tratando de comunicar y es necesaria su revisión.

<img width="526" height="706" alt="Image" src="https://github.com/user-attachments/assets/f41baf42-eaba-4900-84b1-fd74ab448630" />

<img width="309" height="156" alt="Image" src="https://github.com/user-attachments/assets/81a15c2f-dc26-4d8c-919e-e49e7924a476" />

Recomendación:

Revisar minuciosamente la información con internacionalización y verificar que todos los textos se estén mostrando de forma exitosa en la página.

**PROBLEMA \#20: Interfaz duplicada y sin respetar espacios**

Severidad: 2

Heurística violada: Prevención de errores (Heurística \#5) / Flexibilidad y eficiencia de uso (Heurística \#7) 

Problema: En el campo "Cuenta de Mecánico", el usuario ya ingresó un correo electrónico completo (manolito.rojas@gmail.com), pero la interfaz duplica el dominio mostrando un texto fijo abajo (@gmail.com). Esto confunde al usuario sobre si debe ingresar el correo completo o solo el usuario, además de sugerir un formato rígido (nombre+apellido) que limita el uso de correos corporativos o de otros proveedores. Ademas, al terminar con el formulario las palabras salen del contenedor

<img width="552" height="869" alt="Image" src="https://github.com/user-attachments/assets/eed70cfc-5b0c-4215-adfd-6070b17e103d" />

<img width="642" height="552" alt="Image" src="https://github.com/user-attachments/assets/86a8750d-b25d-4d3a-8646-39de606b1a29" />

Recomendación: Eliminar la etiqueta estática `@gmail.com` externa al campo. Permitir que el usuario ingrese libremente cualquier dirección de correo electrónico válida y cambiar el texto de ayuda por algo más flexible, como: *"Ingrese el correo electrónico del mecánico"*. Agregar también algun acortador de frases cuando la cadena sea demasiado larga para que no sobrepase el espacio asignado.

**PROBLEMA \#20: Duplicidad en tabla**

Severidad: 1

Heurística violada: Consistencia y estándares (Heurística \#4) 

Problema: En la tabla de la sección "Tareas de la Orden", la cabecera presenta una columna duplicada. La etiqueta **"Materiales"** aparece dos veces (como tercera y quinta columna), lo que genera confusión visual y desorganización en la presentación de los datos. 

<img width="886" height="431" alt="Image" src="https://github.com/user-attachments/assets/829a1c23-51ee-4eeb-9e70-163aeb16f142" />

Recomendación: Revisar el componente de la tabla para eliminar la columna duplicada de **"Materiales"** o, en caso de que corresponda a un dato distinto, corregir el texto de la cabecera con el nombre correcto (por ejemplo: "Cantidad", "Acciones", etc.). 

**PROBLEMA \#21: Selector de filtrado por mecánico vacío y sin estado inicial claro** 

Severidad: 2

Heurística violada: Prevención de errores (Heurística \#5) / Visibilidad del estado del sistema (Heurística \#1) 

Problema: En la vista del "Tablero de tareas" (versión en español), al desplegar el filtro de "Mecánico", la lista desplegable muestra el mensaje *"No available options"* en inglés, a pesar de que el sistema está configurado en español. Además, el selector se muestra completamente en blanco sin un texto instructivo inicial (como "Seleccionar mecánico"), lo que genera incertidumbre sobre si existen mecánicos registrados en el sistema o si se trata de un fallo de carga de datos.

<img width="886" height="405" alt="Image" src="https://github.com/user-attachments/assets/f807c0eb-98b2-4377-ba18-a4a774f7f723" />

Recomendación: Implementar un estado por defecto legible para el selector (por ejemplo, "Todos los mecánicos" o "Seleccionar..."). Asimismo, asegurar que los mensajes de las listas vacías estén correctamente internacionalizados con vue-i18n para cambiar dinámicamente a "No hay opciones disponibles" cuando el idioma seleccionado sea el español. 

**PROBLEMA \#22: Falta de control de estados vacíos (Empty States) cuantitativos en el Panel Principal** 

Severidad: 1

Heurística violada: Reconocimiento antes que recuerdo (Heurística \#6) / Estética y diseño minimalista (Heurística \#8)

Problema: En el "Panel Principal del Taller", los contenedores destinados a mostrar los gráficos de "Ingresos semanales", "Actividad reciente" y "Servicios frecuentes" se renderizan completamente vacíos y desproporcionados cuando no hay datos registrados en el sistema. La gráfica muestra un eje numérico vertical flotando sin barras ni referencias temporales claras en el eje X, mientras que las secciones inferiores carecen de un mensaje aclaratorio o ilustración amigable, dejando cajas grises desoladas.

<img width="1949" height="894" alt="Image" src="https://github.com/user-attachments/assets/736dcbe0-9265-433b-96fc-eb1d58abb956" /> 

Recomendación: Implementar componentes de "Empty State" controlados. Cuando los arreglos de datos de las órdenes o ingresos estén vacíos, se debe ocultar el lienzo de la gráfica o la tabla vacía y, en su lugar, mostrar un texto sutil con un diseño limpio que indique al usuario algo como: *"No hay actividad registrada esta semana. Las métricas aparecerán cuando crees tu primera orden de trabajo"*.
