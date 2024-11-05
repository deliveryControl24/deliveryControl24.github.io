# Sistema de Registro y Facturación de Pedidos

Este proyecto es un sistema de registro y facturación de pedidos diseñado para ser utilizado en dispositivos Android y PC. Permite a los usuarios gestionar pedidos y motorizados de manera eficiente, con la opción de exportar e importar sus datos.

## Características

- Registro de pedidos con detalles como lugar de entrega, número de cliente, efectivo y motorizado asignado.
- Gestión de motorizados, permitiendo agregar o eliminar motorizados según sea necesario.
- Exportación de datos a un archivo JSON para guardar información de pedidos y motorizados.
- Importación de datos desde un archivo JSON para restaurar información previamente guardada.
- Generación de vouchers en formato PDF o JPG para los pedidos seleccionados.
- Cálculo de ganancias diarias y tarifas.

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, etc.) en PC o Android.

## Cómo Usar

1. **Clonar el Repositorio**:
   Para clonar el repositorio, usa el siguiente comando en tu terminal:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```

2. **Abrir la Aplicación**:
   Abre el archivo `index.html` en tu navegador. Si estás utilizando un dispositivo Android, puedes abrirlo en el navegador web.

3. **Registrar Pedidos**:
   Completa el formulario de registro de pedidos e incluye todos los detalles requeridos. Haz clic en "Añadir Pedido" para guardar el pedido.

4. **Agregar Motorizados**:
   Utiliza el formulario para añadir nuevos motorizados. Asegúrate de que el nombre del motorizado no esté duplicado.

5. **Exportar Datos**:
   Para exportar tus datos, haz clic en el botón "Exportar Datos". Esto descargará un archivo `datos.json` que contiene todos tus pedidos y motorizados.

6. **Cargar Datos**:
   Si deseas restaurar tus datos desde un archivo, selecciona el archivo `datos.json` que guardaste anteriormente y haz clic en "Cargar Datos". Esto actualizará la aplicación con tus datos.

7. **Generar Vouchers**:
   Selecciona un pedido del menú desplegable y elige el formato (PDF o JPG) para guardar el voucher correspondiente.

8. **Calcular Ganancias**:
   Puedes calcular las ganancias del día y las tarifas utilizando los botones correspondientes.

## Limitaciones

- La información se guarda en `localStorage`,
