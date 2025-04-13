# Stark-Labs-Industry

Proyecto: Intranet Corporativa – Stark Labs Industry

Autores:
Heymmy López Juárez
Jafet Araya Artavia

Instalación de SharePoint Server 2019 en Máquina Virtual
Entorno: Windows Server 2022 + SQL Server Developer 2022 + SSMS 20 + Dominio: root

1. Herramientas necesarias
Windows Server 2022 ISO: Descargar

SQL Server Developer 2022: Descargar

SQL Server Management Studio (SSMS) 20: Descargar

SharePoint Server 2019: Guía oficial

VirtualBox: Descargar

2. Configuración de la máquina virtual
Crear una máquina virtual en VirtualBox con al menos:

6 a 8 GB de RAM

2 o más núcleos de CPU

100 GB de almacenamiento en disco

Instalar Windows Server 2022.

Instalar el rol de Active Directory Domain Services (AD DS).

Crear un dominio local llamado root.

3. Instalación de SQL Server Developer 2022 y SSMS
Instalar SQL Server Developer 2022.

Usar la instancia por defecto: MSSQLSERVER.

Seleccionar autenticación mixta (Windows y SQL).

Instalar SSMS 20 y verificar la conexión con la instancia SQL.

4. Instalación de SharePoint Server 2019
Ejecutar prerequisiteinstaller.exe para instalar los requisitos previos.

Ejecutar setup.exe para iniciar la instalación.

Crear una nueva granja de servidores.

Conectar SharePoint con la instancia SQL configurada.

Establecer el usuario administrador de la granja.

Finalizar el asistente de configuración.

Acceder a la Central Administration de SharePoint.

5. Validación
Crear un sitio de prueba desde Central Administration.

Confirmar acceso al sitio y administración correctamente desde el navegador de la máquina virtual.
