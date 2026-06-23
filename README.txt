# Kahatsa

**Kahatsa** (del maya *"Recuerdo"*) es una aplicación de escritorio para Windows diseñada específicamente para personas con TDAH, TDA o dificultades con la percepción del tiempo[cite: 2]. A diferencia de las alarmas comunes que se descartan fácilmente, esta app utiliza mecánicas visuales forzadas para asegurar que el usuario realmente procese y ejecute sus tareas planificadas[cite: 2].

---

## El Problema
El Trastorno por Déficit de Atención e Hiperactividad (TDAH) afecta significativamente la percepción del tiempo en dos niveles clave[cite: 2]:
* **Memoria Prospectiva:** Dificultad para recordar hacer algo en un momento futuro específico[cite: 2].
* **Interval Timing:** Complicación para dimensionar cuánto tiempo ha pasado o pasará, un fenómeno conocido como "miopía temporal" (según investigaciones de Russell Barkley)[cite: 2].

Las alarmas ordinarias suelen fallar debido a la impulsividad; el usuario tiende a cerrarlas instantáneamente antes de que la mente consciente registre la tarea[cite: 2].

---

## La Solución
Kahatsa resuelve esto mediante un enfoque de diseño minimalista, directo y de atención forzada[cite: 2]:

* **Pantalla Completa Ineludible:** Al llegar la hora, el recordatorio interrumpe la pantalla completa sobre cualquier otra ventana[cite: 1, 2].
* **Contador Regresivo Antimpulsividad:** El botón de cierre permanece deshabilitado durante 5 segundos, obligando al usuario a realizar una pausa mental y leer el recordatorio antes de poder quitarlo[cite: 1, 2].
* **Diseño Sensorial Inclusivo:** Cuenta con un sistema de temas (Claro, Gris, Oscuro) con contrastes cuidados para evitar la sobrecarga sensorial y la fatiga visual[cite: 1, 2].
* **Persistencia:** Funciona en segundo plano desde la bandeja del sistema e incluye una opción de inicio automático con Windows[cite: 1, 2].

---

## Tecnologías Utilizadas
* **Python 3.13**[cite: 1]
* **Tkinter & Tkcalendar:** Para el desarrollo de la interfaz gráfica y selector de fechas[cite: 1, 2].
* **Pystray & Pillow:** Para la ejecución persistente en la bandeja del sistema (System Tray)[cite: 1, 2].
* **Winreg:** Para la manipulación del registro de Windows y el inicio automático[cite: 1, 2].
* **JSON:** Para la persistencia ligera de datos locales[cite: 1, 2].

---
Desarrollado por **J.Q.S. (Zapoide)**[cite: 1, 2].
