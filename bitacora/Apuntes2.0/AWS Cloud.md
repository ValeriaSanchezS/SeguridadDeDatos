# Security access to cloud resources

Ayudar al control de accesos de los recursos de AWS. 
AWS CloudFormation

## Modelo de responsabilidad compartida
Cliente: Plataforma, aplicaciones, identificacion y manejamiento de accesos, sistema operativo 

AWS: Almacenamiento, Bases de datos, Regions, Disponibilidad de la zona. 

### AWS Identify and Access Management (IAM)

Nos permite administrar el acceso a todo usuario o grupos. 

Servicios federados: Es autorizacion federada, te redirige para pedir permisos pero sin necesidad de autorizarte del todo. 
Granular: Son permisos que se dan para el acceso.

### IAM provides
- Autenticacion: quien quiere el acceso
- Autorizacion: A que tienes acceso 

### IAM overview

- USER: Una persona o aplicaion que puede autenticar con la cuente de AWS
- GROUP: A collection
- ROLE: Un rol puede ser asumido por un usuario, para permitir permisos
- IAM policy: Se definen las acciones que se permiten

### IAM terminology 
- IAM entity: Se usa para la autenticacion de los usuarios y roles 
- IAM identify: Aquellos objetos dentro de los recursos de IAM para asignar politicas.
- IAM resource: Aquel recursos al que quieres otorgar el permiso.
- Principal: La persona o aplicacion que usa la cuenta AWS como root user

### Requests 

Informacion que necesitas: 
- Action or operations: Que es lo que quiere hacer
- Resourses:
- Principal: La persona o la aplicacion que envia la peticion
- Environment data: La IP address, user agnet, time of day
- Resourse Data

### Service endpoint
Para conectarte a AWS service puedes utilizar el URL 

### IAM roles
Caracteristicas: 
* Credenciales de seguridad temporales.
* El rol no es inicamente asociada a una persona
* Se brinda un toker temporal para poder acceder a los recursos
* No tienes que asignar las politicas de muevo

### Credenciales de autenticacion
  - Nombre de usuario
  - Contraseña
  - Access key ID
  - secret access key 

### Ma and inline

- Son las politicas predefinidas
- Son las que son creadas por el usuario

### AWS Single Sing-ON
Solo necesitas autenticarte una vez para poder tener acesso a todos los servicios

### AWS cognito
Te permite administrar varias cuentas, brindas permisos para definir quien va a tener acesso a cada cosa.

## CIS 
Guias para configurar de forma segura el sistema operativo

Hardening


