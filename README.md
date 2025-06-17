
# 💻 Estimador de Presupuesto para Desarrollo de Videojuegos Indie

## 🎮 Descripción

Este programa en Java permite a estudios de desarrollo de videojuegos indie, como **IndieDreams**, estimar el presupuesto de su próximo proyecto. Calcula el costo total considerando horas de desarrollo, tarifas por hora, licencias de software y gastos adicionales. Además, incluye honorarios administrativos e imprevistos para una estimación más precisa.

---

## 🐞 Errores Encontrados y Correcciones

### 1. **Uso Incorrecto de `Scanner`**

- **Problema:** Se intentaba crear una instancia de `Scanner` con `new scanner(system)`, lo cual es incorrecto.
- **Solución:** Se corrigió a `new Scanner(System.in)` para leer la entrada estándar del usuario.

### 2. **Errores de Sintaxis en la Captura de Datos**

- **Problema:** Se utilizaban métodos incorrectos como `nextline()` y `nex()`, y se omitían paréntesis en `System.out.print`.
- **Solución:** Se reemplazaron por `nextLine()` y se añadieron los paréntesis faltantes en los métodos de impresión.

### 3. **Declaración Incorrecta de Variables**

- **Problema:** Se declararon variables como `tarifaBase = 50,0,0;`, lo cual no es válido en Java.
- **Solución:** Se corrigió a `tarifaBase = 50.0;` para asignar un valor numérico válido.

### 4. **Falta de Inicialización de Variables**

- **Problema:** Variables como `horasProyecto1`, `horasProyecto2`, `horasProyecto3` no se inicializaban antes de su uso.
- **Solución:** Se añadió la captura de datos para estas variables antes de su utilización en los cálculos.

### 5. **Errores Tipográficos en Variables y Métodos**

- **Problema:** Se encontraron errores tipográficos como `bonusCliene1` y `horasProyec1`.
- **Solución:** Se corrigieron a `bonusCliente1` y `horasProyecto1` respectivamente.

### 6. **Cálculos Incorrectos de Pagos y Totales**

- **Problema:** Se realizaban cálculos con variables no inicializadas o mal declaradas.
- **Solución:** Se aseguraron las inicializaciones correctas y se ajustaron los cálculos para reflejar los valores adecuados.

---

## 🧠 Uso de Inteligencia Artificial

Para mejorar la calidad del código y corregir errores, se utilizó **ChatGPT** de OpenAI. Esta herramienta asistió en:

- Identificación de errores de sintaxis y lógica.
- Sugerencias para mejorar la estructura del código.
- Propuestas para optimizar el flujo de entrada y salida de datos.

---

## 📚 Fuentes Consultadas

- [Documentación oficial de Java](https://docs.oracle.com/javase/8/docs/api/)
- [Guía para crear READMEs Profesionales](https://github.com/Organization-DevXP/Guia-para-crear-READMEs-Profesionales)
- [Cómo escribir un buen archivo README](https://barrosjss.medium.com/c%C3%B3mo-escribir-un-buen-archivo-readme-80afd95db46b)
- [Crea un buen README para tu proyecto en Github](https://www.corecode.school/blog/como-crear-un-buen-readme)

---

## 🚀 Instalación y Uso

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tuusuario/estimador-presupuesto-videojuegos.git

