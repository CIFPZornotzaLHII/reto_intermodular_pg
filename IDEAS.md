# Ideas de proyecto · DAM

Veinte ideas de partida. Todas tienen un cliente o una necesidad identificable y se pueden construir en las horas del
módulo apoyándose en lo que ya trabajáis en otros módulos. Podéis combinarlas, recortarlas o proponer otra: lo que no
cambia es que tiene que haber **un cliente, un plan y algo que funcione en la demo**.

Cómo elegir: coged una que os guste, buscad un cliente real (un comercio, una asociación, un departamento del centro,
una familia) y preguntadle qué le haría falta de verdad. El proyecto bueno sale de esa conversación, no de la lista.

| # | Idea | Qué es | Tecnologías del ciclo | Lo mínimo que tiene que funcionar |
|---|---|---|---|---|
| 1 | **Inventario y almacén** | Gestión de stock de una pyme: productos, entradas/salidas, alertas de mínimo y cliente de escritorio. | Spring Boot, MySQL, API REST, JavaFX/escritorio | Alta de productos, movimiento de stock y alerta cuando un producto baja del mínimo |
| 2 | **Chat de aula por sockets** | Chat cliente-servidor con salas, usuarios y persistencia, sin depender de servicios externos. | Java, sockets TCP, hilos, MySQL/H2 | Tres clientes en dos salas, mensajes persistidos y recuperados al reconectar |
| 3 | **Juego 2D con ranking online** | Juego en Unity (plataformas, carreras, puzzle) con marcador global servido por una API. | Unity (C#), Spring Boot, API REST, MySQL | Partida jugable y puntuación enviada a la API que aparece en el ranking |
| 4 | **Multijugador por turnos** | Juego por turnos (batalla naval, cartas) con servidor propio y varios clientes. | Java, sockets TCP/UDP, hilos, Unity o JavaFX | Dos jugadores en máquinas distintas terminan una partida completa |
| 5 | **Cliente de correo simplificado** | Cliente que lee y envía correo con filtros, plantillas y firma, pensado para un uso concreto (p. ej. secretaría). | Java, SMTP, IMAP, JavaFX | Leer la bandeja, filtrar por remitente, enviar con plantilla y adjunto |
| 6 | **Sincronizador de carpetas** | Copia y sincronización de carpetas entre un cliente y un servidor por FTP/FTPS con planificación y registro. | Java, FTP/FTPS, hilos, planificación, logs | Sincronización programada de una carpeta con detección de cambios y registro |
| 7 | **Monitor IoT con alertas** | Sensores que envían datos a una API y una app que muestra gráficas y avisa (Telegram/correo) al superar umbrales. | IoT (ESP32/Python), Spring Boot, API REST, MySQL, cliente escritorio o móvil | Un sensor real, gráfica del día y una alerta enviada al superar un umbral |
| 8 | **Reservas con backend y app** | Sistema de reservas (aulas, pistas, citas) con API en Spring Boot y cliente multiplataforma. | Spring Boot, MySQL, API REST, JavaFX o web | Reservar, ver disponibilidad y cancelar desde el cliente, con validación en la API |
| 9 | **Biblioteca y préstamos** | Catálogo, socios, préstamos y devoluciones, con informes y búsqueda. | Spring Boot, MySQL/MongoDB, API REST, JavaFX | Préstamo y devolución completos con informe de libros fuera de plazo |
| 10 | **TPV para la cafetería** | Punto de venta táctil: productos, pedidos, tickets, cierre de caja e informes. | Spring Boot, MySQL, API REST, JavaFX, impresión | Un pedido completo con ticket y el cierre de caja del día |
| 11 | **Fichaje y control horario** | Registro de entrada/salida (QR, PIN o tarjeta) con API, panel y exportación mensual. | Spring Boot, API REST, MySQL, cliente escritorio o móvil | Fichar entrada y salida, ver las horas del mes y exportarlas |
| 12 | **Entrenador de comandos Linux** | App que propone retos de terminal, comprueba la respuesta y guarda el progreso y un ranking. | Java, procesos/sh, Spring Boot, API REST, MySQL | Cinco retos con corrección automática y ranking entre usuarios |
| 13 | **Bot del centro** | Bot de Telegram o Discord que responde dudas (horarios, menú, avisos) y publica alertas desde un backend. | Java o Python, API del bot, Spring Boot, MySQL | Tres comandos útiles con datos reales y un aviso programado |
| 14 | **Tablero Kanban de tareas** | Gestor de tareas con tableros, columnas, asignación y notificaciones, con cliente de escritorio. | Spring Boot, API REST, MySQL, JavaFX, SMTP | Crear tablero, mover tarjetas entre columnas y recibir un aviso al asignar |
| 15 | **Agregador de ofertas de empleo TIC** | Recoge ofertas de varias fuentes, las guarda y las muestra con filtros y alertas por correo. | Python (scraping), Spring Boot o Flask, API REST, MySQL, SMTP | Ofertas reales recogidas a diario, filtro por tecnología y alerta por correo |
| 16 | **Gestor de turnos con pantalla** | Sistema de turnos (secretaría, cafetería) con pantalla de llamada y app para pedir número. | Spring Boot, API REST, Unity o JavaFX para la pantalla, cliente móvil o web | Pedir turno, llamarlo desde el mostrador y verlo en la pantalla |
| 17 | **Juego educativo sobre seguridad** | Juego en Unity para alumnado de ESO sobre contraseñas, phishing o redes, con puntuación y progreso guardado. | Unity (C#), API REST, MySQL | Tres niveles jugables y progreso guardado por usuario |
| 18 | **Mini ERP para una pyme** | Clientes, presupuestos, facturas en PDF y envío por correo para un negocio real. | Spring Boot, MySQL, API REST, generación de PDF, SMTP, JavaFX | Crear un cliente, una factura en PDF y enviarla por correo |
| 19 | **Servidor de ficheros con protocolo propio** | Servidor y cliente con interfaz para subir, bajar y compartir ficheros por un protocolo TCP diseñado por vosotros. | Java, sockets TCP, hilos, cifrado, JavaFX | Subida y descarga de ficheros grandes con varios clientes a la vez y comprobación de integridad |
| 20 | **Gestión de un club deportivo** | Socios, cuotas, equipos, partidos y clasificaciones, con API y app. | Spring Boot, MySQL, API REST, JavaFX o web | Alta de socio, cobro de cuota registrado y clasificación calculada a partir de los partidos |
