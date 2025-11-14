# Configuración de Variables de Entorno

Este archivo documenta las variables de entorno necesarias para el proyecto.

## Variables Requeridas

```bash
# Base de datos PostgreSQL (requerido)
POSTGRES_URL="postgresql://usuario:contraseña@localhost:5432/dbname?sslmode=require"

# Ejemplo de otras variables que podrías necesitar:
# NEXT_PUBLIC_APP_URL="http://localhost:3000"
# NEXTAUTH_SECRET="tu_secreto_aqui"
# NEXTAUTH_URL="http://localhost:3000"
```

## Configuración Local

1. Copia este archivo a `.env.local` en la raíz del proyecto
2. Completa los valores reales
3. **NUNCA** subas el archivo `.env.local` al control de versiones

## Variables en Producción

En producción (Vercel, etc.), configura estas variables a través del panel de administración de tu plataforma de hosting.
