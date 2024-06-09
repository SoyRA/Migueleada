[![BATTLY LAUNCHER - ¡CUIDADO! Lanzador ACUSADO de MIRAR POR LA CAM (Pruebas) - (Habla el creador)](../../src/img/Vid-13-Thumb.jpg)](https://www.youtube.com/watch?v=InjnuNYfg-E)

> 0:56 - 1:13 | "Battly es un proyecto de una sola persona llamada Ilyas. Él es español y Battly Launcher, según él mismo me cuenta, es un trabajo que hace en su tiempo libre dado que su trabajo real es otro. Vive en casa de sus padres y acaba de cumplir 18 años."

Esto que voy a decir es del futuro así que no lo tengan en cuenta aún (aunque no afecta a todo lo que sigue en este vídeo):

Increiblemente resulta que Battly Launcher es una red española al igual que TLauncher es una red rusa, LauncherFenix una red argentina que fue superada por una red mexicana (los impostores), Salwyrr una red francesa y SKlauncher una red polaca.

Vos dirás "[yo quiero de lo que fuma este tipo](https://www.youtube.com/watch?v=JQ-xHVUp62Q)" pero ¿qué opciones deja Miguel? si cuando hice mi broma sobre [red polaca vs red española](../Vid-11/src/img/Miguel-Gamer-Red-Polaca-vs-Red-Española.png) ([link al mensaje](https://discord.com/channels/612373280900513842/1134302777607209010/1181400605638529034)) no se considera red porque está solo Ilyas pero luego resulta que a SK lo trata de red por el simple hecho de tener usuarios con rol (y luego vimos que usuarios sin rol tambíen)...no se gente, me parece apropiado llamar red española a un lanzador donde su servidor de Discord está [lleno de roles](../Vid-11/src/img/Battly-Launcher-Permissions.jpg) en [comparación](../Vid-11/src/img/SKlauncher-Permissions.jpg) (ni hablemos de las ayudas comunitarias que tienen practicamente todos los lanzadores).

Pero seamos sinceros...o todos son una red de x país o ninguno es una red de x país. xd

> 1:17 - 1:57 | "(...) lo creó para ser un lanzador libre de virus. Es un enemigo natural de TLauncher y de SKlauncher, no solo se expresa siempre en contra de ellos si no que en su canal le dedicó vídeos, por ejemplo este: donde explica como eliminar el virus de SKlauncher (según él) o este otro donde hace algo similar pero con TLauncher. Déjame decirte que en nuestra entrevista no tuvo comentarios gentiles para estos lanzadores, sobre todo con SK ¿Pero por qué? Él los considera malos para la comunidad de Minecraft y muy peligrosos. Pero mira que ironía porque hace pocos días se descubrió dos cosas sobre su lanzador (...)"

Dejo su vídeo de [SKLauncher](https://www.youtube.com/watch?v=ivv1aj_od64) y de [TLauncher](https://www.youtube.com/watch?v=hudilaMZV5A).\
Ilyas...inicialmente iba a decir que tu vídeo sirve como guía para eliminar SKlauncher y de paso hacer un lindo análisis con el Antivirus, pero no recordaba dos detalles importantes: te acabás de cargar todos los datos del jugador.\
¿No era más fácil eliminar el `.exe` / `.jar` que uno descarga y luego eliminar también `%APPDATA%\.minecraft\sklauncher`, `%APPDATA%\.minecraft\sklauncher-fx.jar` y `%APPDATA%\java`? Pero debo felicitarte con la parte de eliminar todos los Java, ahorraste varios problemas a futuro. xd\
Y la parte de Malwarebytes...¿Vos me estás jodiendo? No solo metiste una amenaza apropósito (ni SKlauncher, ni Temurin ni Liberica ponen un `%USERPROFILE%\Downloads\java.exe`) si no que haces un análisis rápido...o sea ¿No que SK tiene virus? ¿Por qué no hiciste un análisis súper completo? Pero fuerte eh, tan fuerte que tu PC se convierte en una papa mientras dura el análisis. -.-"

Sobre vos Miguel, podrían ser 3 cosas que se descubrieron porque yo ya mencioné lo de la seguridad del sitio web antes de que siquiera pienses en hacer un vídeo.\
Pero bueno, seguramente me ignoraste al 100% porque pensaste "es de SK, seguro le está tirando mierda a la competencia".

> 2:09 - 2:31 | "¿Y de donde nacen estas pruebas? del análisis de su instalador (...)"

Bueno, como que dijiste estándar para luego descargar la beta. xd\
Dejo el informe de [VirusTotal](https://www.virustotal.com/gui/file/52b71e7c38eabddf0ba9ce20fbe6f6d7e69a8f12cf7128ffb0b50d8ea12ea2c0) que corresponde a la [release 1.4.5-beta](https://github.com/1ly4s0/battlylauncher/releases/tag/1.4.5-beta).\
&nbsp; \* Lamentablemente Ilyas eliminó todas las beta a los días de este vídeo, así que nadie podrá analizar ese ejecutable exacto (a menos que re-compilarlo nos deje con el mismo SHA-256).

> 6:35 - 6:40 | "Triage es lo que digamos yo, pienso que es el que mejor analiza ¿no? si hay virus o no."

Si, hasta que te marca [ransomware](https://tria.ge/231201-w7wqfaeh82) y ahí [decimos que es un falso positivo](src/img/Miguel-Gamer-Discord-Msg.png) ([link al mensaje](https://discord.com/channels/612373280900513842/1134302777607209010/1181391396352036964)). xd\
&nbsp; \* Si, se que es un falso positivo, creo que es en lo único que ambos podemos estar de acuerdo. (?

PD: Dejo el informe de [Triage](https://tria.ge/231105-gkzfgsdd37) que estás mostrando (que por cierto, nunca se terminó de instalar).

> 7:00 - 7:09 | "Desde Triage puedes ejecutar el instalador, seguir los pasos y claro, tu estás ya analizando lo que es el launcher en si ¿no? no solo el instalador."

No Ilyas, no...\
Hasta que no se termina la instalación y el usuario ejecuta el lanzador, se está analizando solamente el instalador.

> 16:12 - 16:16 | "Claro es que el problema es este, yo no puedo confirmar algo que no se como funciona."

¿Cómo? ¿Pero para SK y TL si sabes mientras que con tu propio lanzador no? es que...que lo diga Milei: [12:44 - 12:54](https://youtu.be/Jf3DfB-LTBI?t=764) (?\
¿Y si abrís la VM y le mostrás a Miguel como va el tema tras instalar? hasta podrías usar esto así no se escapa nada: [Enable or Disable Camera OSD](https://www.tenforums.com/tutorials/166065-how-enable-disable-camera-off-osd-notifications-windows-10-a.html)\
&nbsp; \* Ok ok, ya se que existen ataques para evitar hasta la maldita luz de la webcam...pero tengámosle algo de piedad al pibe.

> 19:06 - 19:38 | "Pero claro, recibir acusaciones de sus seguidores en plan (...) algunos me dijeron "¿tanto te cuesta admitir que tiene virus?" o me mandaban a callar (...) puro hate el que recibí...cuando yo, digamos, que no lo merezco ¿sabes? porque yo en ningún momento he hecho algo así ¿sabes?"

Pobrecito...no fue divertido que te acusen de delitos graves y te tiren mierda ¿verdad Ilyas?

> 21:05 - 22:30 | "Ahora reflexionemos un momento: que exista la posibilidad de que lo haga no significa que sea automáticamente culpable. Tener una duda es sano y está bien, pero acusar y sentenciarlo directamente no. Porque seamos conscientes de la gravedad de la acusación: se lo señala como una persona que hizo una aplicación para espiar personas en sus hogares, se lo acusa de mirar niños, se lo acusa de robar contraseñas y datos. Son acusaciones enormemente serias, cualquiera que hable de este tema lo debe hacer con mucho cuidado porque, si lo haces quedar a este chico como un loco que espía niños y al final no era cierto, yo creo que siempre que la otra parte este dispuesta a hablar, es importante contactarla, sobre todo en estos temas tan delicados. También es cierto que no siempre el creador de un lanzador donde se lo sospecha de algo hable, pero en este caso si. Pero en un caso así de grave, insisto, se debería intentar. Y claro, como se ve, el creador de Battly, estaba dispuesto a hablar y a explicarse. Este es Battly Launcher, estas son las pruebas de lo que supuestamente hace. Estas son las explicaciones técnicas de todo lo mencionado. Y estas son las palabras del creador del lanzador. Te doy todas las herramientas para que vos saques tu propia conclusión, de si es inseguro o no. Quiero que me des tu opinión sobre Battly en los comentarios."

1\. Me pregunto si será porque hablan el mismo idioma...me pregunto si será porque tiene 18 años...me pregunto si será porque reflexionaste y te diste cuanta que con SK te fuiste bien a la mierda y no deberías volver a hacerle algo así a nadie.\
2\. Todo muy lindo lo que decís y concuerto con casi todo, pero es un giro de 180º...es como si todo lo que pasó con TLauncher, Salwyrr y SKlauncher no exisitera (sin mencionar el resto de lanzadores). Por un lado digo "oh genial, ese certificado en Ciberseguridad funcionó muy bien" pero por el otro digo "uy...esto es un cambio demasiado radical...se acaba de cargar sus propios vídeos".\
3\. O sea que si mi conclusión es que es inseguro y hace todas las barbaridades de las que se le acusa...¿es totalmente válida? ¿Debo tirarle mierda a Ilyas porque concluí eso? ¿Debo tirarte mierda a vos porque también concluí eso? Es que esto es un sin sentido absoluto...

> <Fin del vídeo>

Bueno, no tengo enlaces que agregar ya que no hubo necesidad del canal de pruebas o algo similar (y las cosas se ven bastante claras como para que lo copien ustedes xd pero tampoco es como que se comenta al respecto).\
Este es el mejor vídeo en cuanto a neutralidad y objetividad se refiere...ni con Salwyrr (la 1ra vez) hubo este nivel. Esto obviamente es genial, pero como mencioné antes...no se que pensar al respecto (limitandome a la fecha de este vídeo).\
&nbsp; \* También veo que por primera vez en Miguel Gamer se menciona alguna de las otras pestañas de VirusTotal (lo cual va a ser un dolor de huevos para todos, ya que no se actualizan al re-analizar y son más complejas).

Sobre este vídeo no tengo más nada que decir, pero hay un tema que no se trató y me veo en la obligación de hacerlo.

***

> [!NOTE]
> Hablar sobre Battly Launcher fue algo díficil porque:\
> 1\. Ilyas hace un vídeo contra SKlauncher con que "ayy virus virus unu" donde obviamente el virus no existe.\
> 2\. Si entro a su sitio web, me encuentro que a Ilyas le importa mucho la seguridad y los datos y no se que...pero va y comete aberraciones como dejar mi usuario y contraseña en HTML y una Cookie o dejar que el mundo vea su CRUD mal hecho (por suerte mal hecho) con los 50.000 usuarios (y en aumento) que tenía.\
> 3\. Miguel hace un giro de 180º, no tira acusaciones graves así de gratis (hasta hace una reflexión)...pero ignoró por completo lo que dije arriba...menos mal que a Miguel le importaba la seguridad de los usuarios y ahora tiene una certificación en Ciberseguridad. . _ .\
> 4\. Y lo más complicado de todo (y razón por la cual terminé haciendo el repositorio): Miguel me estaba empezando a cansar un poco con que tire mierda de SK esperando que yo responda, pero decirme "hacete cargo de tu red" ([link al mensaje](https://discord.com/channels/612373280900513842/1134302777607209010/1181402083388293120)) hizo que se me inflen un poco los huevos. Luego que Ilyas se me ofenda porque descubre "que soy de SK" y piense que dije lo del HTML, Cookie y CRUD "por ser de SK" hizo que también se me inflaran los huevos un poco más. Pero lo que terminó de rematarla fue el siguiente vídeo donde dejo un comentario, me responde Ilyas y bueno...que me tire "(...) vosotros, los de SK, en ningún momento habéis (...)" y luego no responda terminó por inflarme los huevos al 100% (dato curioso: borraron mi respuesta a ese mensaje luego de unos días, veo que el derecho a réplica solo es válido para algunos).
>
> Y bueno...así que este vídeo es muy jodido de responder porque tengo que ser lo más neutral y objetivo posible con las dos personas que no les gusta que les tiren mierda mientras van tirando mierda a los demás (especialmente a mi, que me ponen como si formo parte de SK al grado de que es mi red o soy del staff).

> [!TIP]
> Ah si, cuando digo algo como "dice que le importa la seguridad" me refiero a esto:\
> FAQ - ¿Battly es seguro? ¿Está libre de virus? | [Imagen](src/img/Battly-Launcher-FAQ.png) - [Link](https://battlylauncher.com/faq)\
> Política de privacidad - Protección de Datos | [Imagen](src/img/Battly-Launcher-PP.png) - [Link](https://battlylauncher.com/politica-privacidad)\
> Términos y condiciones - Privacidad y Protección de Datos | [Imagen](src/img/Battly-Launcher-ToS.png) - [Link](https://battlylauncher.com/terminos)

***

El 07/08/2023 dije que el sitio web de Battly Launcher no me inspiraba mucha confianza ya que aparece mi usuario y contraseña en el código HTML ([link al mensaje](https://discord.com/channels/612373280900513842/1079516976982003772/1138156970445131906)).\
Luego el 16/08/2023 volví a opinar pero le sumé que podía acceder un random a su CRUD mal hecho (que suerte que estaba mal hecho) para ver la lista de usuarios ([link al mensaje](https://discord.com/channels/612373280900513842/1141422535003611186/1141443455801888838)).\
Y finalmente el 30/11/2023 mencioné todo lo que sabía...pero no dije mi teoría de "¿Y si en verdad aparece mi contraseña porque el pibe la almacena en texto plano en la base de datos?" porque...bueno, ya tenes un certificado en Cibersegurdad y expertos que te ayudan ¿no tienen el nivel suficiente para darse cuenta? ([link al mensaje](https://discord.com/channels/612373280900513842/1134302777607209010/1179932178474340542)).\
&nbsp; \* Imagen sobre [HTML](src/img/Battly-Launcher-HTML.png), [Cookie](src/img/Battly-Launcher-Cookie.png) y [CRUD](src/img/Battly-Launcher-CRUD.png).

> [!CAUTION]
> Entre Enero/Febrero del 2024, ya no hay más categoría/canal para crear hilos (por lo tanto, ya no se puede acceder a los dos hilos donde menciono lo del HTML y CRUD).

Yo sospechaba que Battly Launcher almacenaba las contraseñas SIN ENCRIPTAR en su base de datos porque, si utiliza justamente el usuario y contraseña para hacer ciertas acciones, debería de estar pasando esto:\
\- El servidor recibe mi usuario y contraseña, hace lo que tenga que hacer y luego devuelve dicho usuario y contraseña (todo va ocurriendo en memoria, no se guarda nada). Pero en la base de datos realmente lo almacena cifrado.\
&nbsp; \* Un poco falopero hacer las cosas así pero hey, literalmente cuando lo vi la 1ra vez pensé que quizás el pibe es un groso en Back-End pero tiene sus momentos de brillar xd

Pero este pensamiento tenía un problema muy grave: ¿Cómo mierda alguien que le importa la seguridad va a hacer algo así? Pensé "bueno, será para mantener la sesión porque no sabe otra forma" pero me encuentro como hay ID de Sesión...y cualquier justificación que yo intentaba darle, no hay forma de remarla.\
&nbsp; \* Aunque yo no quería creerlo, realmente todo apuntaba a que almacena todo en texto plano, cagándose en cualquier tipo de seguridad básica...y lo peor de todo: en los datos de sus usuarios ¿Quien tiene datos muy interesantes para vender, Ilyas? ¿SK que lo único visible es mi Email? ¿O vos que podes ver mi Email y Contraseña?

Así que entré al Discord de Battly Launcher para ver si alguien comentó algo al respecto y me fui encontrando cosas que no quería ver...yo realmente no quería ver que mi teoría se vuelva realidad:\
\- "te mandaré de nuevo la contraseña si todo coincide" | [Imagen](src/img/Battly-Launcher-Discord-01.png) - [Link al mensaje](https://discord.com/channels/885235460178342009/968137371298168853/1128063308214321295)\
\- "Espera unos minutos y se te enviará tu contraseña actual" | [Imagen](src/img/Battly-Launcher-Discord-02.png) - [Link al mensaje](https://discord.com/channels/885235460178342009/1118939499083345960/1130558862995496990)\
\- "Por cierto, actualiza tu contraseña a una más "normal"" | [Imagen](src/img/Battly-Launcher-Discord-03.png) - [Link al mensaje](https://discord.com/channels/885235460178342009/1118939499083345960/1146213893740441670)\
\- "dime tu correo y usuario por dm, y la contraseña con la que estás intentando acceder" | [Imagen](src/img/Battly-Launcher-Discord-04.png) - [Link al mensaje](https://discord.com/channels/885235460178342009/968137371298168853/1152648339460980779)\
\- "Que buena contraseña tienes" | [Imagen](src/img/Battly-Launcher-Discord-05.png) - [Link al mensaje](https://discord.com/channels/885235460178342009/968137371298168853/1192130458406891631)

De igual modo, aunque todo apuntaba a que podes ver la contraseña de tus usuarios, dije "mmm...bueno, si hasta a TL mencioné que podría ser un desafortunado mal entendido...creo que puedo preguntarle a los usuarios xd"\
\- ~~"te mandaré de nuevo la contraseña si todo coincide"~~ | No responde\
\- ~~"Espera unos minutos y se te enviará tu contraseña actual"~~ | No responde\
\- "Por cierto, actualiza tu contraseña a una más "normal"" | ¿Le diste tu contraseña? No ¿Puedo sacar foto? No :'v\
\- ~~"dime tu correo y usuario por dm, y la contraseña con la que estás intentando acceder"~~ | No responde\
\- ["Que buena contraseña tienes"](src/img/Battly-Launcher-Discord-05-Answer.png)

> [!NOTE]
> Algo que noté, es que a ambos usuarios les parecía normal esto...\
> O sea...esto es grave...ni los usuarios saben que datos tienen que estar protegidos y cuales no.

Yo se que me dirás "ayyy pero tengo autenticación en 69 fases, contraseña de 1024 caracteres que cambio cada 5 segundos, blablabla" pero no importa Ilyas ¿Sabes por qué?\
\- Porque sos vos el que tiene datos muy interesantes para vender.\
\- Porque si por algún casual tu seguridad falla y pueden hacerse con la base de datos, sentenciaste a tus 50.000 usuarios (que además de ir en aumento, para este vídeo seguro que serán muchos más porque el 50.000 lo digo por el CRUD).

Así que felicidades Ilyas, lograste hacer algo 100% comprobado peor que cualquier lanzador analizado hasta este vídeo y que Miguel no te diga nada al respecto.\
Y vos Miguel...es una fatalidad que hayas ignorado este detalle y debo felicitarte solamente a vos (haré de cuenta que ignoraste a los expertos que te ayudan y a tu comunidad tan superior): no tuviste el nivel suficiente para darte cuenta que había esta posibilidad y, sobre todo, no te diste cuenta que era muy grave...especialmente si recordamos todos los eventos resientes. Que loco ¿no? A SKlauncher hasta le detectaste un patrón y modus operandi profesional (que obviamente nunca existió, pero bueno), pero no pudiste detectar algo más simple con Battly Launcher. -.-"\
&nbsp; \* Recordemos que en el directo que exponias a los estafadores, dijiste literalmente esto: "*¿Se acuerdan que yo le había dicho que es bastante peligroso que puedan tener tus datos? sobre todos, sobre todo si vos tenés la misma contraseña y el mismo usuario para todo. Lo hablamos mucho por ejemplo con el caso de SKlauncher por ejemplo u otros donde tenés que tener cuidado con tus con los datos que hacían, SKlauncher prometía hasta venderlos.*" ¿Te das cuenta que trataste peor al que COMO MUCHO puede dar tu usuario y correo y al que puede dar tu usuario, correo y CONTRASEÑA no le dijiste nada? Ambos obviamente no premium, ya que no pueden ver ni tocar algo así de tu cuenta Premium.

> [!CAUTION]
> Ojo! Que Battly Launcher almacene las contraseñas en texto plano, no significa que Ilyas va y vende todo o intenta hackear a sus usuarios.\
> Yo creo que Ilyas no es malicioso, solamente no tiene los conocimientos suficientes y bueno...pasan cosas como esta.

***

> [!NOTE]
> Ahora pondré en práctica lo que te dije Ilyas: [Créeme, sería peor si estuviera en proceso de elegir otro lanzador para utilizarlo todos los días. a,a](https://discord.com/channels/612373280900513842/1134302777607209010/1181618376313929770)\
> Bueno, un cachito porque obviamente si antes de llegar a analizar código, paquetes, etc. veo cosas inviables...no voy a seguir xd

¿Recomiendo Battly Launcher? Por su puesto que no ¿Qué esperabas? ¿Un plot twist? :'v\
Pero ¿Por qué? pues...¿En serio tengo que decirlo? xd bueno, vamos en orden con un resumen de 50.000 caracteres:\
1\. Veo mi usuario y contraseña en el código HTML y en una Cookie, además de la lista de usuarios (que si, ya se que esto último se arregló al igual que no usar HTTPS en lo que mostré del HTML).\
&nbsp; \* Más adelante confirmo que incluso almacena la contraseña en la base de datos en texto plano (sin encriptar ni nada - algo que se arregló, supuestamente, el 31/12/2023 ya que intentaron hacer ataques de SQL Injection).\
2\. Si o si tengo que hacer una cuenta para poder usar el lanzador, parece que alguien olvidó lo que es un no premium.\
3\. [Tu repositorio sobre el lanzador](https://github.com/1ly4s0/battlylauncher) estuvo 7 meses bajo licencia [GNU AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) ([2ca1db1](https://github.com/1ly4s0/battlylauncher/blob/2ca1db1caa40dfc2cb04c0e7e8706f1110fa48f2/LICENSE)) porque al final la borraste...pero para empeorar todo: estuvo 4 meses (y en aumento) con un [EULA](https://github.com/1ly4s0/battlylauncher/blob/51cd14356d2b53de43cf3254610dd43fff2a6998/LICENSE.MD) que invalida dicha licencia.\
&nbsp; \* No solo invalida la licencia, si no que pones cosas que NO querés que te hagan pero luego vos vas y se la haces a los demás: como decir "No podras copiar, modificar, distribuir, (...)" y a OptiFine te cagaste en su [Copyright](https://optifine.net/copyright) poniéndolo en tu lanzador si no que hasta le re-subiste los archivos en [1ly4s0/battlylauncher-optifine](https://github.com/1ly4s0/battlylauncher-optifine).\
4\. Justo el código más importante para poder defenderte en la acusación de si tenes virus o no, lo tenes todo ofuscado ¿Para qué mierda te haces el open source si luego tenes ofuscado tu código? ¿Miedo a que te roben? No me jodas Ilyas, hasta me dirás "ay pero yo avisé en el vídeo de Miguel" ¿Y si el vídeo nunca llegaba? Porque revisé tu sitio web y tu repositorio, ambos no dicen nada sobre que el código está ofuscado (si dicen que NO debo "descompilar, realizar ingenieria inversa o intentar obtener el codigo fuente del Software").\
&nbsp; \* Además de ofuscado está licenciado con [CC BY-NC 4.0 DEED](https://creativecommons.org/licenses/by-nc/4.0/) (no muy recomendada para software), donde nuevamente tu EULA lo invalida.\
5\. Borraste todas las versiones beta...ahora nadie podrá re-analizar los ejecutables (aunque siguen los [tags](https://github.com/1ly4s0/battlylauncher/tags) y con eso podrías re-compilarlo...si deja un SHA-256 distinto, al pedo sirve investigar).\
&nbsp; \* Para peor, vi que uno preguntó al respecto en tu Discord y tu respuesta fue solamente "[porque quiero](src/img/Battly-Launcher-Discord-06.png)" ([link al mensaje](https://discord.com/channels/885235460178342009/1118939499083345960/1181690281582678086)) ¿Vos te acordás de lo que te acusaron? ¿A vos te parece que borrando cosas, ocultando código, etc. va a ayudar? . _ .\
6\. Y para terminar de rematarla (como si ya el punto 1 no fuera suficiente motivo de inviabilidad), mostrás tu gran preocupación por la seguridad [no sabiendo si algo es seguro y que lo permitan de todos modos](src/img/Battly-Launcher-Discord-07.png) ([link al mensaje](https://discord.com/channels/885235460178342009/1118939499083345960/1184861460631928983)) ¿Pasaste de un "será un falso positivo" a un "no tiene nada" en pocos minutos? que crack, ahora aplicá ese nivel a todo lo demás, por favor. :v

Sacando el punto 2, el resto fue sin mirar tu lanzador (no pienso meterme a analizar el código, paquetes, etc).\
Yo personalmente ya con el punto 1 dejaba de seguir mirando y no tocaba tu lanzador ni en pedo, pero tuviste la gran idea de inflarme los huevos.

Aunque podría tener motivos para pensar que sos algo malicioso, es verdad que con 18 por más adulto que seas...vas a hacer pelotudeces igualmente, hasta las harás en mayor o menor medida el resto de tu vida.\
Ojalá que reflexiones y te sirva esta experiencia para cambiar para bien. Y por el amor de Dios, la próxima vez que hagas un proyecto que involucre datos de usuarios: asegurate de que estos datos estén protegidos por todos lados.

> [!CAUTION]
> Pese a todo lo que dije, esto no significa que efectivamente/probablemente Battly Launcher accede al portapapeles ni a la cámara web.\
> &nbsp; \* Ni tampoco que haga algo con los datos de sus usuarios.

> [!IMPORTANT]
> 1\. Lo del HTML y Cookie sigue pasando, lo del CRUD fue arregalo incluso antes de que yo haga este repositorio.\
> 2\. Lo de almacenar las contraseñas en texto plano se arregló (supuestamente) el 31/12/2023 porque intentaron hacer SQL Injection.\
> 3\. Sobre el tema del portapapeles/cámara web, le he preguntado a Ilyas si ya tiene un vídeo o algo donde muestra que esto efectivamente es un falso positivo y un desafortunado mal entendido: por ahora no, así que luego editaré esto cuando por fin lo tenga.
