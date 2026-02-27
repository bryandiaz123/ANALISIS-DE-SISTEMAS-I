# Requirements – Cargo Expres

## Backlog
(PEGAR LINK DEL TABLERO AQUÍ)

## Historias de Usuario

1. Registrar paquete (Must)
2. Calcular ruta óptima (Must)
3. Visualizar ruta en mapa (Must)
4. Autenticación usuario (Should)
5. Editar paquete (Should)
6. Eliminar paquete (Could)
7. Historial de rutas (Could)
8. Reporte de entregas (Won’t)

## Criterios Given / When / Then

### Registrar paquete (Must)
Given que el administrador está autenticado  
When ingresa dirección válida  
Then el sistema guarda el paquete  

Given que la dirección está vacía  
When intenta guardar  
Then muestra error  

### Calcular ruta óptima (Must)
Given que existen paquetes registrados  
When solicita calcular ruta  
Then el sistema aplica Dijkstra  

Given que no hay suficientes paquetes  
When intenta calcular  
Then muestra advertencia  

## MVP Rationale
El MVP incluye registro de paquetes, cálculo de ruta y visualización.
Estas funciones resuelven el problema principal de optimización.
