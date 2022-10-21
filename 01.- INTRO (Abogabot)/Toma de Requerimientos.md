# Toma de Requerimientos

Un despacho de abogados se ha puesto en contacto solicitando el diseño de una aplicación web para la atención de sus clientes.

De manera general lo que necesitan es:

## Objetivo
Automatizar las solicitudes de los clientes del despacho, logrando la digitalización del proceso de gestión de las demandas.

## Características generales de la aplicación
- Se trata de una aplicación con diseño responsive para poder ser visualizada tanto en versión Desktop como Móvil.
- Debe contener una pantalla para el inicio de sesión y creación de cuenta nueva. Esta pantalla es para el usuario y para el administrador.
- Debe contener un formulario con los datos necesarios para que el usuario proporciones toda la información y detalles de su demanda.
- Debe contener una página para montar la pasarela de pagos para que el uuario procese el pago de su demanda con el método que prefiera.
- Debe contener un panel de control que permita conectar al administrador y al usuario, brindando un lugar determinado para la actualización de los casos.

### Identidad
No se ha compartido un logotipo, tampoco ningún detalle relacionado con el tema del diseño gráfico o de identidad. El único detalle proporcionado por el cliente ha sido la preferencia de colores. Aún así se encuentra abierto a sugerencias.
- **Colores**: Azul marino y blanco.

## Funcionamiento general de la aplicación
El flujo de funcionamiento de la aplicación debe mantenerse lo más simple posible.
### Usuario
1. Inicia sesión. (***Si no tiene un cuenta debe crearla***)
2. Selecciona la opción de crear nuevo caso.
3. Llena el formulario con todos los datos de su caso.
4. Hace clic en **"Enviar Formulario"**.
5. Es redirigido a la pasarela de pagos y selecciona el de su preferencia.
6. Luego de procesar su pago recibe un comprobante y un número de folio o seguimiento de caso. (***El comprobante y el folio, así como cada actualización del caso, serán recibidos en el correo electrónico del usuario***)
7. El usuario puede seleccionar el panel de control (o seguimiento de caso) para ver todas las actualizaciones de su caso, responder solicitudes del administrador o agregar peticiones que sean pertinentes para cada caso.
### Administrador
1. Inicia sesión.
2. Ingresa al panel de control.
3. Encuentra todos los casos activos y selecciona el que es de su interés. También puede ingresar desde las notificaciones, pues cada nuevo caso genera una notificación en el perfil del administrador.
4. Puede ver el documento word generado automáticamente con los datos que el usuario ingresó en el formulario.
5. Puede agregar actualizaciones, comentarios o solicitudes adicionales para el usuario, según el progreso del caso.
