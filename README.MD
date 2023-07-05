Su empresa tiene departamentos de servicio. Cada departamento tiene un número de máquinas virtuales (VM).
La compañía tiene una suscripción de Azure que contiene un grupo de recursos denominado RG1.
Todas las máquinas virtuales se encuentran en RG1.
Desea asociar cada máquina virtual con su departamento respectivo.

¿Qué debe hacer?

a. Cree grupos de administración de Azure para cada departamento.

B. Cree un grupo de recursos para cada departamento.

>C. Asigne etiquetas a las máquinas virtuales. Más votados

D. Modifique la configuración de las máquinas virtuales.

Su empresa tiene una suscripción a Azure Active Directory (Azure AD).
Desea implementar una directiva de acceso condicional de Azure AD.
La directiva debe configurarse para requerir que los miembros del grupo Administradores globales usen Multi-Factor Authentication y un dispositivo unido a Azure AD cuando se conecten a Azure AD desde ubicaciones que no sean de confianza.
Solución: acceda a Azure Portal para modificar el control de concesión de la directiva de acceso condicional de Azure AD.

¿La solución cumple con el objetivo?

>A. Sí Más votados

B. No



Está planeando implementar una máquina virtual de Ubuntu Server en la suscripción de Azure de su empresa.
Debe implementar una implementación personalizada que incluya la adición de una entidad de certificación raíz (CA) de confianza.

¿Cuál de las siguientes opciones debe usar para crear la máquina virtual?

a. El cmdlet New-AzureRmVm.

B. El cmdlet New-AzVM.

>C. El cmdlet Create-AzVM.

D. El comando az vm create



La solución Azure de su empresa usa Multi-Factor Authentication para cuando los usuarios no están en la oficina. La opción Por autenticación se ha configurado como modelo de uso.
Después de la adquisición de una empresa más pequeña y la adición del nuevo personal a Azure Active Directory (Azure AD) obtiene una empresa diferente y la adición de los nuevos empleados a Azure Active Directory (Azure AD), se le informa que estos empleados también deben hacer uso de Multi-Factor Authentication.
Para lograr esto, la configuración Por usuario habilitado debe establecerse para el modelo de uso.
Solución: cree un nuevo proveedor de Multi-Factor Authentication con una copia de seguridad de los datos existentes del proveedor de Multi-Factor Authentication.

¿La solución cumple con el objetivo?

>a. Sí Más votados

B. No Más votados




Su empresa tiene un inquilino de Azure Active Directory (Azure AD) denominado weyland.com que está configurado para la coexistencia híbrida con el dominio local de Active
Directory.
Tiene un servidor denominado DirSync1 que está configurado como un servidor DirSync.
Crear una nueva cuenta de usuario en Active Directory local. Ahora debe replicar la información de usuario en Azure AD inmediatamente.
Solución: ejecute el cmdlet Start-ADSyncSyncCycle -PolicyType Initial PowerShell.

¿La solución cumple con el objetivo?

>A. Sí

B. No




Su empresa tiene una suscripción de Azure que incluye una cuenta de almacenamiento, un grupo de recursos, un contenedor de blobs y un recurso compartido de archivos.
Un colega llamado Jon Ross usa una plantilla solitaria de Azure Resource Manager (ARM) para implementar una máquina virtual y una cuenta de Azure Storage adicional.
Desea revisar la plantilla de ARM que usó Jon Ross.
Solución: obtenga acceso a la hoja Grupo de recursos.

¿La solución cumple con el objetivo?

>A. Sí Más votados

B. No




Su empresa tiene tres máquinas virtuales (VM) que se incluyen en un conjunto de disponibilidad.
Intenta cambiar el tamaño de una de las máquinas virtuales, que devuelve un mensaje de error de asignación.
Es imperativo que se cambie el tamaño de la máquina virtual.

¿Cuál de las siguientes acciones debería tomar?

A. Solo debe detener una de las máquinas virtuales.

B. Debe detener dos de las máquinas virtuales.

>C. Debe detener las tres máquinas virtuales. Más votados

D. Debe quitar la máquina virtual necesaria del conjunto de disponibilidad.




Tiene una máquina virtual (VM) de Azure que tiene un único disco de datos. Se le ha encomendado la tarea de adjuntar este disco de datos a otra máquina virtual de Azure.
Debe asegurarse de que su estrategia permita que las máquinas virtuales estén sin conexión durante el menor tiempo posible.

¿Cuál de las siguientes es la acción que debe tomar PRIMERO?

>A. Detenga la máquina virtual que incluye el disco de datos.

B. Detenga la máquina virtual a la que se debe conectar el disco de datos.

C. Separe el disco de datos. Más votados

D. Elimine la máquina virtual que incluye el disco de datos.



Su empresa tiene una suscripción de Azure.
Debe implementar varias máquinas virtuales (VM) de Azure mediante plantillas de Azure Resource Manager (ARM). Se le ha informado de que las máquinas virtuales se incluirán en un único conjunto de disponibilidad.
Debe asegurarse de que la plantilla de ARM que configure permita que permanezcan accesibles tantas máquinas virtuales como sea posible en caso de error o mantenimiento del tejido.

¿Cuál de los siguientes es el valor que debe configurar para la propiedad platformFaultDomainCount?

A. 10

B. 30

C. Valor mínimo

>D. Valor máximo Más






Su empresa tiene una suscripción de Azure.
Debe implementar varias máquinas virtuales (VM) de Azure mediante plantillas de Azure Resource Manager (ARM). Se le ha informado de que las máquinas virtuales se incluirán en un único conjunto de disponibilidad.
Debe asegurarse de que la plantilla de ARM que configure permita que permanezcan accesibles tantas máquinas virtuales como sea posible en caso de error o mantenimiento del tejido.

¿Cuál de los siguientes es el valor que debe configurar para la propiedad platformUpdateDomainCount?

Un. 10

> B. 20 Más votados

C. 30

D. 40




ARRASTRAR Y COLOCAR:
ha descargado una plantilla de Azure Resource Manager (ARM) para implementar numerosas máquinas virtuales (VM). La plantilla de ARM se basa en una máquina virtual actual, pero debe adaptarse para hacer referencia a una contraseña administrativa.
Debe asegurarse de que la contraseña no se pueda almacenar en texto sin formato.
Se está preparando para crear los componentes necesarios para lograr su objetivo.

¿Cuál de los siguientes debe crear para lograr su objetivo? Responda arrastrando la opción correcta de la lista al área de respuesta.
Seleccione y coloque:


![Alt text](image.png)




Su empresa tiene un inquilino de Azure Active Directory (Azure AD) configurado para la coexistencia híbrida con el dominio local de Active Directory.
El entorno virtual local consta de máquinas virtuales (VM) que se ejecutan en servidores host Hyper-V de Windows Server 2012 R2.
Ha creado algunos scripts de PowerShell para automatizar la configuración de máquinas virtuales recién creadas. Tiene previsto crear varias máquinas virtuales nuevas.Necesita una solución que garantice que los scripts se ejecutan en las nuevas máquinas virtuales.

¿Cuál de las siguientes es la mejor solución?

>A. Configure un archivo por lotes SetupComplete.cmd en el directorio %windir%\setup\scripts.

B. Configure un objeto de directiva de grupo (GPO) para ejecutar los scripts como scripts de inicio de sesión.

C. Configure un objeto de directiva de grupo (GPO) para ejecutar los scripts como scripts de inicio.

D. Coloque los scripts en un nuevo disco duro virtual (VHD).






Su empresa tiene un inquilino de Azure Active Directory (Azure AD) configurado para la coexistencia híbrida con el dominio local de Active Directory.
Planea implementar varias máquinas virtuales (VM) nuevas en Azure. Las máquinas virtuales tendrán el mismo sistema operativo y requisitos de software personalizados.
Configure una máquina virtual de referencia en el entorno virtual local. A continuación, generalice la máquina virtual para crear una imagen.
Debe cargar la imagen en Azure para asegurarse de que está disponible para su selección al crear las nuevas máquinas virtuales de Azure.

¿Qué cmdlets de PowerShell debe usar?

A. Add-AzVM

>B. Add-AzVhd Más votados

C. Add-AzImage

D. Add-AzImageDataDisk




ARRASTRAR SUÉLTELO:
su empresa tiene una suscripción de Azure que incluye varias máquinas virtuales (VM) de Azure, que forman parte de la misma red virtual.
Su empresa también tiene un servidor Hyper-V local que hospeda una máquina virtual, denominada VM1, que debe replicarse en Azure.

¿Cuál de los siguientes objetos que se deben crear para lograr este objetivo? Responda arrastrando la opción correcta de la lista al área de respuesta.
Seleccione y coloque:


![Alt text](image-1.png)





La suscripción de Azure de su empresa incluye dos redes de Azure denominadas VirtualNetworkA y VirtualNetworkB.
VirtualNetworkA incluye una puerta de enlace VPN que está configurada para hacer uso del enrutamiento estático. Además, existe una conexión VPN de sitio a sitio entre la red local de su empresa y VirtualNetworkA.
Ha configurado una conexión VPN de punto a sitio a VirtualNetworkA desde una estación de trabajo que ejecuta Windows 10. Después de configurar el emparejamiento de red virtual entre
VirtualNetworkA y VirtualNetworkB, confirma que puede tener acceso a VirtualNetworkB desde la red local de la empresa. Sin embargo, encuentra que no puede establecer una conexión a VirtualNetworkB desde la estación de trabajo de Windows 10.
Debe asegurarse de que se pueda establecer una conexión a VirtualNetworkB desde la estación de trabajo con Windows 10.
Solución: descargue y vuelva a instalar el paquete de configuración del cliente VPN en la estación de trabajo con Windows 10.


¿La solución cumple con el objetivo?

>A. Sí Más votados

B. No




Su empresa tiene máquinas virtuales (VM) hospedadas en Microsoft Azure. Las máquinas virtuales se encuentran en una única red virtual de Azure denominada VNet1.
La empresa tiene usuarios que trabajan de forma remota. Los trabajadores remotos requieren acceso a las máquinas virtuales en VNet1.

Debe proporcionar acceso a los trabajadores remotos.
¿Qué debe hacer?

A. Configure una VPN de sitio a sitio (S2S).

B. Configure una VPN de red virtual a red virtual.

>C. Configure una VPN de punto a sitio (P2S). Más votados

D. Configurar DirectAccess en una máquina virtual de servidor de Windows Server 2012.

E. Configurar una VPN multisitio





Nota: La pregunta se incluye en una serie de preguntas que representan la configuración idéntica. Sin embargo, cada pregunta tiene un resultado distintivo. Establezca si la solución satisface los requisitos.
Su empresa tiene un grupo de disponibilidad Always On de Microsoft SQL Server configurado en sus máquinas virtuales (VM) de Azure.
Debe configurar un equilibrador de carga interno de Azure como agente de escucha para el grupo de disponibilidad.
Solución: habilite la IP flotante.

¿La solución cumple con el objetivo?

>A. Sí Más votados

B. No





Su empresa tiene dos servidores locales denominados SRV01 y SRV02. Los desarrolladores han creado una aplicación que se ejecuta en SRV01. La aplicación llama a un servicio en SRV02 por dirección IP.
Tiene previsto migrar la aplicación en máquinas virtuales (VM) de Azure. Ha configurado dos máquinas virtuales en una sola subred de una red virtual de Azure.
Debe configurar las dos máquinas virtuales con direcciones IP internas estáticas.

¿Qué debe hacer?

A. Ejecute el cmdlet New-AzureRMVMConfig PowerShell.

B. Ejecute el cmdlet de PowerShell Set-AzureSubnet.

C. Modifique las propiedades de la máquina virtual en el Portal de administración de Azure.

D. Modifique las propiedades IP en el Centro de redes y recursos compartidos de Windows.

>E. Ejecute el cmdlet de PowerShell Set-AzureStaticVNetIP.





Su empresa tiene una suscripción a Azure Active Directory (Azure AD).
Debe implementar cinco máquinas virtuales (VM) en la subred de red virtual de su empresa.
Cada máquina virtual tendrá una dirección IP pública y privada. Las reglas de seguridad de entrada y salida para todas estas máquinas virtuales deben ser idénticas.

¿Cuál de las siguientes es la menor cantidad de interfaces de red necesarias para esta configuración?

>A. 5 Más votados

B. 10

C. 20

D. 40



Su empresa tiene una suscripción a Azure Active Directory (Azure AD).
Debe implementar cinco máquinas virtuales (VM) en la subred de red virtual de su empresa.
Cada máquina virtual tendrá una dirección IP pública y privada. Las reglas de seguridad de entrada y salida para todas estas máquinas virtuales deben ser idénticas.

¿Cuál de las siguientes es la menor cantidad de grupos de seguridad necesarios para esta configuración?

>A. 4

B. 3

C. 2

D. 1




La suscripción de Azure de su empresa incluye máquinas virtuales (VM) de Azure que ejecutan Windows Server 2016.
Se realiza una copia de seguridad de una de las máquinas virtuales todos los días mediante Restauración instantánea de Copia de seguridad de Azure.
Cuando la máquina virtual se infecta con ransomware de cifrado de datos, decide recuperar los archivos de la máquina virtual.


¿Cuál de las siguientes opciones es VERDADERA en este escenario?

Un. Solo puede recuperar los archivos en la máquina virtual infectada.

>B. Puede recuperar los archivos en cualquier máquina virtual dentro de la suscripción de la empresa. Más votados

C. Solo puede recuperar los archivos en una nueva máquina virtual.

D. No podrá recuperar los archivos.





La suscripción de Azure de su empresa incluye máquinas virtuales (VM) de Azure que ejecutan Windows Server 2016.
Se realiza una copia de seguridad de una de las máquinas virtuales todos los días mediante Restauración instantánea de Copia de seguridad de Azure.
Cuando la máquina virtual se infecta con ransomware de cifrado de datos, debe restaurar la máquina virtual.

¿Cuál de las siguientes acciones debería tomar?

A. Debe restaurar la máquina virtual después de eliminar la máquina virtual infectada.

>B. Debe restaurar la máquina virtual en cualquier máquina virtual dentro de la suscripción de la empresa.

C. Debe restaurar la máquina virtual en una nueva máquina virtual de Azure. Más votados

D. Debe restaurar la máquina virtual en un dispositivo Windows local.





Administrar una solución en Azure que actualmente tiene problemas de rendimiento.
Debe encontrar la causa de los problemas de rendimiento relacionados con las métricas en la infraestructura de Azure.

¿Cuál de las siguientes es la herramienta que debe usar?

A. Análisis de tráfico de Azure

>B. Azure Monitor Más votados

C. Registro de actividad de Azure

D. Azure Advisor



Su empresa tiene una suscripción de Azure que incluye un almacén de Recovery Services.
Desea usar Copia de seguridad de Azure para programar una copia de seguridad de las máquinas virtuales (VM) de su empresa en el almacén de Recovery Services.
¿De cuál de las siguientes máquinas virtuales puede hacer una copia de seguridad? Elija todas las que correspondan.


> Respuesta correcta: ABCDE 🗳️



Después de responder a una pregunta de esta sección, NO podrá volver a ella. Como resultado, estas preguntas no aparecerán en la pantalla de revisión.
Tiene un inquilino de Azure Active Directory (Azure AD) denominado contoso.com.
Tiene un archivo CSV que contiene los nombres y direcciones de correo electrónico de 500 usuarios externos.
Debe crear una cuenta de usuario invitado en contoso.com para cada uno de los 500 usuarios externos.
Solución: cree un script de PowerShell que ejecute el cmdlet New-AzureADMSInvitation para cada usuario externo.

¿Esto cumple con el objetivo?

>A. Sí Más votados

B. No




tiene una suscripción de Azure denominada Subscription1 que contiene un grupo de recursos denominado RG1.
En RG1, se crea un equilibrador de carga interno denominado LB1 y un equilibrador de carga público denominado LB2.
Debe asegurarse de que un administrador denominado Admin1 pueda administrar LB1 y LB2. La solución debe seguir el principio del privilegio mínimo.
¿Qué rol debe asignar a Admin1 para cada tarea? Para responder, seleccione las opciones apropiadas en el área de respuesta.
NOTA: Cada selección correcta vale un punto.
Zona caliente:


![Alt text](image-2.png)



