
# Práctica: AWS con Asciinema  

**Alumno:** Daniel Omar González Martínez  
**Carrera:** Ingeniería en Sistemas Computacionales  
**Materia:** (Nombre de la materia que corresponda)  
**Fecha:** 04 de septiembre de 2025  

---

## 🎯 Objetivo
El estudiante será capaz de crear una instancia EC2 en AWS Academy, instalar Asciinema, grabar una sesión de actualización del sistema operativo con comandos básicos de Linux y finalmente compartir el enlace de la grabación.  

---

## 🖥️ Procedimiento

### 1. Creación de la instancia EC2
- Accedí a **AWS Academy**.  
- Creé una instancia **EC2 Ubuntu LTS**.  
- Tipo de instancia: **t2.micro** (recomendado para prácticas básicas).  

### 2. Conexión SSH
- Me conecté desde el panel web de AWS Academy usando la opción **Conexión remota SSH**.  

### 3. Instalación de paquetes
Ejecuté los siguientes comandos para actualizar e instalar las herramientas:  

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install asciinema figlet -y
```

Verificación de instalación:  
```bash
asciinema --version
```

### 4. Grabación con Asciinema
Inicié la grabación con:  
```bash
asciinema rec
```

Dentro de la grabación ejecuté:  
```bash
echo "Práctica de Asciinema por Daniel Omar González Martínez"
sudo apt update
sudo apt upgrade -y
```

Finalicé la grabación con **Ctrl+D**.  

### 5. Enlace de la grabación
La práctica quedó registrada en el siguiente enlace de **Asciinema**:  

[![asciicast](https://asciinema.org/a/uNEZCsvmDl0fNQchxXoVMMnDT.svg)](https://asciinema.org/a/uNEZCsvmDl0fNQchxXoVMMnDT)  

---


