# mockapiUsers
🛠️ Cómo crear una API simulada en MockAPI.io
Regístrate o inicia sesión

Visita https://mockapi.io/ y crea una cuenta gratuita o inicia sesión si ya tienes una.

Crea un nuevo proyecto

Haz clic en el botón "New Project" (Nuevo Proyecto).

Asigna un nombre a tu proyecto, por ejemplo, mockapiProducts, y haz clic en "Create" (Crear).

Agrega un recurso (Resource)

Dentro de tu proyecto, haz clic en "New Resource" (Nuevo Recurso).

Nombra el recurso como products y define el esquema con los siguientes campos:

name: tipo string

description: tipo string

price: tipo number

category: tipo string

image: tipo string (URL de la imagen)

stock: tipo number

Haz clic en "Create" (Crear) para guardar el recurso.

Genera datos simulados

Una vez creado el recurso, haz clic en él para acceder a su vista de datos.

Haz clic en el botón "Add" (Agregar) para añadir manualmente registros o utiliza la opción de generación automática para crear múltiples entradas con datos ficticios.

Accede a tu API

MockAPI.io generará automáticamente endpoints RESTful para tu recurso. Por ejemplo:

GET https://[tu_subdominio].mockapi.io/products – Obtener todos los productos

POST https://[tu_subdominio].mockapi.io/products – Crear un nuevo producto

GET https://[tu_subdominio].mockapi.io/products/{id} – Obtener un producto por ID

PUT https://[tu_subdominio].mockapi.io/products/{id} – Actualizar un producto por ID

DELETE https://[tu_subdominio].mockapi.io/products/{id} – Eliminar un producto por ID

Integra la API en tu aplicación

Utiliza herramientas como fetch, axios, Postman o cualquier cliente HTTP para consumir los endpoints de tu API simulada en tus aplicaciones frontend o backend.

📘 Recursos adicionales
Documentación oficial: https://docs.mockapi.io/

Tutorial en video: Cómo crear una API simulada para eCommerce

Project to Mock an API Rest catalog of Users

# mockapiUsers

**mockapiUsers** es una API simulada (mock) que proporciona un catálogo estático de usuarios en formato JSON. Este repositorio está diseñado para desarrolladores que necesitan datos de usuario falsos para pruebas, desarrollo frontend, simulaciones de API REST o presentaciones sin depender de una base de datos real o conexión externa.

Cada usuario contiene los campos: `id`, `email`, `first_name`, `last_name` y `avatar`, permitiendo construir interfaces realistas como listas de usuarios, perfiles, validadores de formularios o pruebas de consumo de endpoints en aplicaciones frontend y backend.

Las imágenes de avatar están alojadas en la carpeta `/assets` del repositorio, y la estructura del JSON está inspirada en [reqres.in](https://reqres.in), con datos ampliados y personalizables.

## 🚀 Cómo empezar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/marcotrejolemus/mockapiUsers.git
   cd mockapiUsers


---

### 📁 `db.json`

```json
{
  "users": [
    {
      "id": 1,
      "email": "george.bluth@reqres.in",
      "first_name": "George",
      "last_name": "Bluth",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/george.png"
    },
    {
      "id": 2,
      "email": "janet.weaver@reqres.in",
      "first_name": "Weaver",
      "last_name": "Janet",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/janet.png"
    },
    {
      "id": 3,
      "email": "emma.wong@reqres.in",
      "first_name": "Wong",
      "last_name": "Emma",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/emma.png"
    },
    {
      "id": 4,
      "email": "eve.holt@reqres.in",
      "first_name": "Eve",
      "last_name": "Holt",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/eve.png"
    },
    {
      "id": 5,
      "email": "charles.morris@reqres.in",
      "first_name": "Charles",
      "last_name": "Morris",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/morris.png"
    },
    {
      "id": 6,
      "email": "tracey.ramos@reqres.in",
      "first_name": "Tracey",
      "last_name": "Ramos",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/tracey.png"
    },
    {
      "id": 7,
      "email": "jordan.miles@reqres.in",
      "first_name": "",
      "last_name": "",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/jordan.png"
    },
    {
      "id": 8,
      "email": "john.milton@reqres.in",
      "first_name": "John",
      "last_name": "Milton",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/milton.png"
    },
    {
      "id": 9,
      "email": "kyle.reese@reqres.in",
      "first_name": "Kyle",
      "last_name": "Reese",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/kyle.png"
    },
    {
      "id": 10,
      "email": "john.connor@reqres.in",
      "first_name": "John",
      "last_name": "Connor",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/connor.png"
    },
    {
      "id": 11,
      "email": "katherine.brewster@reqres.in",
      "first_name": "Katherine",
      "last_name": "Brewster",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/kat.png"
    },
    {
      "id": 12,
      "email": "sara.connor@reqres.in",
      "first_name": "Sara",
      "last_name": "Connor",
      "avatar": "https://github.com/marcotrejolemus/mockapiUsers/blob/main/assets/sara.png"
    }
  ]
}
