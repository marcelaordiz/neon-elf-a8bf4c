# Buscador de licitaciones y convocatorias · PED FLACSO Argentina

Una rutina de Claude corre todos los lunes a las 7:52 (hora de Buenos Aires). Busca en la web licitaciones, consultorías y convocatorias de financiamiento en las que el Programa de Educación a Distancia podría presentarse, las puntúa de 0 a 100 según el perfil del programa y manda el reporte por mail a marcelaordiz@gmail.com.

La rutina se llama "Oportunidades PED FLACSO (semanal)". Hoy no tiene Gmail conectado (desde esta sesión no se pudo guardar el conector), así que el reporte llega como notificación por mail de la rutina. Si le agregás Gmail desde la rutina en claude.ai, pasa a mandar el reporte formateado y a revisar los mails anteriores para no repetir oportunidades.

Las instrucciones completas que recibe la rutina están en [`prompt-rutina.md`](prompt-rutina.md): perfil del PED, fuentes, consultas, criterios de puntaje y formato del mail. ## Cómo ajustarlo

Si querés cambiar el perfil, sumar fuentes o tocar los puntajes, editá `prompt-rutina.md` y pedile a Claude que actualice la rutina con el texto nuevo (el texto se guarda en la rutina misma; editar este archivo solo no alcanza). Lo mismo para cambiar el día, la hora o los destinatarios.

La rutina se ve y se pausa desde claude.ai, en la sección Routines.

## Limitaciones

- Trabaja con búsqueda web, sin acceso con usuario a portales cerrados (UNGM con login, COMPR.AR con registro de proveedor, dgMarket, Devex Pro). Lo que está detrás de un login puede no aparecer.
- Las fechas y montos se verifican abriendo la página de la fuente. Igual conviene confirmar en el pliego antes de decidir.
