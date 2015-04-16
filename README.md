1. Package Control
Básicamente es el padre de todos, es el que nos permite gestionar la instalación, desinstalación y muchas más cosas, de cualquier plugin, de forma rápida e intuitiva.

https://packagecontrol.io/installation

import urllib2,os,hashlib; h = 'eb2297e1a458f27d836c04bb0cbaf282' + 'd0e7a3098092775ccb37ca9d6b2e4b7d'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler()) ); by = urllib2.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); open( os.path.join( ipp, pf), 'wb' ).write(by) if dh == h else None; print('Error validating download (got %s instead of %s), please try manual install' % (dh, h) if dh != h else 'Please restart Sublime Text to finish installation')

2. ColorPicker y Color Highlighter
Super útil para CSS, con CMD+MAY+C nos abre el color picker propio del sistema operativo, sin más.

https://github.com/weslly/ColorPicker

3. Emmet 
Como Prince, “el artista antes conocido como Zen-Coding” va a hacer que se nos olvide escribir html, este plugin completa el código de todo lo que te puedas imaginar, mediante introducción de unas pocas letras.
Pero no sólo eso, sino que a través de determinados comandos, podemos escribir toda una estructura de capas, en una línea.
Os voy a poner algunos ejemplos pero os aconsejo que os echéis un vistazo donde tenéis todo, todo, todo lo que hace. Es alucinante.

MUY IMPORTANTE: si el documento no está guardado con la extensión correspondiente a cualquier sintaxis html, NO FUNCIONA.

–	Crear el documento html: Escribimos html:5 y dando tabulador ( a partir de ahora +Tab), nos genera toda la estructura básica de un HTML5.

http://emmet.io/download/

4. Search Stack Overflow
¿Cuántas veces has terminado encontrando la solución a tu problema en Stack Overflow?? Pues busca directamente ahí y no te marees… este magnífico plugin permite buscar directamente en Stack Overflow desde el editor, y abre el navegador en los resultados de búsqueda.

Lo puedes hacer de dos formas;
–	Seleccionas el texto a buscar -> botón derecho, “Stack overflow Search”.

5.GIST y Git
Integracion de git
