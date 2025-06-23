# Changelog

Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
y este proyecto adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1-SNAPSHOT] - Actual

### Added
- Configuración inicial del proyecto Spring Cloud Gateway
- Integración con Eureka Client para service discovery
- Implementación de Caffeine Cache
- Sistema de documentación automática con GitHub Pages y Wiki
- Configuración de CI/CD con GitHub Actions
- Soporte para Docker y Docker Compose
- Actuator endpoints para monitoreo
- Enrutamiento a múltiples servicios (haberes, tesoreria, mercadopago, afipws, chequera)
- Scripts de generación automática de documentación

### Changed
- Migración a Java 24
- Actualización a Spring Boot 3.5.0
- Actualización a Spring Cloud 2025.0.0
- Actualización de dependencias y configuración
- Mejoras en el pipeline de CI/CD
- Optimización del Dockerfile

### Removed
- Config Server (migración a Eureka)
- Dependencias obsoletas

### Technical
- Configuración de logging mejorada
- Actualización de versiones de Spring Boot y Spring Cloud
- Mejoras en la configuración de Eureka
- Optimización de la configuración de caché

---

**Nota:** Este changelog se basa únicamente en el historial de git verificable. Los commits incluyen:
- Migración a Java 24 (3 semanas atrás)
- Actualizaciones de documentación y dependencias (3-4 meses atrás)
- Implementación de sistema de documentación automática (4 meses atrás)
- Upgrade a Spring Boot 3.4.2 y agregado de Caffeine cache
- Actualizaciones de versiones de Spring Boot y Spring Cloud
- Configuración de Eureka y eliminación de config server
- Implementación de facturador
- Mejoras en pipeline
- Agregado de Actuator
- Configuración de Docker 