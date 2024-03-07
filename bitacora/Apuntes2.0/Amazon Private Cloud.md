# VPC 
Modelo de responsabilidad compartida:

Cliente: Proteccion del manejo de red.

## Arquitectura de 3 capas: 

VPC: Virtual P Cloud
Desplega la informacion, Permite mantener seguro la informacion, esta almacenada en esta nube privada virtual. 
Segemento de red, en cuantos bloques lo quieres dividir, security group donde defines el trafico definidio 

* Presentacion layer:
    - Application Load Balance: Recibe todas las solicitudes de tus clientes, distribuyendo la carga de forma uniforme(trafico). Solo te da servicio en HTTF HTTPS. 
    - NAT Gateway: Lo necesitas para poder hacer las intancias. 
* Business logic layer():
    - Maquinas virtuales.
    - Auto Scalling group: Crea instancias o quitar instancias para aumentar o reducir los recursos que usas
    - Network Load Balancer. 
* Data storage layer: Zona de disponibilidad.

### Amazon Private Cloud
Cuando divides tu vpc debe tener una rub red que debe tener una disponibilidad. 
Controlas tus recursos de red. Puedes cre

Internet Gateway: Provee a target en tu VPC route

NAT gateway 

Private subnet: Subredes privadas, debe tener una tabla de enrutamiento, la comunicacion se logra mediante las tablas de enrutamiento. 

Sub redes publicas: Estan mas expuestas. Conexion a internet. 

IP addressing: Va desde los 16 a 28 beats

Tablas de enrutamiento:

### Security Groups
Para definir los puertos para contactar a las instancias, los defines por los security groups. Estan cerrados. Necesitas reglas para permitir el trafico.

Cuando el grupo de seguridad esta en stayfull significa que yo no necesito definir una reglas de salida un trafico de entrada.
Stayless: necesitas una regla para definir una entrada y una salida. 
