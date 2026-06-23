# PFO2: Evaluación de Agentes de IA en el Desarrollo Frontend

Este proyecto forma parte de la práctica PFO2 del IFTS N.°29, cuyo objetivo es evaluar y comparar la capacidad de distintos agentes de Inteligencia Artificial (Codex y Cursor) para generar una Landing Page profesional siguiendo instrucciones precisas de ingeniería de prompts.

## Autor
- **Nombre:** Gabriela Gonzalez
- **Materia:** [Nombre de la materia]
- **Fecha de entrega:** 26/06/2026

## Acceso al Proyecto
Repositorio GitHub: [https://github.com/melinya-byte/pfo2-evaluacion-ia](https://github.com/melinya-byte/pfo2-evaluacion-ia)
 **Vercel:** [Link a tu Vercel aquí]

## Prompt Maestro Utilizado
Para asegurar la consistencia en los resultados, se utilizó la siguiente instrucción en ambos agentes. El prompt fue generado por Gemini AI a partir de instrucciones que le ingresara. Este primer prompt funciono adecuadamente en el agente Codex. En cambio al probarlo en Cursor se produjo un loop. Se procedió a la optimización del prompt, tras lo cual Cursor fue capaz de cumplir con lo especificado.

**Prompt Maestro que funcionó en Codex**

> *# Role
Actúa como un Ingeniero Senior de Frontend especializado en UI/UX con dominio en tecnologías modernas (HTML5, Tailwind CSS y JavaScript moderno). Tu objetivo es desarrollar una Landing Page de alta conversión, estética, moderna y totalmente responsiva.

# Contexto del Proyecto
Debes generar una estructura web completa que cumpla con los estándares de diseño actuales: diseño limpio, tipografía legible, uso estratégico de espacios en blanco y una paleta de colores vibrante pero profesional.

# Especificaciones Técnicas
1. Stack: HTML5 y Tailwind CSS (vía CDN para facilitar el despliegue).
2. Responsividad: Mobile-first. Debe verse impecable en móviles, tablets y escritorios.
3. Estilos:
   - Usa una paleta de colores vibrante pero coherente (ej: gradientes sutiles, sombras suaves "glassmorphism" en elementos clave).
   - Implementa transiciones suaves (hover effects) en botones y enlaces.
   - Tipografía sans-serif moderna (tipo Inter o Poppins).

# Estructura Requerida (Landing Page)
Debes implementar las siguientes secciones de forma jerárquica:
1. Header: Menú de navegación sticky con logo a la izquierda y enlaces a la derecha (Mobile menu toggle necesario).
2. Hero Section: Título impactante (H1), subtítulo descriptivo, botón de CTA con gradiente y una imagen de fondo o elemento visual dinámico.
3. Sobre Nosotros: Descripción breve, enfocada en valor al cliente.
4. Servicios: Grid de 3 tarjetas (card) con iconos y descripciones.
5. Testimonios: Carrusel o grid de 3 tarjetas con diseño limpio.
6. Formulario de Contacto: Maquetado visual profesional (inputs con bordes redondeados, label claro).
7. Footer: Links a redes sociales, copyright y links legales básicos.

# Reglas de Ejecución (Restricciones)
- Entregar una solución completa y funcional en la primera iteración.
- Asegura que el código sea semántico y optimizado.
- No incluyas scripts pesados; usa CSS para las animaciones donde sea posible.



# Resultado Esperado
Genera el código en un único archivo HTML que contenga el CSS necesario en un tag <style> y los scripts en <script>.

**Prompt optimizado para Cursor**

# Role
Actúa como un Ingeniero Senior de Frontend. Tu tarea es generar una Landing Page profesional, estética y responsiva, siguiendo las mejores prácticas de UI/UX.

# Contexto y Estructura
Crea una Landing Page completa utilizando un único archivo HTML. Todo el CSS debe estar contenido en etiquetas <style> y toda la lógica JS necesaria en etiquetas <script>. 
Estructura obligatoria:
1. Header (con menú navegación sticky).
2. Hero Section (H1, CTA, visual dinámico).
3. Sobre Nosotros.
4. Servicios (Grid de 3 tarjetas).
5. Testimonios (Grid de 3 tarjetas).
6. Formulario de contacto (Solo maquetado).
7. Footer (Redes sociales y legal).

# Especificaciones Técnicas
- Stack: HTML5 + Tailwind CSS (vía CDN oficial de Tailwind).
- Responsividad: Mobile-first.
- Diseño: Usa paleta vibrante, efectos de glassmorphism y transiciones hover suaves.
- Tipografía: Sans-serif moderna (Inter/Poppins).

# REGLAS DE EJECUCIÓN (CRÍTICO)
1. NO inicies procesos de auto-iteración ni mejora continua tras la primera generación.
2. Genera el código completo en UNA SOLA RESPUESTA.
3. Si el código es extenso, no te detengas; escribe la totalidad del archivo de principio a fin.
4. NO modifiques, corrijas ni re-escribas el código una vez generado.
5. OBJETIVO: Entregar un archivo funcional, limpio y listo para implementar. 
6. DETENTE inmediatamente al terminar la etiqueta </html>.


## Comparativa de Resultados

### 1. Landing Page - Codex
- **Archivo:** `/indexcodex.html`
- **Observaciones:** [Aquí puedes poner una breve línea: ej. "El código fue generado de forma directa y cumplió con la estructura solicitada sin iteraciones."]

### 2. Landing Page - Cursor
- **Archivo:** `/indexcursor.html`
- **Observaciones:** [Aquí puedes poner una breve línea: ej. "El agente mostró gran precisión en el uso de Tailwind CSS y aplicó los efectos visuales de glassmorphism de manera efectiva."]

## Metodología
Se ha respetado estrictamente la restricción de **no modificar el código generado manualmente**, permitiendo evaluar la capacidad de resolución de problemas, semántica y adherencia a los estándares de UI/UX de cada agente de manera independiente.

## Estructura del Repositorio
- `index.html`: Portada principal con acceso a las landing pages.
- `indexcodex.html`: Resultado generado por Codex.
- `indexcursor.html`: Resultado generado por Cursor.
- `README.md`: Documentación del proyecto.