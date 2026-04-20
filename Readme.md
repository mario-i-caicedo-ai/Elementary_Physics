from weasyprint import HTML

# Contenido del archivo Markdown
md_content = """# Physics for Poets: Training the Reason

Bienvenido a este repositorio. Este espacio está dedicado al enfoque conceptual de la física, conocido en muchas instituciones académicas de los Estados Unidos como **"Physics for Poets"**.

### Propósito del Repositorio
A lo largo de mi trayectoria docente, siempre he abogado en contra del modelo educativo de la "caja negra". Entender la física no consiste en memorizar fórmulas o realizar cálculos mecánicos; consiste en comprender la **estructura** del universo.

Este repositorio sirve como un puente entre el riguroso mundo de las leyes físicas y la mente inquisitiva del humanista. Aquí no solo resolvemos problemas; exploramos la historia, el pensamiento clásico y la belleza inherente de las leyes que gobiernan nuestra realidad — desde los diálogos de Galileo hasta la elegancia de la mecánica newtoniana.

### Lo que encontrarás aquí:
* **Marcos Conceptuales:** Materiales diseñados para construir una estructura mental sólida.
* **Contexto Histórico:** Anécdotas y citas de los gigantes que prepararon el camino.
* **Aprendizaje Estructural:** Recursos enfocados en "entrenar la razón" más que en simplemente proporcionar respuestas.

Como suelo decir a mis alumnos: la física es la poesía de la realidad, escrita en el lenguaje de la lógica.

---
*Compilado y organizado por el Dr. Mario I. Caicedo.*
"""

# Guardar el contenido en un archivo .md
with open('README.md', 'w', encoding='utf-8') as f:
    f.write(md_content)

print("Archivo README.md generado con éxito.")
