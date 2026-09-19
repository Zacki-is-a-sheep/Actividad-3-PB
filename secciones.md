```
Página: Detalle del Pedido
│
├── Barra superior (Header)
│   ├── Breadcrumb ("Panel del productor > Pedido")
│   ├── Búsqueda (Lupa)
│   ├── Notificaciones (Campana con alerta)
│   └── Perfil de usuario 
│
├── Barra lateral (Sidebar)
│   ├── Logo y Nombre
│   ├── Menú de Navegación
│   │   ├── Resumen
│   │   ├── Catálogo
│   │   ├── Pedidos (Activo)
│   │   │   ├── Todos los pedidos (Seleccionado)
│   │   │   ├── Pendientes
│   │   │   ├── Entregados
│   │   │   └── Cancelados
│   │   ├── Reporte de ventas
│   │   └── Clima
│   │
│   └── Pie del sidebar (Usuario activo)
│       ├── Nombre y finca ("Ana Gómez - Finca La Esperanza")
│       └── Botón Salir / Cerrar sesión
│
└── Contenido principal
    │
    ├── Navegación secundaria ("Pedidos > Pedido #1042")
    │
    ├── Área principal (Productos)
    │   ├── Título de sección ("Productos solicitados")
    │   ├── Tabla / Lista de productos
    │   │   ├── Ítem 1: Tomate chonto (Confirmado | 2 libras | $3.200 | $6.400)
    │   │   ├── Ítem 2: Aguacate Hass (Disponibilidad pendiente | 3 unidades | $4.500 | $13.500)
    │   │   └── Ítem 3: Café pergamino (Confirmado | 1 libra | $18.000 | $18.000)
    │   │
    │   └── Total del pedido ($37.900)
    │
    └── Columna lateral de detalles
        │
        ├── Tarjeta: Datos del comprador
        │   ├── Nombre ("Laura Restrepo")
        │   ├── Teléfono ("310 442 7788")
        │   └── Instrucciones / Dirección ("Enviar por encomienda a Medellín...")
        │
        ├── Tarjeta: Estado del pedido
        │   ├── Estado actual ("Pendiente")
        │   ├── Botón de acción ("Marcar como entregado")
        │   └── Alerta de bloqueo ("No se puede entregar: 'Aguacate Hass' tiene disponibilidad pendiente")
        │
        └── Tarjeta: Historial del pedido (Línea de tiempo)
            ├── Evento 1: Pedido recibido (26 ago, 7:40 a.m. - Completado)
            ├── Evento 2: Confirmando disponibilidad (En curso)
            └── Evento 3: Preparación (Pendiente)
 ```