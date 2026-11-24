# Tickia — actualizaciones para Windows

Repositorio de distribución de instaladores Windows x64 y manifiestos de actualización de Tickia.

Las versiones publicadas estarán disponibles en [Releases](https://github.com/Josevil75/tickia-updates/releases).

## Instalación inicial del canal

Instala el paquete sobre la instalación existente, sin desinstalar ni borrar datos. Actualiza primero el servidor y después los puestos Windows. Las versiones siguientes se podrán descargar automáticamente e instalar al salir desde Tickia, cuando las operaciones pendientes estén confirmadas y se haya verificado la copia de seguridad del servidor.

## Archivos de cada versión

- `Tickia-<version>-x64-setup.exe`: instalador Windows x64.
- `Tickia-<version>-x64-setup.exe.sig`: firma del actualizador Tauri.
- `latest.json`: versión, dirección de descarga y firma que comprueba Tickia.

La firma del actualizador permite verificar el origen y la integridad del paquete. La disponibilidad de firma comercial Authenticode se indica en las notas de cada versión.

Android se distribuye por separado.
