# Rescate y Optimización Técnica: Peumayen.cl 🚀

Este proyecto documenta la intervención técnica integral realizada en el sitio **peumayen.cl** para restaurar su operatividad y optimizar su infraestructura tras la desactivación de sus funciones de eCommerce.

## ⚠️ El Problema
El sitio presentaba un **error crítico fatal** que impedía el acceso tanto al frontend como al panel de administración. Además, la base de datos se encontraba sobrecargada con residuos y tablas huérfanas de una instalación de WooCommerce desactivada, afectando el rendimiento del servidor.

## 🛠️ La Solución
Se aplicó un protocolo de mantenimiento senior dividido en tres fases:

1. **Recuperación del Sistema:** Restauración de la visibilidad del sitio mediante el aislamiento y desactivación selectiva de plugins conflictivos a nivel de servidor.
2. **Hardening de Seguridad:** Implementación de capas de protección vía `.htaccess` para bloquear la navegación de directorios y el protocolo XML-RPC, sumado a la ofuscación de la ruta de login administrativa.
3. **Optimización SQL:** Limpieza profunda de la base de datos, eliminando tablas huérfanas de WooCommerce y optimizando índices para mejorar la velocidad de respuesta (TTFB).

## 📊 Resultados
- **Antes:** Sitio inaccesible (Error 500 / Pantalla blanca).
- **Después:** Plataforma 100% operativa, segura y con una base de datos compacta.

## Descarga PDF
> **Descarga el [Informe Técnico Completo Aquí](./Caso_Estudio_Peumayen_Final.pdf)** con el detalle de la intervención.

---  
*Intervención realizada por Andrea Oyarce Espinoza - Especialista Web & SEO.*
