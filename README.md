# Practica-Terraform Jose Francisco León López
## En esta práctica vamos a automatizar la instalación de instancias,ips privadas y grupos de seguridad en AWS a través de terraform
### Para ello vamos a tener que instalar terraform en nuestra máquina 
#### Una vez instalamos terraform tenemos que hacer el comando init para instalar los plugins necesarios:
~~~
terraform init
~~~
#### Después del init tenemos que hacer un fmt para validar y formatear el archivo de configuración
~~~
terraform fmt
~~~
#### Con el validate confirmamos que el archivo de configuración está bien:
~~~
terraform validate
~~~
#### Y una vez hecho eso hacemos el plan para ver los cambios que vamos a hacer y el apply para ejecutar el main.tf
~~~
terraform plan
~~~
~~~
terraform apply
~~~
#### Antes de hacer esto tenemos que configurar nuestro archivo main.tf que se va a dividir en cuatro partes.
##### La segunda parte es la creación de las instancias
