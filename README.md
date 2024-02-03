# DAWI-S3TLb1 | Eduardo Flores | T32311172

Laboratorio Semana 3

## Gestión de variables de archivo .env

- **\_USER**:
  Usuario de base de datos.
- **\_PASS**:
  Password de base de datos.
- **\_HOST**:
  Hosting de base de datos.
- **\_DBNAME**:
  Nombre de base de datos.
- **\_PORT**:
  Puerto de Conexión de base de datos.

## Gestión de Marca

### Insertar marca (POST)

- **Ruta**:
  http://localhost:4000/api/marca
- **Body**
  Body:
  {
  "descripcion": "Hiunday"
  }

### Modificar marca por ID (PUT)

- **Ruta**:
  http://localhost:4000/api/marca/1
- **Body**
  {
  "descripcion": "Hyundai"
  }

### Obtener todas las marcas ordenados por ID (GET)

- **Ruta**:
  http://localhost:4000/api/marca

### Obtener marca por ID (GET)

- **Ruta**:
  http://localhost:4000/api/marca/1

### Eliminar marca por ID (DELETE)

- **Ruta**:
  http://localhost:4000/api/marca/1

## Gestión de Modelo

### Insertar modelo (POST)

- **Ruta**:
  http://localhost:4000/api/modelo
- **Body**
  Body:
  {
  "descripcion": "607",
  "marca_id": 1
  }

### Modificar modelo por ID (PUT)

- **Ruta**:
  http://localhost:4000/api/modelo/1
- **Body**
  {
  "descripcion": "606",
  "marca_id": 1
  }

### Obtener todas los modelo ordenados por ID (GET)

- **Ruta**:
  http://localhost:4000/api/modelo

### Obtener modelo por ID (GET)

- **Ruta**:
  http://localhost:4000/api/modelo/1

### Eliminar modelo por ID (DELETE)

- **Ruta**:
  http://localhost:4000/api/modelo/1

## Gestión de Vehículo

### Insertar vehículo (POST)

- **Ruta**:
  http://localhost:4000/api/vehiculo
- **Body**
  {
  "modelo_id": 1,
  "anio": 1980,
  "tipo_combustible": "Gasolina",
  "kilometraje": 130000,
  "num_puertas": 4,
  "num_asientos": 4
  }

### Modificar vehículo por ID (PUT)

- **Ruta**:
  http://localhost:4000/api/vehiculo/1
- **Body**
  {
  "modelo_id": 1,
  "anio": 1980,
  "tipo_combustible": "Gasolina.",
  "kilometraje": 130001,
  "num_puertas": 4,
  "num_asientos": 3
  }

### Obtener todas los vehículos ordenados por ID (GET)

- **Ruta**:
  http://localhost:4000/api/vehiculo

### Obtener vehículo por ID (GET)

- **Ruta**:
  http://localhost:4000/api/vehiculo/1

### Eliminar vehículo por ID (DELETE)

- **Ruta**:
  http://localhost:4000/api/vehiculo/1
