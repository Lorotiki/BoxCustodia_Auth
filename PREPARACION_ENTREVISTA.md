# 📋 RESUMEN DE PREPARACIÓN PARA ENTREVISTA TÉCNICA

## ✅ Archivos Generados

### 1. **PREGUNTERO_TECNICO.md** (26 KB)
   - 120 preguntas técnicas distribuidas en 12 categorías
   - Cada pregunta con respuesta clara y concisa
   - Categorías:
     - Teóricas Simples (10)
     - Teóricas Medias (10)
     - Teóricas Complejas (10)
     - Diseño Simples (10)
     - Diseño Medias (10)
     - Diseño Complejas (10)
     - Técnicas Simples (10)
     - Técnicas Medias (10)
     - Técnicas Complejas (10)
     - Cuestiones de Código Simples (10)
     - Cuestiones de Código Medias (10)
     - Cuestiones de Código Complejas (10)

### 2. **PREGUNTERO_TECNICO.html** (40 KB)
   - Versión visual del preguntero en HTML
   - Estilos CSS aplicados
   - Listo para visualizar en navegador
   - Convertible a PDF con Print

### 3. **mock_interview.py**
   - Simulador interactivo de entrevista técnica
   - Preguntas aleatorias seleccionables
   - Scoring automático
   - Feedback en tiempo real
   
   **Uso:**
   ```bash
   python3 mock_interview.py
   ```

### 4. **GUIA_PDF.md**
   - Instrucciones para convertir HTML a PDF
   - 4 opciones diferentes
   - Opción recomendada: Google Chrome/Print

### 5. **generate_html.py**
   - Convierte MD a HTML automáticamente
   - Útil si necesitas regenerar

### 6. **convert_to_pdf.py**
   - Intenta convertir a PDF de forma automática
   - Requiere reportlab instalado

---

## 🎯 CÓMO USAR

### Paso 1: Revisar y Estudiar
```bash
# Leer en la terminal
cat PREGUNTERO_TECNICO.md | less

# O abrir en editor
code PREGUNTERO_TECNICO.md
```

### Paso 2: Practicar con Mock Interview
```bash
python3 mock_interview.py
```
- Selecciona nivel de dificultad
- Selecciona cantidad de preguntas
- Responde mentalmente
- Verifica tu respuesta
- Obtén scoring

### Paso 3: Convertir a PDF (Opcional)
```bash
# Opción más fácil: Abre en navegador
open PREGUNTERO_TECNICO.html  # macOS
# o
xdg-open PREGUNTERO_TECNICO.html  # Linux
# o
start PREGUNTERO_TECNICO.html  # Windows

# Luego: Ctrl+P (o Cmd+P) → Guardar como PDF
```

---

## 📚 CONTENIDO POR NIVEL

### NIVEL SIMPLE (30 preguntas)
Conceptos fundamentales:
- ¿Qué es una API REST?
- ¿Qué hace Spring Boot?
- ¿Qué es JPA?
- ¿Qué es un DTO?
- etc.

**Dificultad:** Básico-Intermedio  
**Uso:** Calentamiento, preguntas iniciales  
**Tiempo esperado:** ~30 minutos

### NIVEL MEDIO (30 preguntas)
Conceptos intermedios:
- Inyección de Dependencias
- Transacciones
- Paginación
- Validaciones
- etc.

**Dificultad:** Intermedio  
**Uso:** Preguntas principales  
**Tiempo esperado:** ~45 minutos

### NIVEL AVANZADO (30 preguntas)
Conceptos complejos:
- N+1 Problem
- Lazy Loading
- Concurrencia
- Soft Deletes
- EntityGraph
- etc.

**Dificultad:** Intermedio-Avanzado  
**Uso:** Preguntas de profundidad  
**Tiempo esperado:** ~60 minutos

### CÓDIGO (30 preguntas)
Preguntas sobre el proyecto TaskFlow:
- Decisiones de diseño
- Implementaciones específicas
- Patrones usados
- etc.

**Dificultad:** Variable  
**Uso:** Preguntas del proyecto real  
**Tiempo esperado:** ~45 minutos

---

## 💡 ESTRATEGIA DE PREPARACIÓN

### Semana 1: Fundamentos
- [ ] Lee PREGUNTERO_TECNICO.md completo
- [ ] Subraya conceptos nuevos
- [ ] Anota dudas

### Semana 2: Refuerzo
- [ ] Corre `mock_interview.py` diariamente
- [ ] Comienza con nivel SIMPLE
- [ ] Progresa a nivel MEDIO
- [ ] Anota patrones en respuestas

### Semana 3: Profundidad
- [ ] Practica nivel AVANZADO
- [ ] Conecta teoría con proyecto
- [ ] Prepara ejemplos del código
- [ ] Revisa casos edge

### Semana 4: Simulación
- [ ] Mock interview completo (90 minutos)
- [ ] Cronómetra tus respuestas
- [ ] Pide feedback a compañeros
- [ ] Refina respuestas débiles

---

## 🎤 TIPS PARA LA ENTREVISTA

### Antes:
✓ Duerme bien  
✓ Ten agua cerca  
✓ Revisa el repo del proyecto en rama main  
✓ Ten la terminal lista  
✓ Respira profundo  

### Durante:
✓ Escucha completa la pregunta antes de responder  
✓ Piensa 3 segundos antes de hablar  
✓ Sé honesto si no sabes  
✓ Muestra el pensamiento ("porque...")  
✓ Usa ejemplos del proyecto cuando aplique  
✓ Mantén contacto visual (si es presencial)  

### Respuestas efectivas:
```
"La razón es [concepto fundamental].
Por ejemplo, en TaskFlow [ejemplo específico].
Esto mejora [beneficio]: [impacto]."
```

### Si no sabes:
```
"No estoy seguro, pero puedo deducir que...
¿Puedo investigar y volver con la respuesta?"
```

---

## 🔗 REFERENCIAS RÁPIDAS

### URLs en GitHub
- Repo: https://github.com/Lorotiki/BoxCustodia_Task
- README: [README.md](README.md)
- API Endpoints: [Controllers](src/main/java/com/taskflow/controller/)

### Archivos del Proyecto
- Modelos: [model/](src/main/java/com/taskflow/model/)
- Controllers: [controller/](src/main/java/com/taskflow/controller/)
- Services: [service/](src/main/java/com/taskflow/service/)
- DTOs: [dto/](src/main/java/com/taskflow/dto/)
- BD: [init.sql](init.sql)

---

## 🚀 COMANDOS ÚTILES

### Para el Mock Interview
```bash
# Ejecutar
python3 mock_interview.py

# Con mi puntuación
python3 mock_interview.py --score

# Todas las preguntas de una categoría
python3 mock_interview.py --category "Teóricas Simples"
```

### Para el Proyecto
```bash
# Compilar
mvn clean compile

# Ejecutar
mvn spring-boot:run

# Acceder a Swagger
# http://localhost:8080/swagger-ui.html

# Tests (si existen)
mvn test
```

---

## 📊 MATRIZ DE CONFIANZA

Antes de la entrevista, evalúa tu confianza:

| Categoría | Confianza (1-5) | Temas a Reforzar |
|-----------|-----------------|------------------|
| Teóricas Simple | ☆☆☆☆☆ | ? |
| Teóricas Media | ☆☆☆☆☆ | ? |
| Teóricas Compleja | ☆☆☆☆☆ | ? |
| Diseño Simple | ☆☆☆☆☆ | ? |
| Diseño Media | ☆☆☆☆☆ | ? |
| Diseño Compleja | ☆☆☆☆☆ | ? |
| Técnica Simple | ☆☆☆☆☆ | ? |
| Técnica Media | ☆☆☆☆☆ | ? |
| Técnica Compleja | ☆☆☆☆☆ | ? |
| Código Simple | ☆☆☆☆☆ | ? |
| Código Media | ☆☆☆☆☆ | ? |
| Código Compleja | ☆☆☆☆☆ | ? |

---

## ✨ PRÓXIMOS PASOS

1. **Entra al HTML:** `open PREGUNTERO_TECNICO.html`
2. **Practica:** `python3 mock_interview.py`
3. **Convierte a PDF:** Chrome/Print → "Guardar como PDF"
4. **Descarga del repo:** Comparte README.md y este preguntero
5. **Antes de entrevista:** Repasa el día anterior

---

**¡Mucho éxito en tu entrevista! 🚀**

*Preguntero generado: 24 de Febrero de 2026*
*Proyecto: TaskFlow - Spring Boot 4.0.2 + PostgreSQL*
*Total: 120 preguntas + Simulador interactivo + Herramientas de conversión*
