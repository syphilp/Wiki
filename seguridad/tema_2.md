#

####Medios de almacenamiento

    Material fisico en el que se almacenan los datos, que es escrito o leido por dispositivo o unidad de almacenamiento
    
    Clasificacion según modo de acceso
    
        - Acceso secuencial
        
        - Acceso aleatorio
        
    Medios de almacenamiento:
    
        + Memorias
            
            - ROM (Read Access memory) memoria de solo lectura
            - RAM (Ramdom Access memory) memoria acceso aleatorio, es volatil
            
        + Soporte Magnéticos
        
            - Cinta magnetica, material de plástico recubierto de un material ferreomagnetico, es de acceso secuencial.
            - Tambor magnética, cilindro de material magnetíco, es de acceso aleatorio
            - Disco duro, son los discos actuales, es de acceso aleatorio
            - Disco flexible, los antiguos disquetes.
            
        + Soporte optíco
        
            - CD-R y CD-RW, disco de plastico que almacena datos, es de acceso aleatorio
            - DVD-R y DVD-RW, disco de plastico que tiene mayor capacidad que los CD, es tambien de acceso aleatorio
            - PC Cards
            - Flash card
            
        + Soportes extraibles
        
            - Pendrive o memory flash
            - Unidades de ZIP
            
        Nuevos soporte como Blue-Ray y disco rígidos externos
        
####Almacenamiento redundante y distribuido

    RAID, sistema de almacenamiento que se usa multiples discos o SSD entre los que distribuyen o replican los datos.
    
    Centros de respaldo CPD diseñado especificamente para tomar el control de otro CPD principal en caso de contigencia.
 
    - Hardware, pueden ser iguales o diferentes al del centro principal, puesto que no garantiza el mismo nivel del servicio
    
    - Software, debe ser identico al principal, incluyendo versiones y parches, dado tiene que prestar idéntica funcionalidad
    
    - Datos, debe contar  con un a réplica de los datos del principal, que podra ser sincrona o asincrona
     
        * Sincrona es que se va realizando cuando tu vas modificando algo
        
        * Asincrona es  una copia  programada de la informacion
    
####Seguridad Fisica y ambiental

    El CPD es la ubicacion donde se concentra los recursos necesarios para el procesamiento de la informacion de una organizacion

    Pretende garantizar la continuidad y disponiblidad del servicio mediante:
    
    - Disponibilidad y restriccion (Se mide en hora por dias)
    - Fiabilidad (Tener un centro respaldo, tener dos lineas de comunicacion)
    - Seguridad, redundancia y diversificacion
    - Control ambiental y prevencion (sala fria 21-23º, humedad 40-60)
    
####Ubicacion y acondicionamiento fisico

    Las condiciones atmosfericas adversas severas se localizan espacial y temporalmentee en ciertos partes del mundo y la 
    espacial y temporalmente en ciertos partes del mundo y la probalidad de que estas ocurran
 
    Consideracion para determinan la ubicacion y su acondicionamiento:
    
    - Incendios
    - Temperatura y humedad
    - Inundadciones y Terremotos
    - Rayos e interferencias electro magneticas
    
####Control de acceso fisico

    El uso de creedenciales de identificacion es uno de los puntos más importantes del sistema de seguridad fisico
    
    Se puede identificar a una persona por:
    
    - Algo que se posee
    - Algo que se sabe
    - Algo que se es
    
    Instalacion de equipos en rack bajo llaves
    
#####Sistema biometricos

    Tecnologia que realiza mediciones en forma electronica guarda y compara caracteristicas unica para la identificacion
    de personas:
    
    - ojo(Iris)
    - ojo(Retina)
    - Huellas dactilares
    - Vascular dedo
    - Vascular mano
    - Geometria de la mano
    - Escritura y firma
    - voz
    - cara 2D
    - cara 3D
    
####Cicuito cerrado de television (CCTV)

    Permitir el control de todo lo que sucede en la planta segun lo captado por las camaras extrategicamente colocadas
    
    Fuerte penetracion en el mercado de los CCTV basados en comunes IP, por bajo coste, buenas prestaciones y gestion a traves de la LAN
    
###SAI

#### Introduccion
    
    Dispositivo dotado de baterias que le permiten proporciones energia electrica tras corte suministro electrico  atodos los dispositivos
    que tengan conectados, durante un tiempo ilimitado permitiendo poder apagar los equipos y controlar picos de tension
    
    - SAI-offline, solo alimenta
    - SAI-Inline, alimenta y estabiliza cuando hay  una caida
    - SAI-online, alimenta y estabiliza la corriente
    
#####Potencia

    Es necesaria dimensionar la SAI en funcion de los equipos que se vayan a conectar a ella (carga).
    
        - CC: 
            Potencia=Voltaje*Intensidad
        - CA:
            Potencia eficaz/aparente/efectiva (VA)
            Potencia aparente (VA=potencia[W] * 1,4)
            
    Potencia necesaria
    
        Metodos de calculo
        
        - Medidor de potencia
        - Proporcionado por el fabricante
        - Estimacion de consumo (Energy Star)
        
        La carga no debe superar el 70% del total de potencia de la SAI
        
    
    