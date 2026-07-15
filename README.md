# SICAR puente de conexión POS

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1784063241/assets/proyecto-verificador-precios/bridge-libp2p/images/icon.svg" alt="Logo del proyecto Puente de conexión POS" height="100" align="middle" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1784063599/assets/proyecto-verificador-precios/bridge-libp2p/images/plus-icon.svg" alt="Símbolo más" height="32" align="middle" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1767412522/assets/proyecto-verificador-precios/sicar/sicar.svg" alt="Logo de SICAR" height="100" align="middle" />
</p>

## Introducción

`SICAR puente de conexión POS` es una aplicación de escritorio que permite conectar nuestro `Verificador de Precios` con el punto de venta `SICAR®`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470709/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-home.png?v=2" width="720" alt="Vista general del panel principal de SICAR puente de conexión POS">
</p>

## Guía rápida de configuración

Si solo necesita una vista rápida del proceso, siga estos pasos:

1. Instale `SICAR puente de conexión POS` y permita las `conexiones entrantes` cuando `Windows` lo solicite.
2. Abra la aplicación y revise la [conexión al punto de venta](#conexión-al-punto-de-venta).
3. Confirme la carpeta de instalación de `SICAR®`.
4. La aplicación usará los valores predeterminados de conexión e intentará obtener automáticamente la contraseña desde `SICAR®`.
5. Compruebe que la aplicación logre conectarse correctamente al punto de venta.
6. Verifique que la aplicación ya muestre la `URL para conexión del servidor`.
7. Abra el [Asistente de URL de acceso](#paso-2-abrir-el-asistente-de-url-de-acceso) o use el [QR de conexión](#emparejar-con-el-software-verificador-de-precios-usando-el-qr) para [emparejar Verificador de Precios](#emparejar-con-el-software-verificador-de-precios-usando-el-asistente).
8. [Acepte el permiso de acceso a la red local](#paso-5-permitir-el-acceso-a-la-red-local-en-el-navegador).
9. Confirme que `Verificador de Precios` complete la conexión correctamente.

Puede consultar el detalle completo en estas secciones:

- [Instalación](#instalación)
- [Conexión al punto de venta](#conexión-al-punto-de-venta)
- [Emparejar con el software Verificador de Precios usando el Asistente](#emparejar-con-el-software-verificador-de-precios-usando-el-asistente)

## Compatibilidad con sistemas operativos

La aplicación es compatible con el siguiente sistema operativo:

| Sistema operativo | Compatibilidad |
| --- | --- |
| Windows | ✅ |

### Requisitos mínimos del sistema operativo

Esta versión de la aplicación es compatible con:

| Plataforma | Recomendado |
| --- | --- |
| Windows | Windows 10 / 11 |

## Compatibilidad con punto de venta `SICAR®`

- `SICAR® v4`

## Descarga segura

Antes de instalar la aplicación, tenga en cuenta lo siguiente:

- `SICAR puente de conexión POS` es software legítimo y distribuido de forma oficial a través de [nuestro repositorio de GitHub](https://github.com/verificador-precios).
- La aplicación se construye y empaqueta siguiendo prácticas orientadas a la seguridad y a la integridad del software distribuido.
- Descargue el instalador únicamente desde el sitio oficial o desde el repositorio oficial del proyecto.
- No instale archivos descargados desde enlaces de terceros, servicios no oficiales o sitios no verificados.

## Instalación

Importante:

Para que la aplicación funcione correctamente, es necesario aceptar el permiso de `conexiones entrantes` cuando `Windows` lo solicite.

### Instalación en Windows

1. Descargue [la última versión del instalador](https://github.com/verificador-precios/puente-de-conexion-pos-sicar/releases/latest).
2. Abra el archivo descargado.
3. Siga los pasos del asistente de instalación.
4. Al finalizar, abra `SICAR puente de conexión POS`.

Nota: Para instalar la aplicación en `Windows`, **no se requieren permisos de administrador**.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780368340/assets/proyecto-verificador-precios/bridge-libp2p/win-11/windows-11-installer-initial.png?v=2" width="450" alt="Ejemplo del instalador en Windows">
</p>

### Si Windows bloquea el instalador o la aplicación

En algunos equipos, `Windows` puede mostrar advertencias de seguridad al abrir el instalador o la aplicación. Si esto ocurre, puede usar cualquiera de los siguientes métodos.

#### Método 1: Desbloquear desde Propiedades

1. Haga clic derecho sobre el archivo descargado.
2. Seleccione `Propiedades`.
3. En la pestaña `General`, busque la sección `Seguridad`.
4. Marque la casilla `Desbloquear`.
5. Haga clic en `Aplicar`.
6. Haga clic en `Aceptar`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780104704/assets/proyecto-verificador-precios/bridge-libp2p/win-11/win-11-propiedades-instalador.png?v=2" width="420" alt="Ejemplo del desbloqueo del instalador desde Propiedades en Windows 10 y Windows 11">
</p>

#### Método 2: Omitir la advertencia de Windows SmartScreen

1. Haga doble clic en el instalador o en la aplicación.
2. Si aparece la pantalla `Windows protegió su PC`, haga clic en `Más información`.
3. Después, haga clic en `Ejecutar de todas formas`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780033662/assets/proyecto-verificador-precios/bridge-libp2p/win-10/win-10-smartscreen-1.png?v=2" width="420" alt="Ejemplo de Windows SmartScreen en Windows 10">
</p>

### Permitir conexiones entrantes en el firewall de Windows

Después de instalar y abrir la aplicación, `Windows` puede mostrar una alerta del firewall indicando que `SICAR puente de conexión POS` desea comunicarse en la red. Este permiso es necesario para que la aplicación pueda recibir conexiones locales y funcionar correctamente.

Si aparece esta ventana:

1. Verifique que la aplicación corresponda a `SICAR puente de conexión POS`.
2. Haga clic en `Permitir acceso`.
3. Si Windows muestra opciones de red, permita el acceso según la política de su entorno.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780104704/assets/proyecto-verificador-precios/bridge-libp2p/win-11/win-11-firewall-permiso-2.png?v=2" width="420" alt="Solicitud del permiso de firewall para permitir conexiones entrantes en Windows">
</p>

Si desea confirmar después que el permiso quedó aplicado correctamente:

1. Abra `Seguridad de Windows`.
2. Entre a `Firewall y protección de red`.
3. Haga clic en `Permitir una aplicación a través del firewall`.
4. Busque `SICAR puente de conexión POS` en la lista.
5. Verifique que la aplicación aparezca como permitida.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780104704/assets/proyecto-verificador-precios/bridge-libp2p/win-11/win-11-firewall-permiso-1.png?v=2" width="520" alt="Ejemplo de verificación del permiso de firewall en Windows">
</p>

Si el permiso fue rechazado por error:

1. Abra `Seguridad de Windows`.
2. Entre a `Firewall y protección de red`.
3. Haga clic en `Permitir una aplicación a través del firewall`.
4. Busque `SICAR puente de conexión POS`.
5. Marque la aplicación para permitir el acceso.
6. Guarde los cambios y vuelva a abrir la aplicación.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1780033662/assets/proyecto-verificador-precios/bridge-libp2p/win-10/win-10-firewall-2.png?v=2" width="520" alt="Ejemplo de permiso del firewall en Windows 10">
</p>

## Actualización de la aplicación

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470710/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-update-install-content.png?v=2" width="420" alt="Ejemplo del aviso de actualización lista en SICAR puente de conexión POS">
</p>

### Actualización automática

La búsqueda de actualizaciones se ejecuta automáticamente en las versiones empaquetadas e instaladas desde los canales oficiales de publicación.

Flujo esperado:

1. Abra la aplicación.
2. Aproximadamente `15 segundos` después de abrirla, la aplicación buscará una versión nueva en segundo plano.
3. Si existe una actualización disponible, la aplicación comenzará la descarga automáticamente.
4. Cuando la descarga finalice, la aplicación mostrará un aviso indicando que la nueva versión quedó lista para instalarse.
5. Al cerrar la aplicación, se iniciará la instalación de la actualización descargada.

Si aparece el diálogo `Actualización lista`, puede usar `Actualizar ahora` para cerrar la aplicación e iniciar el proceso de actualización en ese momento.

### Plataformas activas con la actualización automática

Actualmente, la actualización automática está activa solo en `Windows`.

Si necesita actualizar manualmente, descargue e instale la versión más reciente publicada para `SICAR puente de conexión POS`.

## Primer uso

Al abrir la aplicación por primera vez, se intentará establecer la conexión con el punto de venta usando la configuración predeterminada de `SICAR®`.

Al iniciar, la aplicación también intentará obtener automáticamente la contraseña del POS `SICAR®`.

Cuando la comunicación con el punto de venta se establezca correctamente, la aplicación mostrará una confirmación.

## Configuración de la aplicación

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470706/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-app-config.png?v=2" width="720" alt="Ejemplo de la pantalla de configuración de la aplicación en SICAR puente de conexión POS">
</p>

### Cómo abrir la configuración

1. Abra `SICAR puente de conexión POS`.
2. Ubique el botón `Configuración de la app`.
3. Haga clic para abrir el panel de configuración.

### Opciones disponibles

#### Comportamiento

En esta sección puede ajustar cómo responde la aplicación al iniciar y al cerrarse.

- `Lanzar aplicación al iniciar`:
  Permite que la aplicación se abra automáticamente al iniciar sesión en el sistema operativo.
- `Confirmar salida de la aplicación`:
  Muestra una confirmación antes de cerrar completamente la aplicación, para evitar detener por accidente la conexión con el punto de venta y los servicios locales.

#### Apariencia y accesibilidad

En esta sección puede adaptar la apariencia visual de la aplicación.

- `Tema visual`:
  Permite cambiar el estilo visual de la interfaz.
- `Reducir movimiento`:
  Disminuye animaciones y transiciones para una experiencia visual más estable.

#### Funciones auxiliares

En esta sección puede activar herramientas adicionales de apoyo.

- `Habilitar regeneración de QR`:
  Permite mostrar y regenerar el `QR de conexión` cuando cambie la `URL para conexión del servidor`.

### Recomendaciones de uso

- Use `Lanzar aplicación al iniciar` si necesita que el servicio esté disponible automáticamente al encender el equipo.
- Mantenga habilitada `Confirmar salida de la aplicación` para evitar cierres accidentales.
- `Reducir movimiento` puede ser útil si el equipo no tiene altas prestaciones para mostrar animaciones.
- Si comparte la conexión con otros dispositivos, conviene mantener habilitada la regeneración del `QR de conexión`.

## Conexión al punto de venta

La aplicación está preparada para conectarse al punto de venta `SICAR®`.

### Valores predeterminados usados por la aplicación

La aplicación usa estos valores predeterminados para acceder a la base de datos:

- `Host`: `127.0.0.1`
- `Puerto`: `3310`
- `Base de datos`: `sicar`
- `Usuario`: `root`
- `Contraseña`: `Se obtiene de manera automática del POS`
- `Carpeta de instalación`: `C:\Program Files (x86)\SICAR`

La contraseña no se captura como un valor fijo dentro de la aplicación. Al iniciar, se intenta obtener automáticamente del POS `SICAR®`.

### Cómo se realiza la lectura de datos

La aplicación se conecta al POS `SICAR®` de la siguiente manera:

1. Usa los datos de conexión configurados para `SICAR®`.
2. Al iniciar, intenta obtener automáticamente la contraseña del POS `SICAR®`.
3. Una vez conectada, realiza consultas de solo lectura sobre la base de datos para validar la conexión y consultar artículos.

Este flujo permite consultar la información del punto de venta sin interrumpir su funcionamiento.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470707/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-db-config-form.png?v=2" width="520" alt="Ejemplo del formulario de conexión de SICAR puente de conexión POS">
</p>

### Cómo ajustar la configuración

1. Abra `SICAR puente de conexión POS`.
2. Revise que la `Carpeta de instalación` apunte a la carpeta donde está instalado `SICAR®`.
3. Confirme que el `Host` sea `127.0.0.1`, salvo que su instalación use otro.
4. Confirme que el `Puerto` sea `3310`, salvo que su instalación use otro.
5. Confirme que la `Base de datos` sea `sicar`, salvo que su instalación use otra.
6. Confirme que el `Usuario` sea `root`, salvo que su instalación use otro.
7. Normalmente no será necesario capturar la `Contraseña`, ya que se obtiene de manera automática del POS.
8. Compruebe la conexión.

### Cuándo ajustar la carpeta de instalación

Ajuste la `Carpeta de instalación` en estos casos:

- Si `SICAR®` fue instalado en una ubicación distinta a `C:\Program Files (x86)\SICAR`
- Si la aplicación no logra obtener automáticamente la contraseña
- Si hubo una reinstalación o migración del punto de venta a otro equipo

### Recomendaciones

- Mantenga abierta la aplicación mientras use `Verificador de Precios`.
- Si la conexión falla, revise la `Carpeta de instalación`, el `Host`, el `Puerto`, la `Base de datos` y el `Usuario`.
- La `Contraseña` normalmente se obtiene de manera automática del POS `SICAR®`.
- Si la contraseña no se obtiene automáticamente, capture manualmente la contraseña configurada en `SICAR®`.

## Emparejar con el software Verificador de Precios usando el Asistente

Una vez que la aplicación esté abierta y conectada, podrá generar la `URL de acceso` para `Verificador de Precios`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783543013/assets/proyecto-verificador-precios/bridge-libp2p/images/emparejar-asistente-red-lan.png?v=2" width="500" alt="Ejemplo del emparejamiento entre Verificador de Precios y el puente de conexión POS usando el asistente">
</p>

### Paso 1: Verificar la URL para conexión del servidor

Confirme que la aplicación ya muestre la `URL para conexión del servidor`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470708/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-home-server-connection-url.png?v=2" width="520" alt="Ejemplo de la URL para conexión del servidor mostrada en la aplicación">
</p>

### Paso 2: Abrir el Asistente de URL de acceso

1. Dentro de la aplicación, ubique la sección de acceso.
2. Haga clic en `Asistente de URL de acceso`.
3. Se abrirá una ventana para capturar la `URL del Verificador de Precios`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470710/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-url-assistant-content.png?v=2" width="520" alt="Ejemplo del Asistente de URL de acceso para configurar Verificador de Precios">
</p>

### Paso 3: Capturar correctamente la URL del Verificador de Precios

En el campo `URL del Verificador de Precios`, capture únicamente la dirección base del sistema web.

Ejemplo:

- `https://sicar.verificador-precios-prueba.com.mx/`

### Paso 4: Guardar y usar la URL de acceso

1. Revise la `Vista previa de la URL de acceso`.
2. Si la vista previa es correcta, haga clic en `Guardar y usar`.
3. Una vez registrada la URL, se habilitarán los botones `Copiar` y `Abrir`.
4. Use `Copiar` para copiar la URL al portapapeles.
5. Use `Abrir` para abrir la URL en el navegador predeterminado.
6. Mediante la URL generada ya podrá acceder al **software Verificador de Precios emparejado a su punto de venta**.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470707/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-home-access-assistant.png?v=2" width="520" alt="Ejemplo de los botones Copiar y Abrir después de registrar la URL del Verificador de Precios">
</p>

### Paso 5: Permitir el acceso a la red local en el navegador

Para una mejor compatibilidad, se recomienda usar el sitio web de `Verificador de Precios` en [Google Chrome](https://www.google.com/intl/es-419/chrome/).

Si abre el sitio web de `Verificador de Precios` en `Google Chrome`, es posible que el navegador solicite permiso para acceder a la `red local`. Acepte este permiso para que el sitio web pueda comunicarse correctamente con la `URL para conexión del servidor`.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783543092/assets/proyecto-verificador-precios/bridge-libp2p/images/chrome-local-network-access-permission.png?v=2" width="540" alt="Ejemplo del permiso de acceso a la red local solicitado por Google Chrome">
</p>

Referencia:
[Private Network Access update: Introducing permission prompts](https://developer.chrome.com/blog/local-network-access?hl=es-419)

## Emparejar con el software Verificador de Precios usando el QR

También puede emparejar `Verificador de Precios` usando el `QR de conexión` que genera la aplicación.

### Paso 1: Verificar que el QR esté disponible

1. Confirme que la aplicación ya muestre la `URL para conexión del servidor`.
2. Ubique la sección `QR de conexión`.
3. Espere a que la aplicación genere el código QR correspondiente.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783470709/assets/proyecto-verificador-precios/bridge-libp2p/sicar/sicar-home-signaling-qr-panel.png?v=2" width="520" alt="Ejemplo de la sección QR de conexión en SICAR puente de conexión POS">
</p>

### Paso 2: Exportar el QR

1. Dentro de la sección `QR de conexión`, haga clic en `Exportar QR`.
2. Guarde la imagen en una ubicación fácil de encontrar.

### Paso 3: Abrir la conexión rápida en Verificador de Precios

1. Abra el software `Verificador de Precios`.
2. Vaya a la sección `Conexión rápida`.
3. Elija una de las opciones disponibles para leer el QR.

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783574760/assets/proyecto-verificador-precios/screenshots/direct-pos-database/sicar-dc-verificador-precios-prueba-com-mx-config-data-source-9999b8dc11.jpg?v=2" width="720" alt="Opciones de conexión rápida por QR en Verificador de Precios">
</p>

### Paso 4: Emparejar usando el QR

Puede usar cualquiera de estas opciones:

- `Usar cámara`:
  Permite escanear el QR directamente con la cámara del dispositivo.
- `Adjuntar archivo`:
  Permite seleccionar la imagen exportada del QR desde el equipo.
- `Usar escáner 2D`:
  Permite leer el QR con un escáner compatible.

### Paso 5: Confirmar la conexión

1. Verifique que `Verificador de Precios` cargue correctamente la `URL para conexión del servidor`.
2. Revise que la URL corresponda al equipo correcto.
3. Si el QR se importó o se escaneó correctamente, la conexión se establecerá de manera automática.
4. Espere la confirmación de emparejamiento.

Si el sitio web no completa la conexión en `Google Chrome`, revise si el navegador mostró el permiso de acceso a la `red local` y acéptelo. Consulte también el [Paso 5: Permitir el acceso a la red local en el navegador](#paso-5-permitir-el-acceso-a-la-red-local-en-el-navegador).

<p align="center">
  <img src="https://res.cloudinary.com/xadani-mexico/image/upload/v1783574761/assets/proyecto-verificador-precios/screenshots/direct-pos-database/sicar-dc-verificador-precios-prueba-com-mx-config-data-source-82cbe2dcad.jpg?v=2" width="720" alt="Ejemplo de Verificador de Precios con la conexión establecida correctamente">
</p>

### Recomendaciones

- Si no se reconoce el QR, exporte nuevamente la imagen y repita el proceso.
- Si usa `Adjuntar archivo`, asegúrese de seleccionar el QR más reciente.
- Si la conexión no se completa, confirme que la aplicación siga abierta y que la `URL para conexión del servidor` continúe disponible.

## Solución de problemas

Si la aplicación no funciona como esperaba, revise estos casos comunes:

### La aplicación no conecta al punto de venta

- Verifique que la `Carpeta de instalación` corresponda a la ubicación real de `SICAR®`.
- Confirme que el `Host`, el `Puerto`, la `Base de datos` y el `Usuario` sean correctos.
- La `Contraseña` normalmente se obtiene de manera automática del POS `SICAR®`.
- Si la contraseña no se obtuvo automáticamente, capture manualmente la contraseña configurada en `SICAR®`.
- Verifique que el servicio de base de datos de `SICAR®` esté disponible.

### No aparece la URL para conexión del servidor

- Confirme que la aplicación siga abierta.
- Revise que la conexión al punto de venta se haya completado correctamente.
- Si hubo cambios recientes en la red o en la configuración, cierre y vuelva a abrir la aplicación.
- Verifique que el firewall haya permitido las `conexiones entrantes`.

### El Verificador de Precios no se empareja

- Revise que la `URL para conexión del servidor` corresponda al equipo correcto.
- Si usa el asistente, confirme que la `URL del Verificador de Precios` esté bien escrita.
- Si usa QR, vuelva a exportar la imagen e inténtelo nuevamente.
- Confirme que la aplicación de escritorio siga abierta al momento de emparejar.

### El QR no se reconoce

- Genere nuevamente el QR desde la aplicación.
- Si usa `Adjuntar archivo`, asegúrese de seleccionar la imagen correcta.
- Si usa cámara o escáner, procure que el código QR esté nítido y completamente visible.

## Desinstalación

### Desinstalación en Windows

Para desinstalar la aplicación en `Windows`:

1. Abra `Configuración`.
2. Entre a `Aplicaciones`.
3. Busque `SICAR puente de conexión POS`.
4. Haga clic en `Desinstalar`.
5. Siga los pasos del asistente.

## Disclaimer

`SICAR®` y todos sus logotipos son marcas registradas de **sicar.mx**