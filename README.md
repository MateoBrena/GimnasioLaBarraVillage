# Sistema de Gestión Integral – La Barra Village 🏋️‍♂️

Plataforma web Full-Stack desarrollada a medida para la administración digital, control de accesos y reserva de clases del gimnasio de un barrio cerrado. 

El sistema centraliza la operación del espacio logrando prescindir de registros manuales y optimizando la convivencia comunitaria. Actualmente se encuentra en producción con **~165 usuarios activos** en sus primeros días de lanzamiento.

---

## 🚀 Funcionalidades Principales

### 📱 Módulo de Usuarios / Residentes
- **Acceso Inteligente por QR:** Registro automatizado de entradas y salidas de las instalaciones mediante el escaneo de códigos QR individuales desde el dispositivo móvil.
- **Concurrencia en Tiempo Real:** Visualización en vivo del aforo actual del gimnasio para que los residentes puedan planificar su visita y evitar horarios de alta densidad.
- **Cronograma y Reservas:** Consulta del calendario semanal de clases y sistema de reserva de cupos para optimizar la capacidad del lugar.
- **Gestión de Invitados:** Módulo para pre-autorizar el ingreso de visitas temporales a las instalaciones de forma segura.

### 💼 Módulo de Administración, Auditoría y Analíticas
- **Control Global de Usuarios y Clases:** Altas, bajas y modificación de perfiles de residentes autorizados, junto con la gestión de horarios y cupos disponibles.
- **Asistencia Automatizada:** Toma de asistencia automática a las clases en base a las reservas vigentes y los registros de acceso.
- **Centro de Avisos y Novedades:** Canal de comunicación directa dentro de la app para notificar de manera inmediata cambios de horarios, reformas o noticias importantes.
- **Métricas y Business Intelligence:** Panel estadístico que procesa los datos de uso del gimnasio en tiempo real, permitiendo visualizar:
  - Tiempo de permanencia promedio por usuario.
  - Concurrencia simultánea máxima alcanzada.
  - Cantidad de personas promedio por día.
  - Distribución y porcentajes de usuarios que entrenan en sala de musculación vs. los que asisten a clases guiadas.
- **Exportación de Datos (Auditoría):** Motor de descargas que permite extraer el historial completo de entradas/salidas y reservas en formato `.csv` para su posterior análisis y auditoría externa.

---

## ⚙️ Arquitectura de Negocio Especializada
> **Nota de Diseño:** A diferencia de un gimnasio comercial convencional, el sistema está adaptado a las dinámicas de un barrio privado. Toda la gestión de cobros y membresías se unifica de manera externa mediante las expensas de la administración central. Esto permitió enfocar la arquitectura del software puramente en la **experiencia de usuario (UX), el control de accesos, la analítica de datos y la optimización operativa de los espacios comunes.**

---

## 🛠️ Stack Tecnológico
- **Frontend / Framework:** Next.js (React) con arquitectura basada en componentes eficientes.
- **Estilos:** Tailwind CSS para una interfaz moderna, limpia y completamente responsive (Mobile-First).
- **Backend & Base de Datos:** Supabase (PostgreSQL) para el modelado relacional de datos, persistencia, procesamiento de agregaciones estadísticas y autenticación robusta.
- **Despliegue:** Vercel, garantizando alta disponibilidad y estabilidad en producción.
