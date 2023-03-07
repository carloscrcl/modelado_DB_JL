# Directorio de JL

## Entidadades


### Vocales
- vocal_ID **(PK)**
- cargo
- vocalia_FK **(FK)**
- Nombre
- ap. paterno
- ap. materno
- Ip_phone_FK **(FK)**
- email
- foto

### Ip_Phones _(Entidad Pivote)_
- ip_phone_ID
- estado_FK **(fK)**
- distrito_FK **(FK)**
- vocalia_Fk **(FK)**

### telefonos
- id de telefono
- No. de telefono
- direccion_FK **(FK)**

### Direcciones
- direccion_ID **(PK)**
- Calle
- Numero
- cod. postal
- cabecera
- telefono


### distritos _(catalogo)_
- id distrito **(PK)**
- Nombre_distrito

### estados _(Catalogo)_
- id estado **(PK)**
- nombre

### Vocalias _(Catalogo)_
- vocalia_id **(PK)**
- Descripcion
