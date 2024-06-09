[![TLAUNCHER METIO UN "BAZARBACKDOOR" en su instalador (pueden mirarte 👀 y llevarse tus archivos)](../../src/img/Vid-05-Thumb.jpg)](https://www.youtube.com/watch?v=yKUHLv9hgws)

> 1:34 - 1:50 | "Escuchá esto: Se pueden propagar automáticamente por otros dispositivos de la red. O sea que si tienes esto en una PC y alguien en tu casa se conecta a la misma red Wi-Fi, se puede infectar también. Esto ya no queda en las PCs que usan TLauncher, ahora afecta a todo el hogar."

O sea...esto es terrible, si antes Feather Client superaba a todos los lanzadores del vídeo anterior, vino TLauncher y dijo "*¿Y quien lo decidió?*" xdd\
Así que ahora vamos camino a tener que formatear absolutamente todo...lo cual sería una gran idea que ahora Miguel (o alguien) saque un vídeo sobre "ciberseguridad".\
Me explico, si formateaste todo y estás 100% libre de algún virus ¿Qué mejor momento para utilizar correctamente el Antivirus, usar un Firewall, un gestor de contraseñas, el cifrado de BitLocker o VeraCrypt, 2FA, etc?

> 2:57 - 3:04

Che...pero Miguel :'v ¿No estábamos de acuerdo que de TLauncher, una de sus cagadas, era no usar las fuentes oficiales? Dejá el link oficial del [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html) en NirSoft. xd

> 8:11 - 8:20 | "Tria.ge nos enseña, nos dice y yo aquí te traigo y comento que TLauncher a través de su nuevo instalador tiene una puerta trasera que (...)"

A ver a ver...¿Qué pasó? . _ .\
¿O sea qué todo esto es puramente una probabilidad de que TLauncher tenga BazarBackoor o con el equipo que ayuda a Miguel confirmaron que efectivamente lo tiene?\
Apunto a que no, tanto el titulo como la miniatura son una afirmación...y no podes tirar algo así de grave porque leíste una etiqueta en Triage. . _ .

> 10:32 - 10:44 | "Para hacer este vídeo nos asesoramos con expertos en ciberseguridad, ingenieros en informática y todos coinciden que se debe formatear y cambiar todas tus claves y acceso"

Jum...sigo con dudas.\
Por un lado empezamos fuerte con puras afirmaciones, nada de probabilidades ni nada.\
Pero ahora terminamos con que es cosa de Triage y no se afirma que se verificó que efectivamente tenga un BazarBackdoor.\
Mira que TLauncher me parece inviable desde hace años por todo lo que dije anteriormente sobre ellos, pero tampoco da tirarles de criminales al grado de que arruinan empresas e incluso familias.

> <Fin del vídeo>

Informe de [Triage](https://tria.ge/230128-rqw8esfb64), la página oficial de [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html) (Miguel no puso el link oficial, supongo para que no sufras con la montaña de texto) y el informe de TrickBot por [Kaspersky](https://www.kaspersky.es/resource-center/threats/trickbot) como también [ESET](https://www.welivesecurity.com/la-es/2021/06/25/trickbot-caracteristicas-malware-mas-activos-peligrosos/).\
&nbsp; \* Todo esto, salvo el link oficial de HashMyFiles, son sacados del Discord de Miguel ([link al mensaje](https://discord.com/channels/612373280900513842/1069410811988156496/1069413435437224057)).

Algo que noté del informe de Triage es que solo la VM con Windows 7 marca esto, pero si miro los Resubmissions:\
\- Hay uno que marca BazarBackdoor (nuevamente, solo en Windows 7) con menos etiquetas.\
\- Hay otro en Windows 7 pero ya no marca nada de BazarBackdoor.\
Pero todos son del futuro (luego de este vídeo), así que tocaría buscar informes desde el vídeo de Miguel para atrás (y quizás un cachito adelante, pero no irse muy lejos).

Así que si me pongo a ver desde la fecha de vídeo de Miguel (29/01/2023) para atrás (25/01/2023) en Triage, me encuentro con esto:\
\- 61 informes (voy a ignorar los resubmissions como también si tienen o no las mismas etiquetas)\
&nbsp; \- 51 en Windows 7 x64\
&nbsp; &nbsp; \- 21 diciendo BazarBackdoor\
&nbsp; \- 4 en Windows 10 1703 x64\
&nbsp; &nbsp; \- 1 diciendo BazarBackdoor\
&nbsp; \- 57 en Windows 10 2004 x64\
&nbsp; &nbsp; \- 0 diciendo BazarBackdoor

> [!CAUTION]
> 1. No revisé el Replay Monitor de cada uno, podría haber alguno falsificado al ejecutar [000.exe](https://github.com/FlyTechVideos/000exe) (como el de [este](https://es.linkedin.com/pulse/tlauncher-el-anzuelo-perfecto-pablo-arrabal-espinosa) post de LinkedIn) como también algunos donde no ejecutan nada y así.
> 2. Me causa gracia que los 3 Sistemas Operativos son obsoletos xd el usuario común debería estar, al menos, usando Windows 10 21H2.

Entonces...¿Acaso es un desafortunado falso positivo o realmente TLauncher viene con un regalito bien potente?\
Sin pruebas sólidas (hola código fuente o algo de tal calibre xd) hay bastante para defender como atacar a TLauncher sobre el tema del BazarBackdoor.
