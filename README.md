# app-movilidad

PWA de ventas para vendedores en campo.  
Desarrollada por **Vibras Positivas HM**

## Funcionalidades
- Login con JWT (token 12 horas)
- Dashboard con pedidos y total del día
- Clientes filtrados por vendedor con búsqueda
- Ver cartera pendiente por cliente (facturas vencidas/vigentes)
- Nuevo pedido: buscar cliente → buscar productos con stock → confirmar
- Mis pedidos: historial con estados

## Configuración
En `index.html` línea `const API = 'http://localhost:3002/api';`  
Cambiar por la IP del servidor cuando se despliegue:
```
const API = 'http://192.168.1.12:3002/api';
```

## Instalación local
Abrir `index.html` directamente en el navegador del celular  
O servir con cualquier servidor estático.

---
*Vibras Positivas HM — Derechos de Autor Reservados*
