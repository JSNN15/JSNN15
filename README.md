# Julián Neira Nova

Ingeniero eléctrico, instalador SEC clase A, con 10 años en faena minera. Construyo IA que se puede comprobar: cada respuesta trae su fuente y cada resultado está medido, incluidos los que salen mal.

**Todo se prueba en el navegador: [jsnn15.github.io](https://jsnn15.github.io/)**

| Máquina | Qué hace | Medido |
|---|---|---|
| [Supervisor normativo](https://github.com/JSNN15/supervisor) | Una foto: identifica el equipo, lo confirma de cerca y lo revisa contra su lista, con el artículo del RIC, DS 594, DS 132 o DS 43 ya asignado. | 11 de 13 equipos identificados a la primera; los otros 2 los detectó y preguntó |
| [Consulta eléctrica](https://github.com/JSNN15/consulta-electrica) | Chat con los pliegos RIC y el DS 8. Cada cita se compara letra por letra con el texto oficial. | 25 de 29 citas con la frase exacta |
| [Planta virtual](https://github.com/JSNN15/planta-virtual) | Sala de control de una planta de cobre LX-SX-EW: provocas una falla y le preguntas qué pasa. | 13 pruebas del simulador |
| [Vigía EPP](https://github.com/JSNN15/vigia) | Revisa el EPP de cada persona, por foto o con cámaras en vivo sin nube. | 93 de 100 infracciones de casco; 2 falsas alarmas en 100 fotos limpias |
| [Lector de instrumentos](https://github.com/JSNN15/lector) | Foto de un manómetro de aguja y sale el número, con alarma y registro. | 6 de 8: geometría e IA coinciden |
| [Monitor de correas](https://github.com/JSNN15/monitor-correas) | Grietas detectadas con la correa en marcha, ubicadas en metros desde el empalme. | Aviso correcto en 6 de 9 videos |
| [Selector de fruta](https://github.com/JSNN15/selector-fruta) | Decide si cada fruta va o sale y comanda el expulsor. | 98,8 % en 480 fotos nuevas |
| [prama-agent](https://github.com/JSNN15/prama-agent) | Equipos de agentes de programación en tu servidor. No les cree: corre la prueba de cada tarea antes de integrarla. | CI y pruebas en el repositorio |

Las cifras vienen de pruebas chicas hechas por mí. Cada repositorio explica cómo se midió y qué falla todavía.

Las máquinas con IA de NVIDIA pasan por [nv-gateway](https://github.com/JSNN15/nv-gateway), un intermediario que guarda la clave fuera del navegador.

Trabajo a través de Servicio y Soluciones Tecnológicas DelaCruz SpA. Si tienes un problema de operación que se pueda medir, [escríbeme por LinkedIn](https://www.linkedin.com/in/julian-neira-nova/).
