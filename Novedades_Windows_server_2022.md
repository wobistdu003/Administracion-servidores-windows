# Novedades de Windows Server 2022.
Windows Server 2022 se basa en Windows Server 2019 y aporta muchas innovaciones en tres temas clave: seguridad, integración y administración híbridas de Azure y plataforma de aplicaciones.
A continuación, se describen las características de Windows Server 2022 en todas las ediciones. 

# Seguridad.
Las nuevas funcionalidades de seguridad de Windows Server 2022 combinan otras funcionalidades de seguridad de Windows Server en varias áreas para proporcionar protección en profundidad contra 
amenazas avanzadas. La seguridad avanzada de varias capas de Windows Server 2022 proporciona la protección completa que los servidores necesitan actualmente.

# Servidor con núcleo protegido.
El hardware de servidor certificado con núcleo protegido de un asociado de OEM proporciona más protecciones de seguridad que resultan útiles contra ataques sofisticados. Este hardware puede 
proporcionar mayor seguridad al trabajar con datos críticos en algunos de los sectores de datos más confidenciales. Un servidor con núcleo protegido usa funcionalidades de hardware, firmware 
y controlador para habilitar las características de seguridad avanzadas de Windows Server. Muchas de estas características están disponibles en PC con núcleo protegido de Windows y ahora también
están disponibles en hardware de servidor con núcleo protegido y Windows Server 2022. Para obtener más información sobre el servidor de núcleo protegido, vea Servidor de núcleo protegido.

# Protección de firmware.
El firmware se ejecuta con privilegios elevados y a menudo es invisible para las soluciones antivirus tradicionales, lo que ha dado lugar a un aumento en el número de ataques basados en firmware. 
Los servidores con núcleo protegido miden y comprueban los procesos de arranque con la tecnología de raíz dinámica de confianza para la medida (DRTM). Los servidores con núcleo protegido también 
pueden aislar el acceso del controlador a la memoria con la protección de acceso directo a memoria (DMA).

# Arranque seguro UEFI.
El arranque seguro UEFI es un estándar de seguridad que protege los servidores de rootkits malintencionados. El arranque seguro garantiza que el servidor arranque solo el firmware y el software 
de confianza del fabricante de hardware. Cuando se inicia el servidor, el firmware comprueba la firma de cada componente de arranque, incluidos los controladores de firmware y el sistema operativo. 
Si las firmas son válidas, el servidor arranca y el firmware proporciona control al sistema operativo.

# Seguridad basada en virtualización (VBS).
Los servidores con núcleo protegido admiten la seguridad basada en virtualización (VBS) y la integridad de código basada en hipervisor (HVCI). VBS usa características de virtualización de hardware 
para crear y aislar una región segura de memoria del sistema operativo normal, y ofrecer protección contra toda una clase de vulnerabilidades usadas en ataques de minería de criptomonedas. VBS también
permite el uso de Credential Guard. En este caso, las credenciales de usuario y los secretos se almacenan en un contenedor virtual al que el sistema operativo no puede acceder directamente.

# Conectividad segura.
HTTPS y TLS 1.3 habilitados de forma predeterminada en Windows Server 2022. Las conexiones seguras son la base de los sistemas interconectados de la actualidad. Seguridad de la capa de transporte (TLS) 
1.3 es la versión más reciente del protocolo de seguridad más implementado en Internet, que cifra los datos para proporcionar un canal de comunicación seguro entre dos puntos de conexión. HTTPS y TLS 1.3 
ahora están habilitados de forma predeterminada en Windows Server 2022 para proteger los datos de los clientes que se conectan al servidor. Elimina algoritmos criptográficos obsoletos, mejora la seguridad 
con respecto a las versiones anteriores e intenta cifrar la mayor parte del protocolo de enlace posible. Obtenga más información sobre las versiones de TLS compatibles y sobre los conjuntos de cifrado admitidos.
Aunque TLS 1.3 a nivel de protocolo ahora está habilitado de manera predeterminada, las aplicaciones y servicios también deben admitirla activamente.

# DNS seguro: 
solicitudes cifradas de resolución de nombres DNS con DNS sobre HTTPS. El cliente DNS de Windows Server 2022 ahora admite DNS sobre HTTPS (DoH), que cifra las consultas de DNS mediante el protocolo HTTPS. DoH contribuye a mantener el tráfico lo más privado posible evitando la  interceptación y la manipulación de los datos DNS. Obtenga más información sobre cómo configurar el cliente DNS para usar DoH.

# Bloque de mensajes del servidor (SMB): 
cifrado SMB AES-256 para cuando la seguridad es la prioridad
Ahora, Windows Server admite los conjuntos criptográficos AES-256-GCM y AES-256-CCM para el cifrado de SMB. Windows negociará automáticamente este método de cifrado más avanzado al conectarse a otro equipo que lo
admita; esta opción también puede ser obligatoria a través de las directivas de grupo. Windows Server sigue siendo compatible con AES-128 para ofrecer compatibilidad de nivel inferior. Ahora, la firma AES-128-GMAC 
también acelera el rendimiento de firma.

# Funcionalidades del entorno híbrido de Azure.
Puede aumentar su eficacia y agilidad con funcionalidades híbridas integradas en Windows Server 2022 que le permiten ampliar los centros de datos a Azure más fácilmente que nunca.

# Servidores de Windows habilitados para Azure Arc.
Los servidores habilitados para Azure Arc con Windows Server 2022 llevan a las instancias de Windows Server locales y multinube a Azure con Azure Arc. Esta experiencia de administración 
está diseñada para ser coherente con la forma en que administra máquinas virtuales nativas de Azure. Cuando una máquina híbrida se conecta a Azure, se convierte en una máquina conectada 
y se trata como un recurso de Azure. Puede encontrar más información en la documentación de los servidores habilitados para Azure Arc.






