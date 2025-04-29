# Mockups para Banco Saint Patrick Home Banking

## Paleta de colores
- **Color primario:** Verde oscuro (#0A4B4F) - Color del escudo
- **Color secundario:** Dorado/Amarillo (#F2C94C) - Color del trébol
- **Blanco:** #FFFFFF - Para fondos y texto sobre colores oscuros
- **Gris claro:** #F3F4F6 - Para áreas de contenido y fondos secundarios
- **Gris oscuro:** #4B5563 - Para textos secundarios
- **Negro:** #1F2937 - Para textos principales
- **Verde éxito:** #10B981 - Para confirmaciones y transacciones exitosas
- **Rojo error:** #EF4444 - Para alertas y errores

## Tipografía
- **Títulos:** Montserrat Bold
- **Cuerpo:** Montserrat Regular
- **Números de cuenta/tarjeta:** Roboto Mono (para mejor legibilidad de números)

## 1. Página de Login

![Login del Banco Saint Patrick]

**Elementos:**
- Logo del banco (escudo con trébol) en la parte superior
- Título "Bienvenido a Saint Patrick Banking"
- Campo para número de tarjeta con formato XXXX-XXXX-XXXX-XXXX
- Campo para PIN (con opción para mostrar/ocultar)
- Botón "Ingresar" en color verde primario
- Mensaje de error (oculto por defecto)
- Nota de seguridad en la parte inferior
- Indicador de tiempo de inactividad

## 2. Página de Saldo (Dashboard)

![Dashboard Principal]

**Elementos:**
- Barra superior con logo, nombre del usuario y botón de cerrar sesión
- Tarjeta principal mostrando el saldo actual en formato grande
- Número de tarjeta parcialmente oculido (solo últimos 4 dígitos visibles)
- Sección "Resumen de cuenta" con:
  - Saldo actual
  - Última transacción
  - Fecha de última actividad
- Botón grande "Realizar transacción"
- Botón "Ver historial de transacciones"
- Contador de inactividad discreto en la esquina inferior

## 3. Historial de Transacciones

![Historial de Transacciones]

**Elementos:**
- Barra superior con logo, nombre del usuario y botón de cerrar sesión
- Título "Historial de Transacciones del Mes"
- Filtros por tipo (entrantes/salientes/todas)
- Lista de transacciones con:
  - Fecha y hora
  - Tipo (entrada/salida)
  - Número de tarjeta origen/destino (parcialmente oculto)
  - Monto con color verde (entrada) o rojo (salida)
- Botón "Realizar nueva transacción" destacado
- Botón "Volver al dashboard"
- Contador de inactividad discreto

## 4. Nueva Transacción

![Nueva Transacción]

**Elementos:**
- Barra superior con logo, nombre del usuario y botón de cerrar sesión
- Título "Realizar Transferencia"
- Formulario con:
  - Campo para número de tarjeta destino (con validación)
  - Campo para monto a transferir
  - Campo opcional para concepto/mensaje
- Indicador de saldo disponible
- Botón "Continuar" (para ir a confirmación)
- Botón "Cancelar" (vuelve al dashboard)
- Contador de inactividad discreto

## 5. Confirmación de Transacción

![Confirmación de Transacción]

**Elementos:**
- Barra superior con logo, nombre del usuario y botón de cerrar sesión
- Título "Confirmar Transferencia"
- Resumen de la transacción con:
  - Tarjeta origen (últimos 4 dígitos)
  - Tarjeta destino (últimos 4 dígitos)
  - Monto a transferir
  - Concepto/mensaje (si fue ingresado)
- Saldo actual y saldo después de la transacción
- Botón "Confirmar transferencia" en color primario
- Botón "Modificar" (vuelve a pantalla anterior)
- Botón "Cancelar" (vuelve al dashboard)
- Contador de inactividad discreto

## 6. Transacción Exitosa

![Transacción Exitosa]

**Elementos:**
- Ícono grande de éxito (check en círculo verde)
- Mensaje "¡Transferencia Exitosa!"
- Resumen de la transacción con:
  - Número de transacción/referencia
  - Tarjeta destino (últimos 4 dígitos)
  - Monto transferido
  - Fecha y hora
- Botón "Realizar otra transferencia"
- Botón "Volver al inicio"
- Contador de inactividad discreto

## 7. Sesión Cerrada

![Sesión Cerrada]

**Elementos:**
- Logo del banco
- Mensaje "Sesión finalizada correctamente"
- Texto secundario "Por seguridad, su sesión ha sido cerrada"
- Botón "Volver a iniciar sesión"
- Nota de seguridad
- Temporizador (si se cerró por inactividad, muestra el mensaje "Su sesión se cerró por inactividad")

## Diseño Responsivo

Todos los mockups deben considerar al menos tres tamaños de pantalla:
- **Móvil:** 360px - 480px
- **Tablet:** 768px - 1024px
- **Desktop:** 1280px+

Para móviles, las tarjetas y formularios utilizarán el ancho completo de la pantalla, mientras que en tablets y desktop tendrán un ancho máximo y estarán centrados.

## Componentes Comunes

**Tarjetas de Crédito/Débito visualizadas:**
- Diseño que simula una tarjeta física
- Colores que corresponden al banco (verde y dorado)
- Solo muestra los últimos 4 dígitos del número completo
- Incluye fecha de vencimiento (si aplica)

**Botones:**
- Primarios: Fondo verde, texto blanco, bordes redondeados
- Secundarios: Borde verde, texto verde, fondo transparente
- De cancelación: Gris claro con texto oscuro

**Timer de inactividad:**
- Circular, discreto, en la esquina inferior derecha
- Muestra los segundos restantes antes del cierre automático
- Cambia a color rojo cuando quedan menos de 5 segundos

## 8. Aviso de finalizacion de sessión

![Aviso de finalizacion de sessión]

**Características principales:**

- Diseño Modal: Aparece sobre el contenido actual con un fondo semitransparente.
- Temporizador Visual:

- Un círculo que funciona como una cuenta regresiva visual
- Animación que completa una vuelta en 60 segundos
- Contador numérico en el centro que muestra los segundos restantes


**Mensajes Claros:**

- Título "Su sesión está por finalizar"
- Explicación sobre el motivo de seguridad
- Pregunta si desea ampliar el tiempo de sesión


**Opciones para el Usuario:**

- Botón "Ampliar sesión" (botón primario en verde del banco)
- Botón "Finalizar ahora" (botón secundario con borde)


**Nota de Seguridad:**

- Recomendación para proteger los datos del usuario


**Funcionalidad:**

- JavaScript que controla la cuenta regresiva
- Cambio de color del contador cuando queda poco tiempo
- Comportamiento configurado para ambos botones
