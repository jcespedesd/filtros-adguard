# Sistema de Bloqueo de Contenidos en Cumplimiento Legal

## 📄 Descripción

Este repositorio contiene la documentación listas de dominios, configuraciones y archivos HTML utilizados para implementar un **sistema de bloqueo de contenido web**, conforme a la **Ley 679 de 2001** y el **Decreto 1524 de 2002** en Colombia. La solución combina herramientas de red y análisis para asegurar el cumplimiento y el monitoreo continuo de los dominios bloqueados.

---

## 🛠️ Componentes de la Solución

### 1. ⚙️ Mikrotik – Web Proxy
- Utilizado para **bloquear sitios web a nivel HTTP**.
- Se aplica una regla de redirección (`deny redirect-to`) hacia una página de advertencia alojada localmente.
- Ideal para bloquear rutas o URLs específicas que no pueden filtrarse vía DNS.

### 2. ⚙️  Firewall Mikrotik

### 3. ⚙️ DNS Recursivo
