<p align="center">
  <img src="assets/logo.png" width="500">
</p>

# ORC – Dox sistema 

**Por HEXN | República de Colombia**

ORC es un sistema de consultas por terminal desarrollado en **Python**, con una interfaz estilo consola/hacker. Está diseñado para ejecutarse de forma simple, clara y directa desde la terminal, sin configuraciones complejas.

---

## 🚀 Características

- Interfaz  🔧
- Menú interactivo
- Consulta por **Cédula**
- Consulta por **Placa**
- Muestra toda la información devuelta en bloque
- Detección automática de datos faltantes
- Colores en consola
- Compatible con **PC** y **Termux** (Android)
- Auto-descarga de dependencias (no requiere instalación manual)

---

## 📦 Requisitos

- **Python 3.8** o superior
- Conexión a Internet
- No es necesario instalar librerías manualmente

---

## 🛠 Instalación

**Windows / Linux**

```bash
git clone https://github.com/HEXNCOLOMBIA/MODULO-DOX-COLOMBIA.git
cd MODULO-DOX-COLOMBIA
python orc_system.py
```

**Termux (Android)**

```bash
pkg update -y
pkg install python git -y
git clone https://github.com/HEXNCOLOMBIA/MODULO-DOX-COLOMBIA.git
cd MODULO-DOX-COLOMBIA
python orc_system.py
```

---

## 🧭 Uso

Al iniciar el sistema aparecerá un menú en consola:

```
1 → Consulta por Cédula
2 → Consulta por Placa
0 → Salir
```

El sistema pedirá el dato correspondiente y mostrará el resultado completo en pantalla.

---

## 📊 Resultados

- Los datos se muestran en un solo bloque
- Campos vacíos se marcan como **NO DISPONIBLE**
- Se listan los campos faltantes al final
- Se indica si la consulta fue exitosa ✅

---

## ⚠️ Aviso

Este proyecto es únicamente con fines **educativos**. El autor no se hace responsable del uso indebido. No se almacena información: todo se ejecuta localmente.

---

## 👨‍💻 Autor

**HEXN** – ORC (Organización de Investigación)

---

Si quieres, puedo añadir secciones adicionales como ejemplos de salida, estructura de archivos o instrucciones para pruebas automatizadas. 💡
