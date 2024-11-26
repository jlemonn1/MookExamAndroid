# 🌱 **EXAMEN: Gestión de Productos en un Growshop**  

---

## **📚 Contexto**  
Este examen pertenece a la asignatura **Programación Multimedia para Dispositivos Móviles**. El objetivo es desarrollar una aplicación móvil en **Android Studio** para gestionar los productos disponibles en un **growshop**.  

La aplicación permitirá registrar productos, actualizar su disponibilidad, visualizar la lista de productos y eliminar aquellos que ya no estén en stock. Toda la información será gestionada **en memoria**, sin persistencia en esta versión inicial.  

---

## **📋 Requisitos del examen**  

### 1️⃣ **Características del sistema**  
- **Registro de productos:**  
  Los productos deben registrarse con los siguientes datos:  
  - Nombre del producto 🌿  
  - Categoría (fertilizantes, semillas, accesorios) 🛠️  
  - Estado inicial: "Disponible" ✅  

- **Gestión de disponibilidad:**  
  El personal del growshop debe poder actualizar el estado de un producto a:  
  - "Agotado" ❌  
  - "Próximamente disponible" 🕒  

- **Visualización:**  
  La aplicación debe mostrar la lista de productos registrados, con un límite máximo de **20 registros visibles**.  

- **Límites y validaciones:**  
  - Si se alcanzan los 20 productos registrados, se debe mostrar un mensaje de advertencia ⚠️.  
  - Los productos también podrán eliminarse cuando ya no sean relevantes.  

---

### 2️⃣ **Modelo de datos**  
El modelo se define con las siguientes propiedades:  
```java
public class Producto {
    private String nombre;     // Nombre del producto
    private String categoria;  // Categoría (fertilizantes, semillas, accesorios)
    private String estado;     // Estado actual (inicia como "Disponible")
}
```  
Los objetos se almacenarán en un `ArrayList<Producto>` y se realizarán operaciones para agregar, actualizar y eliminar productos.  

---

### 3️⃣ **Consideraciones técnicas**  
💡 **Buenas prácticas:**  
- Organiza el proyecto siguiendo la estructura estándar de Android Studio:  
  - **`activities:`** Para las pantallas principales.  
  - **`models:`** Para las clases del modelo (`Producto`).  
  - **`layouts:`** Archivos XML para diseñar las vistas.  
  - **`menu:`** Elementos de navegación como botones o íconos.  
  - **`drawable:`** Recursos gráficos como imágenes o íconos.  

- Usa el archivo **strings.xml** para manejar textos reutilizables.  
- Diseña una interfaz amigable que permita a los usuarios navegar y gestionar los productos fácilmente.  

---

## **💻 Tareas del examen**  

1. **✍️ Análisis del sistema:**  
   - Define las pantallas necesarias para implementar las funcionalidades solicitadas.  
   - Describe la funcionalidad principal de cada pantalla de forma breve.  

2. **🛠️ Diseño del proyecto:**  
   - Diseña el modelo de datos y la estructura del proyecto en Android Studio.  
   - Organiza correctamente los archivos en sus directorios correspondientes.  

3. **👨‍💻 Implementación:**  
   - Desarrolla la aplicación móvil en Android Studio.  
   - Implementa todas las funcionalidades cumpliendo con los requisitos indicados.  

---

**🌟 ¡Éxito en tu desarrollo!** 🚀
