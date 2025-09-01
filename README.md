# 📡 Sistema de Monitoreo en Tiempo Real con APRS Trackdirect  

Este repositorio contiene la configuración y documentación de un servidor local basado en **APRS Trackdirect** para el monitoreo de equipos de emergencia en incendios forestales. El sistema permite la recepción, procesamiento y visualización en tiempo real de datos APRS (Automatic Packet Reporting System) provenientes de *trackers* e *iGates*, sin depender de servicios externos en la nube.  

---

## 📑 Tabla de Contenidos
1. [Fundamentos](#-fundamentos)  
   - [APRS](#-fundamentos-de-aprs)  
   - [LoRa](#-fundamentos-de-lora)  
   - [Legislación en Costa Rica (PNAF)](#-legislación-de-frecuencias-en-costa-rica-pnaf)  
2. [Problemática](#-problemática)  
3. [Objetivos](#-objetivos)  
4. [Plan de Trabajo](#-plan-de-trabajo)  
5. [Grupo de Trabajo](#-grupo-de-trabajo)  
6. [Instalación y Configuración](#-instalación-y-configuración)  
7. [Uso del Sistema](#-uso-del-sistema)  

9. [Referencias](#-referencias)  

---

## 📡 Fundamentos  

### 🔹 Fundamentos de APRS  
APRS (Automatic Packet Reporting System) es un protocolo de comunicaciones digitales utilizado principalmente por radioaficionados para transmitir información en tiempo real sobre ubicación, telemetría, mensajes y estado de estaciones.

Conceptos Clave: 

-Paquetes de Datos: APRS transmite información en forma de paquetes digitales, generalmente usando AX.25, un protocolo de capa de enlace de datos derivado de X.25.

-Información de Ubicación: Cada estación puede enviar su posición GPS, velocidad, rumbo y altitud para que otros usuarios o aplicaciones puedan visualizarla en mapas en tiempo real.

-Mensajería: Permite enviar mensajes cortos entre estaciones de radio sin necesidad de infraestructura centralizada.

IGate y Digipeater:

-IGate (Internet Gateway): Recibe paquetes APRS por radio y los envía a Internet, integrando la red global de APRS.

-Digipeater: Repite paquetes APRS para extender el rango de comunicación entre estaciones.

---

### 🔹 Fundamentos de LoRa  
*(Próximamente:)


---

### 🔹 Legislación de Frecuencias en Costa Rica (PNAF)  
*(Próximamente:)



---

## 🔥 Problemática de enfoque del proyecto
En incendios forestales, el seguimiento en tiempo real de los bomberos es crucial, pero los métodos actuales dependen de conectividad a Internet. En áreas remotas esto limita la coordinación y puede comprometer la seguridad. El sistema propuesto implementa un servidor local de **APRS Trackdirect**. 

---

## 🎯 Objetivos  

### Objetivo General  
Configurar una aplicación de servidor local APRS Trackdirect que permita la recepción, procesamiento y visualización en tiempo real de los datos APRS, para dar seguimiento a bomberos en incendios forestales.  

### Objetivos Específicos  
- Configurar e implementar APRS Trackdirect en un servidor local Linux.  
- Desarrollar una interfaz web para visualizar la ubicación y mensajes APRS.  
- Documentar instalación, configuración y operación para replicación futura.  

---

## 🗓️ Plan de Trabajo  

![Diagrama de Gantt](./figuras/diagrama_gantt.png)


## 👥 Grupo de Trabajo  

Este grupo se enfoca en la configuración y gestión de un servidor local APRS Trackdirect.  

### Responsabilidades principales:  
- Configuración del servidor en entorno local.  
- Integración con receptores APRS.  
- Visualización y análisis de tramas recibidas.  
- Documentación técnica de instalación y operación.  
- Mantenimiento y solución de problemas.  

---

## ⚙️ Instalación y Configuración del Servidor 

### Pre-Requisitos
Como primeros pasos de configuración preliminar se debe:

- Configurar desde la Interfaz de UEFI/BIOS la opción de virtualización.

![virtualizacion](./figuras/bios_virtualizaciom.png)


Además se deben descargar e instalar lo siguientes programas:

-  Ubuntu Server 
![Pagina Ubuntu](./figuras/pagina_ubuntu_server.png)

-  Virtual Box 
![Pagina Ubuntu](./figuras/pagina_virtual_box.png)

### Paso 1: Instalación de imagen ISO



### Paso 2: Configuración inicial en Virtual-Box


### Paso 3: Instalación Webmin

---



## 🚀 Uso del Sistema  
*(Próximamente: instrucciones de ejecución, acceso a la interfaz web y ejemplos de visualización en tiempo real.)*  

---

## 📚 Referencias  
- APRS.org – Documentación oficial.  
