# Node Plantilla

Proyecto base desarrollado con Node.js y Express para crear APIs backend organizadas y escalables.

## Objetivo

Crear una estructura inicial de proyecto utilizando:

* Node.js
* Express
* Nodemon
* Git y GitHub

El proyecto sirve como plantilla para futuros desarrollos backend.

---

# Tecnologías utilizadas

* Node.js
* Express
* Nodemon
* Git
* GitHub

---

# Instalación

Clonar el repositorio:

```bash id="8skhl8"
git clone https://github.com/TU-USUARIO/node-plantilla.git
```

Entrar al proyecto:

```bash id="wlc2v5"
cd node-plantilla
```

Instalar dependencias:

```bash id="n9m2bh"
npm install
```

---

# Scripts disponibles

## Ejecutar proyecto

```bash id="w9o6fq"
npm start
```

## Ejecutar en modo desarrollo con Nodemon

```bash id="gd6juq"
npm run dev
```

---

# Estructura del proyecto

```txt id="xjk8vw"
node-plantilla/
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
└── src/
    ├── index.js
    ├── controllers/
    ├── services/
    ├── models/
    ├── routes/
    ├── middlewares/
    └── config/
```

---

# Explicación de carpetas

## controllers/

Contiene los controladores encargados de procesar las peticiones y respuestas de la aplicación.

---

## services/

Incluye la lógica de negocio y procesos internos del sistema.

---

## models/

Define los modelos o estructuras de datos utilizados en la aplicación.

---

## routes/

Contiene las rutas o endpoints de la API.

---

## middlewares/

Incluye middlewares personalizados para validaciones, autenticación o manejo de errores.

---

## config/

Almacena configuraciones generales del proyecto.

---

## index.js

Archivo principal encargado de iniciar el servidor Express.

---

# Endpoint principal

## GET /

Respuesta:

```txt id="s8fuf0"
API base
```

---

# Funcionamiento

El proyecto inicia un servidor Express en:

```txt id="t4x0j5"
http://localhost:3000
```

Permitiendo verificar el funcionamiento básico de la API.

---

# Control de versiones

El proyecto utiliza Git para el control de versiones y GitHub como repositorio remoto.

---

# Autor

Wanda Hernández
