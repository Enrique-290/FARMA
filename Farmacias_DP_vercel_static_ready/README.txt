Farmacias y Consultorios DP — Deploy estático (multi‑página, sin JS)
Fecha: 2025-08-27

Contenido:
- index.html (TPV / Caja)
- inventario.html
- clientes.html
- consultorio.html
- laboratorio.html
- reportes.html
- facturacion.html
- admin.html
- chat.html
- config.html

Instrucciones Vercel (Zero‑Config, ultra simple):
1) En Vercel → Add New → Project → Import.
2) Elige “Other”. Arrastra TODOS estos .html (no uses frameworks).
3) Build Command: (vacío)   •   Output Directory: /
4) Deploy.

Comprobación rápida:
- https://TU-DOMINIO.vercel.app/        (TPV / Caja)
- https://TU-DOMINIO.vercel.app/inventario.html
- https://TU-DOMINIO.vercel.app/clientes.html
- … y así con las demás pestañas.

Notas:
- Esta versión no usa JavaScript; la navegación es por enlaces clásicos .html para evitar bloqueos de scripts o rutas rotas.
- Ideal para validar estructura y flujo visual. Luego podemos migrar a single-page con JS y conectar Firebase/roles.