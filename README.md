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

Para evitar que los menús aparezcan duplicados (en Inglés y Español), este paquete debe **reemplazar** al paquete por defecto. Para ello, **la carpeta donde se instalen estos archivos DEBE llamarse `Default`**.

#### Opción A: Usando Git (Recomendado)
Dentro de la carpeta `Packages` abierta en el paso anterior, abra una terminal o consola y ejecute:
```bash
git clone https://github.com/su-usuario/sublime-merge-spanish.git "Default"
```

#### Opción B: Descarga manual
1. Descargue este repositorio como un archivo ZIP.
2. Descomprima el contenido.
3. Renombre la carpeta descomprimida a `Default`.
4. Mueva la carpeta `Default` dentro de la carpeta `Packages`.

> [!WARNING]
> Si ya tiene una carpeta `Default` en `Packages` (que no es común a menos que la haya creado usted), haga una copia de seguridad antes de reemplazarla.

### 3. Verificar la instalación
Una vez que la carpeta `Default` esté en su lugar, reinicie Sublime Merge. Los menús en inglés deberían desaparecer y ser reemplazados por los de español.

## Notas de la traducción
- **Stage** se ha traducido como **Preparar** (o **Poner en el índice**).
- **Stash** se ha traducido como **Resguardo** o **Stash**.
- Se han mantenido términos técnicos comunes como **Checkout**, **Push**, **Pull**, **Fetch**, **Merge** y **Rebase** entre paréntesis o en su forma original cuando es estándar en la industria.
- **Nota sobre Tooltips:** La información emergente (al pasar el mouse sobre un commit) es parte del núcleo de Sublime Merge y actualmente no es posible traducirla mediante archivos de configuración.

## Contribuciones

Si encuentra algún error o desea mejorar la traducción, no dude en abrir un issue o enviar un pull request.
