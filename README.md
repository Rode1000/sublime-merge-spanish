# Traducción al Español para Sublime Merge

Este paquete traduce y adapta la interfaz de Sublime Merge al idioma español.

## Características

- Traduce los menús principales y de contexto.
- Traduce la paleta de comandos.
- Mantiene la compatibilidad con las funciones originales.

## Instrucciones de Instalación

Para instalar este paquete de traducción, debe colocar los archivos en la carpeta de paquetes de Sublime Merge de su sistema operativo.

### 1. Localizar la carpeta de paquetes

Abra Sublime Merge y vaya a:
`Preferences` (Preferencias) > `Browse Packages...` (Explorar paquetes...)

Esto abrirá el explorador de archivos en la ubicación correcta.

Alternativamente, puede ir directamente a las siguientes rutas:

- **Windows:** `%APPDATA%\Sublime Merge\Packages`
- **macOS:** `~/Library/Application Support/Sublime Merge/Packages`
- **Linux:** `~/.config/sublime-merge/Packages`

### 2. Instalar el paquete

Hay dos formas de hacerlo:

#### Opción A: Usando Git (Recomendado)
Dentro de la carpeta `Packages` abierta en el paso anterior, abra una terminal o consola y ejecute:
```bash
git clone https://github.com/su-usuario/sublime-merge-spanish.git "Spanish Translation"
```

#### Opción B: Descarga manual
1. Descargue este repositorio como un archivo ZIP.
2. Descomprima el contenido en una nueva carpeta llamada `Spanish Translation` dentro de la carpeta `Packages`.

### 3. Verificar la instalación
Una vez que los archivos estén en la carpeta `Spanish Translation`, Sublime Merge debería cargar la traducción automáticamente. No es necesario reiniciar la aplicación, aunque se recomienda hacerlo si no ve los cambios de inmediato.

## Notas de la traducción
- **Stage** se ha traducido como **Preparar** (o **Poner en el índice**).
- **Stash** se ha traducido como **Resguardo** o **Stash**.
- Se han mantenido términos técnicos comunes como **Checkout**, **Push**, **Pull**, **Fetch**, **Merge** y **Rebase** entre paréntesis o en su forma original cuando es estándar en la industria.

## Contribuciones

Si encuentra algún error o desea mejorar la traducción, no dude en abrir un issue o enviar un pull request.
