# Lab#2 - Configuración y simulación de Red LAN.

## Presentado por: Julián(Alvarado + Durán + Pinilla)

### Metodología seguida.

Para el desarrollo del laboratorio se tuvo en cuenta los siguiente conceptos:

* Red LAN: "Se conoce como red LAN (siglas del inglés: Local Área Network, que traduce Red de Área Local) a una red informática cuyo alcance se limita a un espacio físico reducido, como una casa, un departamento o a lo sumo un edificio" [1].
* VLAN: "Las VLAN o también conocidas como «Virtual LAN» nos permite crear redes lógicamente independientes dentro de la misma red física, haciendo uso de switches gestionables que soportan VLANs para segmentar adecuadamente la red" [2]. Básicamente permiten segmentar una misma red apartir de un Switch, y tener distintas subredes.
* Cableado estructurado: "Cuando hablamos del cableado estructurado nos referimos a un sistema de conectores, cables, dispositivos y canalizaciones que forman la infraestructura que implanta una red de área local en un edificio o recinto. Su función es transportar señales desde distintos emisores hasta los receptores correspondientes"[3].
* Spanning Tree: "Spanning Tree Protocol (STP) es un protocolo de capa dos publicado en la especificación IEEE 802.1.
El objetivo de STP es mantener una red libre de bucles. Un camino libre de bucles se consigue cuando un dispositivo es capaz de reconocer un bucle en la topología y bloquear uno o más puertos redundantes" [4].

### RESPUETAS.

1.Montaje de la topología.  
 ![image](https://user-images.githubusercontent.com/64561271/230110951-c54f73a3-3506-47a7-8303-c8f7a135481c.png)
 
3.Verifique que se haya asignado correctamente las direcciones IP a cada una de las interfaces NIC de los PC.
 ##### PC1 
 ![image](https://user-images.githubusercontent.com/64561271/230111323-5d6a0f59-f70e-4491-9833-17f7edff085d.png)
 ##### PC2
 ![image](https://user-images.githubusercontent.com/64561271/230111421-592ad698-1c66-484d-b62e-e7f0ad1a1603.png)
 ##### PC3
 ![image](https://user-images.githubusercontent.com/64561271/230111438-001eb411-ed89-4cdd-9bbb-b720a066cd69.png)
 ##### PC4
 ![image](https://user-images.githubusercontent.com/64561271/230111458-bde692ba-56b7-4695-baad-0fc4ca40ffc2.png)
 ##### PC5
 ![image](https://user-images.githubusercontent.com/64561271/230111473-ee536112-7796-413e-a6c3-d48af6dee3c1.png)
 ##### PC6
 ![image](https://user-images.githubusercontent.com/64561271/230111493-edd1b882-f172-4522-b36f-7651f43909ce.png)

5.Comprobacion de Vlans mediante el comando -Show Vlan Brief.
 ##### SWITCH 1
 ![image](https://user-images.githubusercontent.com/64561271/230113146-a618e567-9ef6-447c-b384-7d1765f449a3.png)

 ##### SWITCH 2
 ![image](https://user-images.githubusercontent.com/64561271/230113156-d564b992-4cee-499d-b934-600e153ab821.png)

 ##### SWITCH 3
 ![image](https://user-images.githubusercontent.com/64561271/230113165-fb2d9b36-9a5e-4421-8ec3-9fde7eb9bfd1.png)

### RETOS.
El principal desafio para la resolución del laboratorio fue la introducción de un nuevo concepto tan global y importante como lo es el "Spanning Tree", fue un poco costoso al principio entder bien cómo era su funcionamiento a grandes rasgos. De la misma forma, cuando se configuró por primera vez fue uno de los mayores desafios, apesar de que ya se había realizado una actividad prácticamente igual en clase, el hecho de sentarse y hacerlo desde 0 por mano propia fue uno de los mayores impedimentos al momento de desarrollar el laboratorio.

### CONCLUSIONES Y RECOMENDACIONES.
A diferencia del primer laboratorio existieron unas mejoras considerables, el trabajo en equipo fue bastante más fluido, la comunicación entre Julianes fue más efectiva, y se facilitó la repartición de tareas. Claramente la complejidad del laboratorio fue superior comparada a la primera práctica, pero se contaba ya con distintos ejemplos realizados en clase y un poco más de practica en Packet Tracer, esto también debido al desarrollo de los distintos módulos del curso recomendado. Para próximos laboratorios se tendrá en cuenta la misma organización que hubo para esta práctica, la buena comunicación entre compañeros es algo que se quiere destacar de este laboratorio. 

### REFERENCIAS
* [1] Fragmento tomado de: "https://concepto.de/red-lan/#ixzz7xxuZ6gL7"
* [2] Fragmento tomado de: "https://www.redeszone.net/tutoriales/redes-cable/vlan-tipos-configuracion/"
* [3] Fragmento tomado de: "https://www.nextu.com/blog/cableado-estructurado-que-es-rc22/"
* [4] Fragmento tomado de: "https://aprenderedes.com/2019/11/protocolo-de-arbol-de-extensionstp/"
* Curso de Skills For All Networking Essentials. Módulo 17 y 18. "https://skillsforall.com/launch?id=104c1536-83d6-47db-b7a1-6007327b3134"
