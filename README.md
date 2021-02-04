# Workshop about RHEL 8 and Insights right from your laptop 💻🔥🚀

Bienvenido a este taller, aqui instalarás RHEL versión 8, configuraras tu laptop con una VM y montaremos Insights en esa máquina 🚀

*Requisitos:*

💻 Laptop con suficiente RAM/disco, para montar Virtualbox/VMware Player etc.

🧰 Internet y tiempo.


![title](https://media1.tenor.com/images/0ac80d82231814ec9d7d331861b855c1/tenor.gif?itemid=5425050)

## 1. Crea una cuenta en access.redhat.com

- Abre este link https://access.redhat.com/downloads/
- Selecciona Red Hat Enterprise Linux 8
- Haz click en: "Crear una cuenta"  
- En tipo de cuenta: Selecciona personal
- En ID de inicio: Pone un nickname que quieras usar
- Luego completa el formulario con los datos y da click en Crear mi cuenta


## 2. Activa tu cuenta

Seguramente te llegará un correo dandote la bienvenida y pidiendo activar la cuenta ---> Hazlo!

## 3. Descarga la iso de Red Hat Enterprise Linux 8

- Ingresa de nuevo al link: https://access.redhat.com/downloads/
- Luego Selecciona Red Hat Enterprise Linux 8
- Descarga el que dice: 
```
Red Hat Enterprise Linux 8.3 Boot ISO
```

## 4. Monta la iso en tu virtualbox/vmware workstation

```
Tienes ya esto instalado no?
```
Si no lo tienes instalado puedes bajarlo de aqui:
https://www.virtualbox.org/wiki/Downloads
o de aqui:
https://www.vmware.com/products/workstation-player.html

## 5. Configura la VM adecuadamente:

- Recuerda que en tu VMware o lo que sea, debes configurar la VM con 1 adaptador de red en modo NAT + 1 en modo adaptador solo-anfitrion ( si quieres tener acceso SSH desde fuera) 😁 

## 6. Echale candela a esa máquina!!! Encendámos la VM:

- Vamos paso a paso, pero mientras tienes un video de guia https://youtu.be/QHAbL9P_LA4?t=191

## 7. Si ya esta la VM ok, registremos el RHEL con Insights

Como escogimos RHEL 8, ahora solo es hacer 1 comando mágico:

```
insights-client --register
```


![title](https://untrite.com/wp-content/uploads/2019/01/automate-everything.jpg)
