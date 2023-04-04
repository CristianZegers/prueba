graph LR
A[Ejecutivo Comercial (EC)] -- Presenta a --> B[TFP]
A -- Realiza levantamiento de muy alto nivel --> B
B -- Invita a --> C[Solution Consultant (SC)]
A -- Actualiza información --> D((CRM))
D -- Agenda reunión con SC --> C
C -- Identifican necesidades --> E[Necesidades del cliente]
C -- Discuten soluciones --> E
C -- Prepara detalle técnico --> F[Detalle técnico de la necesidad y posible solución]
F -- Se valida internamente --> G[Equipo de Operaciones y Tecnología]
G -- Factibilidad de la solución --> F
C -- Agenda reunión con prospecto --> E
E -- Presenta solución --> H[Propuesta de solución]
H -- Prepara presentación --> I[Presentación especial]
I -- Solicita apoyo --> J[Marketing (MKT)]
J -- Brinda apoyo --> I
E -- Acuerdo con la solución --> K[Elaborar propuesta comercial]
K -- Genera reunión interna --> L[Operaciones y Tecnología (O&T)]
L -- Entrega costo en X plazo --> K
F -- Solución nueva --> M[Valida con Finanzas el modelo de negocio y definen un Pricing]
K -- Agenda reunión con prospecto --> N[Presentar propuesta económica]
N -- Estrategia de cierre --> O[Estrategia de cierre]
O -- Firma contrato --> P[Firma del contrato]
P -- Implementación y onboarding --> Q[Delivery - Implementación y Onboarding de Operaciones]
