# Laboratorio abierto · Dispositivos experimentales impresos en 3D

Repositorio complementario del manuscrito *Péndulos, imanes y pájaros carpinteros: dispositivos impresos en 3D para enseñar dinámica no lineal*.

🌐 **Sitio web:** https://msilva-32.github.io/dispositivos-3d-sistemas-dinamicos-nolineales/

## Dispositivos y materiales disponibles

| Dispositivo | Documentación técnica | Modelo de referencia |
| --- | --- | --- |
| Péndulo magnético | Base hexagonal con 36 posiciones de alojamiento; 6 imanes de ferrita; mástil de 200 mm | [Chaotic Pendulum · Printables](https://www.printables.com/model/459578-chaotic-pendulum) |
| Pájaro carpintero | Piezas impresas en PLA; resortes de 40 mm con perfiles distintos; regulación de inclinación | [Modelo G6033465 · Nexprint](https://www.nexprint.com/en/models/G6033465?printConfigId=G9424662) |
| Péndulo doble | Brazos de 160 y 130 mm; 2 rodamientos 608 por péndulo; abrazaderas tipo C | [3D Printing Chaos · Lanv3r](https://github.com/Lanv3r/chaos-theory-3d-printing/tree/main/double_pendulum) |

Los archivos de impresión y la guía de ensamblaje se encuentran en [docs/descargas](docs/descargas). Las fotografías y los modelos digitales figuran en [docs/img](docs/img). La web está construida en [docs/index.html](docs/index.html), con estilos en [docs/styles.css](docs/styles.css).

## Fabricación

- **Impresora:** Bambu Lab A1 mini.
- **Tecnología y material:** FDM y filamento PLA.
- **Preparación:** Bambu Studio, con parámetros predeterminados del perfil de impresión seleccionado.
- **Adaptaciones:** recortes, incorporación de elementos geométricos y ajustes dimensionales en Tinkercad; diseño de piezas originales en OpenSCAD.
- **Montaje:** inspección de defectos y encastres; comprobación del movimiento tras ensamblar cada dispositivo.

Los parámetros específicos de laminado deben verificarse con registros de impresión o archivos de proyecto. No se atribuyen valores de relleno, temperatura u orientación que no se hayan documentado.

## Procedencia, créditos y permisos

Los modelos originales fueron creados por terceros. Este proyecto utiliza versiones adaptadas para una propuesta de enseñanza experimental. Se indican sus fuentes originales en la tabla anterior y en el sitio web.

**Revisión pendiente:** confirmar la atribución y la licencia del diseño de Printables y de Nexprint; consultar las condiciones de reutilización del diseño de Lanv3r, cuyo repositorio no presenta un archivo de licencia explícito. Publicar archivos bajo una licencia nueva requiere respetar los derechos de los autores originales. Hasta verificar esos permisos, las declaraciones generales del archivo `LICENSE` **no deben interpretarse como una autorización sobre modelos de terceros**.

## Revisiones técnicas pendientes

1. Contrastar los STL finales con las cantidades de piezas y las dimensiones incluidas en el manuscrito.
2. Actualizar la guía PDF para que describa los montajes finales.
3. Confirmar permisos y licencias de origen antes de difundir versiones derivadas con licencia propia.
4. Sustituir o retirar el archivo `editables/pendulo-imanes.step` si no contiene un modelo editable válido.
5. Incorporar archivos de proyecto `.3mf` y diseños editables cuando estén disponibles.

## Estado de este rediseño

La rama `redisenio-apfu-v2-20261109` presenta una propuesta de diseño del sitio para revisión. El contenido de `main` permanece sin cambios hasta aprobar su incorporación.
