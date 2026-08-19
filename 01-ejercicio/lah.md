# Permisos de Archivos y Directorios

Aquí tienes la tabla convertida a formato Markdown con la representación de permisos y su equivalencia octal:

| Nombre / Elemento | Permisos (Simbólico) | Permisos (Octal) |
| :--- | :---: | :---: |
| `README.TXT` | `rw-rw-r--` | **664** |
| `docs` | `rwxrwxr-x` | **775** |
| `src` | `rwxrwxr-x` | **775** |
| `logs` | `rwxrwxr-x` | **775** |

---

### Guía de Valores Octales

* **`r`** (Read / Lectura) = **4**
* **`w`** (Write / Escritura) = **2**
* **`x`** (Execute / Ejecución) = **1**

#### Desglose de Cálculo:
* **`6`** = `r` (4) + `w` (2) = Lectura y escritura
* **`7`** = `r` (4) + `w` (2) + `x` (1) = Lectura, escritura y ejecución
* **`5`** = `r` (4) + `x` (1) = Lectura y ejecución
* **`4`** = `r` (4) = Solo lectura
