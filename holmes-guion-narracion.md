# Holmes — guion de narración — sincronizado con holmes-montaje.mp4 (4:08)

[0:00] 01-cover — Holmes es una prueba de concepto: un equipo de agentes de inteligencia artificial que monitorea la infraestructura. No solo avisa cuando algo falla: investiga la causa y la explica en lenguaje claro.

[0:14] 02-problema — Hoy, muchas fallas las descubrimos por un llamado. Las pistas están repartidas en decenas de servidores, y la experiencia de cómo se resolvió algo depende de quién estaba de guardia.

[0:27] 03-que-es — Holmes es un agente de IA que vigila la infraestructura las veinticuatro horas y le acerca al equipo la causa probable de cada problema. Propone, pero no actúa por su cuenta.

[0:40] 04-como — El ciclo es simple: observa los registros, detecta lo que importa, investiga con evidencia y casos anteriores, y avisa con un mensaje claro: qué pasó, por qué y qué conviene hacer.

[0:54] 04b-clip-alerta (15 s) — Un ejemplo real: llegan dos alertas críticas. En minutos, Holmes investiga, descubre que es una falsa alarma por un reinicio del monitoreo, muestra la evidencia y la vincula con casos anteriores ya confirmados por el equipo.

[1:09] 05-equipo — Holmes no trabaja solo: son tres agentes de IA, cada uno con su rol. Watson es el único que puede actuar, por ejemplo reiniciar una aplicación, y siempre después de que una persona lo aprueba. Hudson acompaña el día a día: responde consultas y toma notas. Las personas deciden.

[1:30] 05b-clip-hudson (16 s) — A Hudson se le pregunta como a un colega. Responde con datos reales, sin tocar nada: y si hay que ejecutar algo, indica el comando y los riesgos, pero no lo hace.

[1:46] 06-herramientas — Para investigar, Holmes cruza varias fuentes: los registros, el pulso de cada servidor, el historial de casos y los cambios recientes en el código.

[1:56] 06b-clip-pulso (8 s) — Cada cinco minutos, cada servidor manda su latido: memoria, disco y carga. Si alguno deja de reportar, Holmes empieza a investigar.

[2:06] 07-seguridad — La seguridad es uno de sus ejes. Todos los días contrasta los servicios con la base pública de vulnerabilidades, las CVE, y señala qué parches urgen. Revisa accesos y puertos abiertos, siempre con mínimo privilegio. Un caso real: detectó servidores que aceptaban acceso remoto con contraseña, y el equipo los cerró.

[2:27] 08-comunica — Una regla de diseño fue no inundar al equipo de alarmas. Lo crítico llega al instante; lo demás se agrupa en partes periódicos y resúmenes. Y se le puede consultar por Telegram, como a un colega. Horarios, frecuencia y funciones son personalizables.

[2:45] 08b-clip-comandos (12 s) — Con comandos simples se ve el estado de todos los servidores, o se pide un resumen de la semana por mail.

[2:57] 09-casos — En las primeras semanas, Holmes señaló problemas reales temprano y con la pista correcta. En ninguno hizo el arreglo: el equipo fue directo a la causa.

[3:08] 10-beneficios — Nos enteramos antes que los usuarios, el aviso llega con la causa probable, el conocimiento queda en la organización y la seguridad se revisa todos los días.

[3:20] 11-confidencialidad — La confidencialidad está resuelta por diseño. Holmes solo puede leer: no ejecuta comandos ni entra a las bases. Antes de enviar cualquier texto al modelo de IA, oculta emails, CUIL, contraseñas y credenciales, y los registros completos quedan en servidores propios.

[3:37] 12-propuesta — Esta prueba de concepto ya funciona en producción, y deja algo claro: Holmes no reemplaza a nadie. Hace el trabajo repetitivo de mirar registros a toda hora y le devuelve al equipo tiempo y contexto. Los próximos pasos: sumar aplicaciones, probar los sitios desde afuera y un informe mensual para la dirección.

[3:59] 13-cierre — Holmes: agentes de IA, en prueba de concepto. Más visibilidad, más seguridad, las personas al mando.
