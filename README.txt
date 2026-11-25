PLAYANATOMY LIVE V5 - ACTUALIZACIÓN DEL MISMO SITIO RENDER / GITHUB

Contenido: server.js, package.json, render.yaml, questions.json, public/index.html.
Banco: 2638 QCM, Temas 1-12. Incluye banque_controle.csv para revisión manual.

PASOS: en el repositorio GitHub existente PlayAnatomy-LIVE, reemplaza el contenido de cada fichero por la versión de este ZIP (incluyendo public/index.html), haz commit y espera a que Render indique LIVE. No crees un servicio nuevo. Conserva una copia de la versión actual antes del cambio.

FUNCIONES: 30 preguntas por defecto, selección de temas, preguntas rotativas por tema en el navegador del profesor, respuestas A/B/C/D sin texto en móviles, control del profesor sin cronómetro; la primera respuesta correcta recibe 1000 puntos, las siguientes pierden 10 puntos por cada segundo completo desde esa respuesta hasta un mínimo de 500; respuestas incorrectas 0. Los puntos se revelan solo con la corrección. Revancha: mismos jugadores, mismo código y temas, puntuaciones reiniciadas; nueva partida: termina sala y crea otra con nuevo QR y código. Reconexión por token de navegador y sala.

Limitaciones: las salas son temporales en la RAM del servidor; reinicios/suspensión de Render interrumpen la partida. La rotación se guarda en localStorage del profesor (borrar datos del navegador reinicia la rotación). No se ha hecho una revisión médica manual individual de los 2638 enunciados. Para el QR se conserva el servicio de imagen externo de la versión existente.
