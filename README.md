# Laboratorio 2 — Tipos de datos, variables y expresiones

Este es tu repositorio del laboratorio 2. La hoja del laboratorio, con el contexto, los pasos y las
pistas de cada ejercicio, está en Moodle.

## Qué hay aquí

| Fichero | Ejercicio |
|---|---|
| `exercise_01_phone.py` | Validador de número de teléfono |
| `exercise_02_dni.py` | Letra del DNI |
| `exercise_03_wifi_password.py` | Clave WiFi segura |
| `exercise_04_palindrome.py` | Detector de palíndromos |
| `check.py` | Comprueba tus ejercicios con los ejemplos de la hoja |

Cada fichero de ejercicio empieza con un comentario. Escribe tu programa debajo. No cambies la
carpeta `.grader/`.

## Antes de entregar: comprueba

En VS Code: **Terminal → Ejecutar tarea… → Comprobar mis ejercicios**. O en el terminal:

```bash
python check.py        # todos los ejercicios
python check.py 2      # solo el ejercicio 2
```

`check.py` ejecuta tus programas con las entradas de los ejemplos de la hoja y compara tu
salida con la del ejemplo. Si algo falla, te enseña la primera línea distinta, con los espacios
marcados con `·`, y la columna en la que difiere.

Una prueba comprueba el texto, los espacios de alineación y los valores `True` y `False`. Si tu
salida tiene un espacio de más, la prueba falla.

## Cómo se entrega

Cada vez que haces `push`, tu trabajo queda entregado. Haz un commit cada vez que termines un
ejercicio:

```bash
git add exercise_01_phone.py
git commit -m "Ejercicio 1: validador de teléfono"
git push
```

## Dónde ves tu corrección

El corrector de la asignatura pasa las mismas pruebas que `check.py` a lo que has subido. Unos
minutos después de tu `push`, en la página de tu repositorio, en **Releases**, aparece una
**Corrección** con el resultado de cada prueba. Si una prueba falla, la corrección muestra tu
salida, la salida esperada y dónde difieren.
