┌──────────────────────────────────────────────────┐
│                     ACTORES                      │
│ Cliente            Seller          Administrador │
└──────────────────────────────────────────────────┘
                          ↓
┌──────────────────────────────────────────────────┐
│                   PRESENTACIÓN                   │
│            Aplicación Web → API REST             │
└──────────────────────────────────────────────────┘
                          ↓
┌──────────────────────────────────────────────────┐
│                LÓGICA DE NEGOCIO                 │
│  Usuarios | Sellers | Catálogo | Carrito         │
│                    | Pedidos                     │
└──────────────────────────────────────────────────┘
                          ↓
┌──────────────────────────────────────────────────┐
│                      DATOS                       │
│                  Base de datos                   │
└──────────────────────────────────────────────────┘

                          │
                          │ integraciones
                          ▼
┌──────────────────────────────────────────────────┐
│                SISTEMAS EXTERNOS                 │
│ Pasarela de pago | ERP | Servicio de envío       │
└──────────────────────────────────────────────────┘
Formato de Tabla EstándarSi prefieres la información estructurada como una tabla nativa de Markdown: