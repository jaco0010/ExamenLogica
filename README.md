
# 🧑‍💻 Calculadora de Tarifas para Programadores Freelance

Este programa en Java permite calcular la tarifa por hora de un programador freelance, teniendo en cuenta su nivel de experiencia, años de experiencia, tipo de contrato y bonos adicionales por cliente. Además, genera un reporte detallado con la información ingresada y el cálculo final.

## 🛠️ Errores Encontrados y Corregidos

### 1. **Uso incorrecto de `Scanner`** ❌

**Problema:**  
Se instanciaba el objeto `Scanner` de manera incorrecta: `new scanner(system)`.

**Solución:**  
Se corrigió a `new Scanner(System.in)`, que es la forma adecuada de crear un objeto `Scanner` para leer desde la entrada estándar.

### 2. **Método `nextLine()` no funcionando correctamente después de `nextInt()`** 🔄

**Problema:**  
Al usar `nextInt()` seguido de `nextLine()`, el método `nextLine()` no capturaba la entrada correctamente, debido a que `nextInt()` no consume el salto de línea (`\n`) dejado por el Enter.

**Solución:**  
Se añadió una llamada adicional a `sc.nextLine()` después de cada `nextInt()` para consumir el salto de línea pendiente.

### 3. **Errores de sintaxis y tipográficos** 📝

**Problema:**  
Existen varios errores de sintaxis y tipográficos, como:
- Uso incorrecto de comas en lugar de puntos en valores decimales.
- Métodos mal escritos como `nextline()` en lugar de `nextLine()`.
- Variables no declaradas o mal nombradas.

**Solución:**  
Se corrigieron todos los errores de sintaxis y se estandarizó el uso de la convención de nomenclatura en Java.

### 4. **Cálculos incorrectos en el pago por proyecto** 💰

**Problema:**  
Las fórmulas para calcular el pago por proyecto contenían errores de sintaxis y lógica, como el uso de variables no declaradas o mal nombradas.

**Solución:**  
Se revisaron y corrigieron todas las fórmulas de cálculo, asegurando que las variables estén correctamente declaradas y utilizadas.

### 5. **Falta de importación de clases necesarias** 📦

**Problema:**  
No se importaban las clases necesarias para el funcionamiento del programa, como `Scanner` y `LocalDate`.

**Solución:**  
Se añadieron las importaciones correspondientes al inicio del archivo:


