# UD1 A1. Lenguajes de Marcas

## 1. ¿Qué es un lenguaje de marcas?
Un lenguaje de marcas es un sistema para etiquetar elementos dentro de un documento, estructurando la información para definir la presentación, el formato o la relación de los datos. Estos lenguajes suelen usarse para representar datos de manera que sean comprensibles tanto para humanos como para máquinas.

## 2. Características generales de los lenguajes de marcas:
- Utilizan etiquetas o marcas para estructurar y definir la información.
- Son independientes del sistema operativo y la plataforma.
- Son legibles tanto por humanos como por máquinas.
- Facilitan la interoperabilidad y el intercambio de datos entre sistemas.
- Se suelen escribir en formato texto plano, lo que los hace fácilmente editables.

## 3. Clasificación de los lenguajes de marcas más relevantes:

- **Lenguajes de marcas de presentación**:  
  Son utilizados principalmente para definir la apariencia de un documento.  
  Ejemplo: **HTML** (HyperText Markup Language).

- **Lenguajes de marcas de descripción de datos**:  
  Estos lenguajes sirven para describir datos en un formato estructurado.  
  Ejemplo: **XML** (eXtensible Markup Language), **KML** (Keyhole Markup Language).

- **Lenguajes de marcas de intercambio de información**:  
  Se utilizan para intercambiar datos entre diferentes sistemas.  
  Ejemplo: **RSS** (Really Simple Syndication), **iCalendar**, **vCard**.

## 4. Ámbitos de aplicación de los lenguajes de marcas:

- **Web y desarrollo de aplicaciones**: HTML se utiliza para la creación de páginas web.
- **Intercambio de información**: RSS, iCalendar y vCard permiten compartir información como eventos, contactos y noticias entre diferentes plataformas.
- **Geoposicionamiento**: KML se emplea para mostrar información geoespacial, siendo usado en herramientas como Google Earth.

## 5. Trozos de código y explicación de los lenguajes de marcas:

### 1. HTML (HyperText Markup Language)
HTML es el lenguaje estándar utilizado para crear páginas web y aplicaciones web.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de HTML</title>
</head>
<body>
    <h1>Bienvenido a mi página</h1>
    <p>Este es un ejemplo básico de HTML.</p>
</body>
</html>
```
**Aplicación**: Navegadores web como Google Chrome o Firefox procesan y muestran este tipo de archivos.


## 2. iCalendar (.ics)

iCalendar es un formato de archivo que permite intercambiar información de calendario.

```
BEGIN:VCALENDAR
VERSION:2.0
PRODID:-//Mi Aplicación//iCalendar 1.0//ES
BEGIN:VEVENT
UID:uid1@example.com
DTSTAMP:20231010T120000Z
DTSTART:20231012T090000Z
DTEND:20231012T100000Z
SUMMARY:Reunión con equipo
END:VEVENT
END:VCALENDAR
```
**Aplicación**: Los calendarios electrónicos como Google Calendar o Microsoft Outlook utilizan este formato para gestionar eventos.

## 3. vCard (Virtual Contact File)

vCard es un formato estándar para compartir información de contacto.

```
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
ORG:Mi Empresa
TEL;TYPE=WORK,VOICE:(111) 555-1212
ADR;TYPE=WORK:;;123 Calle Principal;Ciudad;Provincia;12345;País
EMAIL:juan.perez@ejemplo.com
END:VCARD
```
**Aplicación**: Aplicaciones como los contactos de un teléfono móvil o CRM utilizan este formato para guardar y compartir contactos.

## 4. KML (Keyhole Markup Language)

KML es un lenguaje utilizado para representar datos geoespaciales.

```
<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Ubicación Ejemplo</name>
    <Point>
      <coordinates>-122.0822035425683,37.42228990140251,0</coordinates>
    </Point>
  </Placemark>
</kml>
```

**Aplicación**: Herramientas de mapas como Google Earth o Google Maps procesan estos archivos para mostrar ubicaciones geográficas.

## 5. RSS (Really Simple Syndication)

RSS es un formato que permite distribuir contenido actualizado, como artículos o noticias.

```RSS
<?xml version="1.0" encoding="UTF-8" ?>
<rss version="2.0">
  <channel>
    <title>Mi Blog</title>
    <link>http://www.miblog.com</link>
    <description>Últimas noticias de mi blog</description>
    <item>
      <title>Nuevo Artículo</title>
      <link>http://www.miblog.com/articulo-nuevo</link>
      <description>Este es un nuevo artículo en mi blog.</description>
      <pubDate>Wed, 01 Oct 2024 10:00:00 +0000</pubDate>
    </item>
  </channel>
</rss>
```

**Aplicación**: Lectoras de feeds como Feedly o aplicaciones de gestión de noticias utilizan este formato para mostrar contenido actualizado.




