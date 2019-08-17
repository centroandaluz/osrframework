OSRFramework
============

OSRFramework: Marco de investigación de fuentes abiertas

Copyright (C) 2014-2018 F. Brezo e Y. Rubio, i3visio

[! [Versión en PyPI] (https://img.shields.io/pypi/v/osrframework.svg)] ()
[! [Licencia] (https://img.shields.io/badge/license-GNU%20Affero%20General%20Public%20License%20Version%203%20or%20Later-blue.svg)] ()

1 - Descripción
---------------

OSRFramework es un conjunto de bibliotecas GNU AGPLv3 + desarrollado por i3visio para realizar
Tareas de inteligencia de código abierto. Incluyen referencias a un montón de diferentes
aplicaciones relacionadas con la verificación de nombre de usuario, búsquedas de DNS, fugas de información
investigación, búsqueda en la web profunda, extracción de expresiones regulares y muchos otros.
Al mismo tiempo, mediante transformaciones ad-hoc de Maltego, OSRFramework proporciona
una forma de hacer estas consultas, interactuar con OSRFConsole o una interfaz web.

2 - Licencia: GNU AGPLv3 +
------------------------

Este es un software gratuito y puede redistribuirlo bajo ciertas
condiciones.

Este programa es software libre: puede redistribuirlo y / o modificarlo
bajo los términos de la Licencia Pública General GNU publicada por
Free Software Foundation, o la versión 3 de la Licencia, o
(a su elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil,
pero CON CUALQUIER GARANTÍA; sin siquiera la garantía implícita de
COMERCIABILIDAD o APTITUD PARA UN PROPÓSITO EN PARTICULAR. Ver el
GNU Affero General Public License para más detalles.

Debería haber recibido una copia de la GNU Affero General Public License
junto con este programa. Si no, vea <http://www.gnu.org/licenses/>.


Para obtener más detalles sobre este problema, consulte el archivo [COPIANDO] (COPIANDO).

3 - Instalación
----------------

Forma rápida de hacerlo en cualquier sistema para un usuario con administración privilegiada:
`` `
pip2 instalar osrframework
`` `
Puede actualizar a la última versión del marco con:
`` `
pip2 install osrframework --upgrade
`` `
Esta versión de la última versión de
El marco.

Si necesita más información sobre cómo instalar OSRFramework en ciertos
sistemas, tenga en cuenta que es posible que deba agregar `PATH = $ PATH: $ HOME / .local / bin` a
su `~ / .bashrc_profile`). Esto ha sido confirmado en algunas distribuciones,
incluyendo MacOS En cualquier caso, le recomendamos que eche un vistazo a
[INSTALL.MD] (doc / INSTALL.MD) donde proporcionamos detalles adicionales para estos
cajas.

4 - Uso básico
---------------

Si todo salió correctamente (¡eso esperamos!), Es hora de probar usufy.py,
mailfy.py y así sucesivamente. Pero nosotros somos ellos? Se instalan en tu camino
que puedes abrir el terminal y escribir el nombre del programa (parece
ser una mejora de instalaciones anteriores ...). ejemplos:
`` `
osrf --help
usufy -n i3visio febrezo yrubiosec -p twitter facebook
searchfy -q "i3visio"
mailfy -n i3visio
`` `

Escriba -h o --help para obtener más información sobre cuáles son los parámetros de cada
aplicación.

Puede encontrar los archivos de configuración en una carpeta creada en la página de inicio de su usuario
define el comportamiento predeterminado de las aplicaciones:
`` `
# Archivos de configuración para Linux y MacOS
~ / .Config / OSRFramework /
# Archivos de configuración para Windows
C: \ Users \ <usuario> \ OSRFramework \
`` `

OSRFramework buscará los ajustes de configuración almacenados allí. Puedes agregar
nuevas credenciales allí y si algo sale mal, siempre puede restaurar el
archivos almacenados en la subcarpeta `por defecto`.

Si tienes problemas,
(Sección de preguntas frecuentes) [doc / FAQ.md].

5 - HACKING
-----------

Si desea ampliar las funcionalidades de OSRFramework y no sabe
desde dónde comenzar, verifique el archivo [HACKING.md] (doc / HACKING.md).

6 - AUTORES
-----------

[AUTHORS.md] (AUTHORS.md) archivo.
