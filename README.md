# Laboratorio 2 — Tipos de datos, variables y expresiones

Este es tu repositorio del laboratorio 2. La hoja del laboratorio, con el contexto, los pasos y las
pistas de cada ejercicio, está en Moodle.

## Qué hay aquí

| Fichero | Ejercicio |
|---|---|
| `ejercicio_01_telefono.py` | Validador de número de teléfono |
| `ejercicio_02_dni.py` | Letra del DNI |
| `ejercicio_03_clave_wifi.py` | Clave WiFi segura |
| `ejercicio_04_palindromo.py` | Detector de palíndromos |
| `comprobar.py` | Comprueba tus ejercicios con los ejemplos de la hoja |

Cada fichero de ejercicio empieza con un comentario. Escribe tu programa debajo. No cambies la
carpeta `.corrector/`.

## Antes de entregar: comprueba

En VS Code: **Terminal → Ejecutar tarea… → Comprobar mis ejercicios**. O en el terminal:

```bash
python comprobar.py        # todos los ejercicios
python comprobar.py 2      # solo el ejercicio 2
```

`comprobar.py` ejecuta tus programas con las entradas de los ejemplos de la hoja y compara tu
salida con la del ejemplo. Si algo falla, te enseña la primera línea distinta, con los espacios
marcados con `·`, y la columna en la que difiere.

Una prueba comprueba el texto, los espacios de alineación y los valores `True` y `False`. Si tu
salida tiene un espacio de más, la prueba falla.

## Cómo se entrega

Cada vez que haces `push`, tu trabajo queda entregado. Haz un commit cada vez que termines un
ejercicio:

```bash
git add ejercicio_01_telefono.py
git commit -m "Ejercicio 1: validador de teléfono"
git push
```

## Dónde ves tu corrección

El corrector de la asignatura pasa las mismas pruebas que `comprobar.py` a lo que has subido. Unos
minutos después de tu `push`, en la página de tu repositorio, en **Releases**, aparece una
**Corrección** con el resultado de cada prueba. Si una prueba falla, la corrección muestra tu
salida, la salida esperada y dónde difieren.
