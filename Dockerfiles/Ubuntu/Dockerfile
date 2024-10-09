FROM ubuntu:latest

# Instalar las herramientas necesarias
RUN apt-get update && apt-get install -y \
    curl \
    vim \
    git \
    netcat \
    gnupg \
    && apt-get clean

# Configuración del directorio de trabajo
WORKDIR /app

# Exponer un puerto para la transferencia
EXPOSE 12345

# Ejecutar el contenedor en modo interactivo con bash
CMD ["bash"]
