<p align="center"><img src="brand/astrim_access_logo.png" alt="ASTRIM ACCESS" width="220"></p>

# ASTRIM ACCESS

**Cada placa, reconocida. Cada ingreso, confirmado.**

Control de acceso vehicular para **conjuntos residenciales**, de **ASTRIM**. Convierte un teléfono **Android** en la portería vehicular: reconoce las placas colombianas con la cámara, en el propio teléfono y **sin conexión a Internet**, y el vigilante confirma cada ingreso.

👉 Página oficial: <https://astrim-web.web.app/productos/astrim-access>

## ¿Cómo obtenerla?

ASTRIM ACCESS **no tiene descarga pública**. Cada instalación se entrega con su licencia para un conjunto residencial y con acompañamiento de ASTRIM.

1. **Contáctanos:** cuéntanos cómo es tu conjunto (torres o casas, vehículos, porterías).
2. **Demostración y licencia:** te mostramos la app y acordamos la licencia de uso.
3. **Entrega e instalación:** recibes la APK oficial firmada por ASTRIM y te acompañamos en la instalación y la carga de datos.

| Vía | |
|---|---|
| WhatsApp | [+57 301 523 2103](https://wa.me/573015232103?text=Hola%20ASTRIM%2C%20quiero%20informaci%C3%B3n%20para%20adquirir%20ASTRIM%20ACCESS%20para%20mi%20conjunto%20residencial.) |
| Formulario | <https://astrim-web.web.app/contacto?producto=ASTRIM%20ACCESS> |

## Qué hace

- **Reconocimiento automático de placas (ANPR)** en video continuo: carros (ABC123) y motos de una y de dos filas.
- **Lectura por consenso** entre varios fotogramas. Nunca inventa caracteres; ante la duda pide verificación.
- **Verificación de letras confundibles** (D, O, Q) y corrección de confusiones como O/0, B/8, S/5, I/1 y Z/2.
- **Resultado inmediato** con color, ícono, texto y sonido: AUTORIZADO, AUTORIZADO TEMPORAL, SUSPENDIDO, NO REGISTRADO o VERIFICAR.
- **Decide una persona:** el vigilante confirma cada ingreso con su turno y su PIN.
- **Visitantes** con autorización temporal de 1 a 24 horas, por torre o casa y apartamento, con buscador.
- **Operadores** con código y PIN individual, roles (vigilante y administrador), turnos y bloqueo progresivo ante PIN incorrectos.
- **Historial y auditoría:** línea de tiempo por día; un ingreso nunca se confunde con una consulta; cada acción queda a nombre de quien la hizo.
- **Importación** de torres, apartamentos y vehículos desde Excel (`.xlsx`) o CSV, con vista previa y detección de duplicados.
- **Respaldos cifrados** con contraseña y verificación SHA-256; restauración guiada.
- **Alertas sonoras** configurables, incluso con el teléfono en silencio.

## Seguridad y privacidad

- Base de datos **cifrada** (ChaCha20-Poly1305) con la clave en el almacén seguro de Android.
- PIN guardados como huella **PBKDF2-HMAC-SHA256** con sal única; nunca en claro.
- La versión de producción **no tiene permiso de Internet**: los datos del conjunto no salen del teléfono.
- Único permiso solicitado: **la cámara**. No guarda fotografías.
- Copia automática de Android desactivada; los respaldos se hacen a mano y cifrados.

## Requisitos

- Android 7.0 o superior.
- Procesador de 64 bits (ARM64); hay versión de 32 bits.
- Cámara trasera con enfoque automático.
- 300 MB libres. No necesita Internet.

---

ASTRIM ACCESS es **software propietario**. Este repositorio solo contiene información del producto: el código fuente y los instaladores no son públicos. Uso sujeto a [LICENCIA.txt](LICENCIA.txt).

© 2026 ASTRIM. Todos los derechos reservados. · <https://astrim-web.web.app/>
