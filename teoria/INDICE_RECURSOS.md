# 📚 Índice de Recursos - Preparación Técnica TaskFlow

## 🎯 OPCIÓN RÁPIDA (Lee primero)

**Si tienes poco tiempo:**
1. Lee [PREPARACION_ENTREVISTA.md](PREPARACION_ENTREVISTA.md) (7 minutos)
2. Abre [PREGUNTERO_TECNICO.html](PREGUNTERO_TECNICO.html) en navegador
3. Ejecuta `python3 mock_interview.py` para practicar

---

## 📖 ARCHIVOS PRINCIPALES

### 1. [PREGUNTERO_TECNICO.md](PREGUNTERO_TECNICO.md) ⭐ **RECOMENDADO**
**Tipo:** Documento de estudio  
**Tamaño:** 26 KB  
**Contenido:** 120 preguntas técnicas con respuestas  
**Organización:** 12 categorías (Simple, Medio, Avanzado)  
**Mejor para:** Lectura profunda, referencias

```bash
# Ver en terminal
cat PREGUNTERO_TECNICO.md | less

# O abrir en editor
code PREGUNTERO_TECNICO.md
```

---

### 2. [PREGUNTERO_TECNICO.html](PREGUNTERO_TECNICO.html) 🎨 **VISUAL**
**Tipo:** Página web interactiva  
**Tamaño:** 40 KB  
**Contenido:** Mismo que MD pero con estilos CSS  
**Mejor para:** Lectura visual, impresión

```bash
# Abrir en navegador
open PREGUNTERO_TECNICO.html      # macOS
xdg-open PREGUNTERO_TECNICO.html  # Linux
start PREGUNTERO_TECNICO.html     # Windows
```

---

### 3. [mock_interview.py](mock_interview.py) 🎮 **SIMULADOR**
**Tipo:** Aplicación interactiva Python  
**Contenido:** Simulador de entrevista técnica  
**Funcionalidad:** 
- Preguntas aleatorias
- Seleccionar dificultad
- Scoring automático
- Feedback en tiempo real

```bash
# Ejecutar
python3 mock_interview.py

# Pasos:
1. Selecciona categoría (1-5)
2. Selecciona cantidad de preguntas
3. Responde en voz alta
4. Presiona Enter para ver respuesta
5. Evalúa tu respuesta
```

---

### 4. [PREPARACION_ENTREVISTA.md](PREPARACION_ENTREVISTA.md) 📋 **GUÍA COMPLETA**
**Tipo:** Plan de estudio  
**Contenido:**
- Estrategia de 4 semanas
- Tips para entrevista
- Matriz de confianza
- Comandos útiles
- Referencias

**Recomendado leer primero**

---

### 5. [GUIA_PDF.md](GUIA_PDF.md) 📄 **CONVERSIÓN A PDF**
**Tipo:** Instrucciones  
**Contenido:** 4 formas diferentes de convertir a PDF
- Opción 1: Chrome Print ⭐ (más fácil)
- Opción 2: wkhtmltopdf
- Opción 3: Pandoc
- Opción 4: Servicios online

---

## 📁 ARCHIVOS AUXILIARES

- `generate_html.py` - Regenera el HTML desde MD
- `convert_to_pdf.py` - Intenta convertir a PDF (requiere reportlab)
- `README.md` - Información del proyecto TaskFlow
- `init.sql` - Script de base de datos

---

## 🗺️ DISTRIBUCIÓN DE CONTENIDO

### Por Categoría (120 preguntas):
```
Teóricas Simples           (10) ███░░░░░░░
Teóricas Medias            (10) ███░░░░░░░
Teóricas Complejas         (10) ███░░░░░░░
                              
Diseño Simples             (10) ███░░░░░░░
Diseño Medias              (10) ███░░░░░░░
Diseño Complejas           (10) ███░░░░░░░

Técnicas Simples           (10) ███░░░░░░░
Técnicas Medias            (10) ███░░░░░░░
Técnicas Complejas         (10) ███░░░░░░░

Cuestiones Código Simples  (10) ███░░░░░░░
Cuestiones Código Medias   (10) ███░░░░░░░
Cuestiones Código Complejas(10) ███░░░░░░░
```

### Por Nivel:
```
Nivel SIMPLE:     30 preguntas  (25%) - Fundamentos
Nivel MEDIO:      30 preguntas  (25%) - Aplicado
Nivel AVANZADO:   30 preguntas  (25%) - Profundo
Nivel CÓDIGO:     30 preguntas  (25%) - Proyecto
```

---

## ⏱️ PLAN DE ESTUDIO RECOMENDADO

### Semana 1: Teoría Básica
- [ ] Semana 1: Leer categorías "Simple"
- [ ] Ejecutar mock_interview.py con "Teóricas Simples" (5+ veces)
- [ ] Tomar notas de conceptos claves

### Semana 2: Conceptos Medios
- [ ] Leer categorías "Medias"
- [ ] Mock interview "Teóricas Medias" + "Diseño Medias"
- [ ] Conectar conceptos con el proyecto TaskFlow

### Semana 3: Temas Complejos
- [ ] Leer categorías "Complejas"
- [ ] Practicar todas las categorías
- [ ] Preparar ejemplos del código

### Semana 4: Simulación Full
- [ ] Mock interview integral (90 minutos)
- [ ] Revisar casos débiles
- [ ] Ensayo con feedback de compañeros

---

## 🎤 TIPS RÁPIDOS

### Antes de la Entrevista:
- ✓ Revisa conceptos de "Simples" la noche anterior
- ✓ Duerme 8 horas
- ✓ Ten el código del proyecto abierto
- ✓ Mejora tu conexión a internet

### Durante la Entrevista:
- ✓ Escucha completa la pregunta
- ✓ Respira y piensa 3 segundos
- ✓ Sé honesto si no sabes
- ✓ Muestra tu pensamiento ("porque...")
- ✓ Usa ejemplos del proyecto
- ✓ Ramifica en casos edge si es relevante

### Respuesta Modelo:
```
"La forma correcta es [concepto}.
La razón es que [principio}.
En TaskFlow, esto se aplica porque [ejemplo}.
El impacto es [beneficio}."
```

---

## 📞 COMANDO RÁPIDO PARA PRACTICAR

```bash
# Inicia aquí - Modal de práctica
python3 mock_interview.py

# Y luego abre para referencia
open PREGUNTERO_TECNICO.html
```

---

## ✨ PRÓXIMO PASO

**→ Empieza leyendo:** [PREPARACION_ENTREVISTA.md](PREPARACION_ENTREVISTA.md)  
**→ Luego practica:** `python3 mock_interview.py`  
**→ Finalmente revisa:** [PREGUNTERO_TECNICO.md](PREGUNTERO_TECNICO.md)

---

## 📊 RESUMEN

| Recurso | Tipo | Uso | Tiempo |
|---------|------|-----|--------|
| [PREGUNTERO_TECNICO.md](PREGUNTERO_TECNICO.md) | 📖 Documento | Estudio | 2-3 horas |
| [PREGUNTERO_TECNICO.html](PREGUNTERO_TECNICO.html) | 🎨 Web | Referencia | Flexible |
| [mock_interview.py](mock_interview.py) | 🎮 Script | Práctica | 15 min c/ sesión |
| [PREPARACION_ENTREVISTA.md](PREPARACION_ENTREVISTA.md) | 📋 Guía | Planificación | 15 min |
| [GUIA_PDF.md](GUIA_PDF.md) | 📄 Instrucciones | Conversión | 5 min |

---

**¡Estás listo! 🚀 Escoge tu punto de partida arriba.**
