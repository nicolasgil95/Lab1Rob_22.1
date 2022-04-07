# Laboratorio 1 - Parte 2: Introducción ROS
<p><strong>Integrantes: &nbsp;</strong></p>
<p style="text-align: center;"><span data-contrast="auto">Jhon Brandol Mu&ntilde;oz Romero</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}">&nbsp;</span></p>
<p style="text-align: center;"><span data-contrast="auto">Nicolas Gil</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}">&nbsp;</span></p>
<h2><strong>Introducci&oacute;n</strong></h2>
<p><span data-contrast="auto" xml:lang="ES-ES" lang="ES-ES" class="TextRun SCXW158323604 BCX0"><span class="NormalTextRun SCXW158323604 BCX0">En el siguiente documento, se mostrar&aacute; la metodolog&iacute;a que se utilizaron para realizar la conexi&oacute;n de los nodos de ROS (</span><span class="NormalTextRun SpellingErrorV2 SCXW158323604 BCX0">Rootic</span><span class="NormalTextRun SCXW158323604 BCX0"> Operative </span><span class="NormalTextRun SpellingErrorV2 SCXW158323604 BCX0">System</span><span class="NormalTextRun SCXW158323604 BCX0">) con Matlab, as&iacute; que, se introduce de manera sencilla el funcionamiento de cada uno de los comandos, servicios y t&oacute;pico que se debe implementar. </span></span><span class="EOP SCXW158323604 BCX0" data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}">&nbsp;</span></p>
<h2><strong></strong></h2>




<h2><strong>Metodologı́a</strong></h2>
<ul>
<li><strong>Conexi&oacute;n de ROS con Matlab:</strong><br /><br /></li>
</ul>
<p>Procedimiento<strong>:</strong></p>
<p><strong></strong></p>
<ul>
  
  
  
  
  
  
<li><strong>Utilizando Python: </strong></li>
</ul>
<p>Procedimiento<strong>:<br /></strong>Se crear en un script de Python en el paquete hello turtle de ROS en la carpeta de scripts con el nombre myTeleopKey.py , el cual fue edictado en Visual estudio code.<strong></strong></p>
<p>&nbsp;</p>
<a href="https://ibb.co/80r83Xj"><img src="https://i.ibb.co/1Lr2Vb9/scri.png" alt="scri" border="0"></a>

<p><span data-contrast="auto">Por lo tanto, se escribe el c&oacute;digo para que la tortuga del paquete turtlesim se mueva con el teclado, dado esto, se realiza las siguientes especificaciones:</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}">&nbsp;</span></p>
<ul>
<li><span data-contrast="auto"> Se debe mover hacia adelante y hacia atr&aacute;s con las teclas W y S</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}"></span></li>
<li><span data-contrast="auto"> Debe girar en sentido horario y antihorario con las teclas D y A.</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}"></span></li>
<li><span data-contrast="auto"> Debe retornar a su posici&oacute;n y orientaci&oacute;n centrales con la tecla R</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}"></span></li>
<li><span data-contrast="auto"> Debe dar un giro de 180&deg; con la tecla ESPACIO</span><span data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}"></span></li>
</ul>

<p></p>
<p style="text-align: justify;"><span data-contrast="auto" xml:lang="ES-ES" lang="ES-ES" class="TextRun SCXW9434875 BCX0"><span class="NormalTextRun SCXW9434875 BCX0">Primero, se lograr detectar las teclas que son presionadas, as&iacute; que, se importa el m&eacute;todo </span><span class="NormalTextRun SpellingErrorV2 SCXW9434875 BCX0">termios</span><span class="NormalTextRun SCXW9434875 BCX0"> de </span><span class="NormalTextRun SpellingErrorV2 SCXW9434875 BCX0">python</span><span class="NormalTextRun SCXW9434875 BCX0">, ya que, se presentaban algunos problemas en Linux con alguna librer&iacute;a.</span></span><span data-contrast="auto" xml:lang="ES-ES" lang="ES-ES" class="TextRun SCXW9434875 BCX0"><span class="NormalTextRun SCXW9434875 BCX0"> Por lo tanto, en la siguiente imagen puede encontrar la funci&oacute;n &ldquo;</span><span class="NormalTextRun SpellingErrorV2 SCXW9434875 BCX0">getkey</span><span class="NormalTextRun SCXW9434875 BCX0">(</span><span class="NormalTextRun SCXW9434875 BCX0">)&rdquo; que</span><span class="NormalTextRun SCXW9434875 BCX0"> realiza la lectura de la tecla, y as&iacute;, guardarlo en la variable &ldquo;</span><span class="NormalTextRun SpellingErrorV2 SCXW9434875 BCX0">key</span><span class="NormalTextRun SCXW9434875 BCX0">&rdquo; que ser&aacute; la pieza fundamental para realizar las diferentes comparaciones dentro de los condicionales, con el objetivo de activar las funciones que tiene encargada cada letra mencionada anteriormente. </span></span><span class="EOP SCXW9434875 BCX0" data-ccp-props="{&quot;201341983&quot;:0,&quot;335559739&quot;:160,&quot;335559740&quot;:259}">&nbsp;</span></p>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/31Yrcs6/get.png" alt="get" border="0"></a>


<h2><strong>Resultados y&nbsp;</strong><strong>an&aacute;lisis&nbsp;</strong></h2>


<h2><strong>conclusiones.</strong></h2>
