Primero registrar un usuario en la siguiente ruta:

http://localhost:8080/register

con el siguiente JSON de Entrada

```json
{
    "username":"correa96b2r",
    "password":"123456",
    "firsName":"Marcelo",
    "lastName":"Valderrama",
    "role":"USUARIO"
}
```
Una vez registrado como usuario, aparecera el Token

```json
{
    "token": "eyJhbGciOiJIUzM4NCJ9.eyJzdWIiOiJjb3JyZWE5NmIyciIsImlhdCI6MTcxMTIzNDI0MiwiZXhwIjoxNzExMzIwNjQyfQ.6STbnApvfw3ZKgkNbronXRgSbcRRA9D_KL-OK7qHs5aUggk1PJ6WGLIQ9ps1y-lg",
    "message": "El registro del usuario fue exitoso."
}
```

Despues en cualquiera de los servicios se debe adicionar el Bearer Token en el encabezado de la requesicion

![image](https://github.com/correa96cl/desafio-previred/assets/41351415/cc117c7d-f7ac-45be-9fd8-679dcf134b11)

Alli se puede ejecutar cualquier de los metodo documentados en el Swagger 

http://localhost:8080/swagger-ui/index.html

![image](https://github.com/correa96cl/desafio-previred/assets/41351415/3b0cfde8-d23a-432f-9b16-3fd1be30afce)

o Directamente en tu aplicacion de preferencia

![image](https://github.com/correa96cl/desafio-previred/assets/41351415/36bf7862-ca83-4f70-ac38-c7040cc95273)

Saludos.

