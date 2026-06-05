# elegance_transfers-
sistema de vouchers online 
Sistema de Gestión: Elegance Transfers
Este sistema web está diseñado para la gestión, generación y firma digital de vouchers de servicios de transporte. Permite a los choferes registrar viajes, calcular importes automáticamente y obtener la firma del pasajero en tiempo real.

🚀 Funcionalidades Principales
1. Gestión de Vouchers (Generación y Edición)
Generador de Vouchers: Creación rápida de documentos de viaje con campos predefinidos (Empresa, Pasajero, Origen, Destino, etc.).

Cálculo Automático: El sistema calcula automáticamente los importes basándose en kilómetros recorridos y tiempo de espera, utilizando precios configurables.

Modos de Visualización:

Modo Pro: Acceso total a todas las herramientas, edición de precios y carga de datos.

Modo Usuario (Estándar): Interfaz simplificada enfocada en la carga y generación, con precios bloqueados para evitar errores.

Modo Pasajero: Vista de lectura y firma, oculta todas las funciones administrativas.

2. Firma Digital y Validación
Captura de Firma: Panel táctil integrado para que el pasajero firme directamente sobre la pantalla del dispositivo.

Seguridad: Una vez firmada y aceptada, la firma queda bloqueada para asegurar la integridad del documento.

3. Integración y Automatización
Envío a Telegram: Al finalizar el voucher, los datos se envían automáticamente a un canal/chat de Telegram (vía Bot API) con un resumen del viaje y un archivo JSON adjunto.

Compartir vía WhatsApp: Permite generar un enlace personalizado con todos los datos precargados para enviarlo directamente al pasajero.

Exportación/Importación: Capacidad de importar archivos .json para recuperar viajes anteriores o retomar la carga de datos.

4. Administración y Respaldo
Historial Local: Almacena los últimos 30 vouchers generados en la memoria del navegador para consultas rápidas sin necesidad de internet.

Configuración por Chofer: El sistema detecta y asigna el móvil/chofer según la configuración inicial, manteniendo un número secuencial de voucher único para cada uno.

🛠 Instrucciones de Uso
Carga: Completa los datos en la pantalla principal. Los valores de "Precio KM" y "Precio Hora" se cargan automáticamente desde el sistema o pueden ser ajustados si tienes permisos de Administrador (Modo Pro).

Vista Previa: Presiona "Generar Vista de Boleta" para revisar los cálculos y verificar que todo esté correcto antes de la firma.

Firma: Pídele al pasajero que firme en el recuadro indicado.

Finalización: Haz clic en "Aceptar y Enviar". Esto enviará el reporte a Telegram y habilitará la opción de "Guardar como PDF" para el registro contable.

Limpiar: Al finalizar, el botón "Terminar y Limpiar Planilla" resetea el formulario para el siguiente viaje, manteniendo la secuencia numérica del voucher.
