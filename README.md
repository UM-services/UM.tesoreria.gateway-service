# UM.tesoreria.gateway-service

## Estado del CI/CD

[![UM.tesoreria.gateway-service CI](https://github.com/UM-services/UM.tesoreria.gateway-service/actions/workflows/maven.yml/badge.svg?branch=main)](https://github.com/UM-services/UM.tesoreria.gateway-service/actions/workflows/maven.yml)

Gateway Service para la arquitectura de microservicios de UM Tesorería. Este servicio actúa como punto de entrada único para todas las solicitudes a los microservicios, proporcionando enrutamiento dinámico, balanceo de carga y seguridad centralizada.

## Características Principales

- Enrutamiento dinámico de solicitudes
- Balanceo de carga
- Seguridad centralizada
- Control y monitoreo del tráfico
- Transformación y validación de solicitudes

## Requisitos

- Java 21
- Maven 3.9+
- Spring Boot 3.4.2
- Spring Cloud 2024.0.0

## Configuración

El servicio se puede configurar a través del archivo `application.yml`. Las principales configuraciones incluyen:

- Puertos y endpoints
- Rutas de servicios
- Configuraciones de seguridad
- Políticas de balanceo de carga

## Documentación

- [Documentación Técnica](https://um-services.github.io/UM.tesoreria.gateway-service)
- [Wiki del Proyecto](https://github.com/UM-services/UM.tesoreria.gateway-service/wiki)
- [Guía de Configuración](https://um-services.github.io/UM.tesoreria.gateway-service/configuration-guide.html)
- [Manual de Despliegue](https://um-services.github.io/UM.tesoreria.gateway-service/deployment-guide.html)
- [Documentación de API](https://um-services.github.io/UM.tesoreria.gateway-service/api-documentation.html)

## Estado del Proyecto

- [Issues Activos](https://github.com/UM-services/UM.tesoreria.gateway-service/issues)
- [Milestones](https://github.com/UM-services/UM.tesoreria.gateway-service/milestones)
- [Historial de Cambios](https://github.com/UM-services/UM.tesoreria.gateway-service/releases)

## Desarrollo

1. Clonar el repositorio:
```bash
git clone https://github.com/UM-services/UM.tesoreria.gateway-service.git
```

2. Instalar dependencias:
```bash
mvn install
```

3. Ejecutar el servicio:
```bash
mvn spring-boot:run
```

## Contribuir

1. Fork del repositorio
2. Crear una rama para la nueva funcionalidad (`git checkout -b feature/nueva-funcionalidad`)
3. Commit de los cambios (`git commit -am 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Crear un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.
