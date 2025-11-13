>  Este repositorio actúa como documentación principal del ecosistema **FitoPrice**, 
> un proyecto dividido en tres partes: frontend, backend y automatización (n8n).
> Aquí encontrarás información general, enlaces y la visión completa del proyecto.

# FitoPrice
FitoPrice es una plataforma que permite comparar precios de insumos agrícolas entre diferentes proveedores.
Ayuda a agricultores, distribuidores y cooperativas a tomar decisiones más rentables gracias al análisis histórico de precios, comparativas automáticas y alertas inteligentes.

## Finalidad del Proyecto
El objetivo principal de este proyecto fue explorar el potencial de la automatización con n8n, aplicándola a un caso real dentro del sector agrícola.
Durante el proceso, identifiqué una oportunidad: no existía una herramienta específica para comparar precios de productos fitosanitarios, fertilizantes o abonos, un nicho clave en la optimización de costes del campo.

FitoPrice nació como una plataforma experimental, con la misión de aportar transparencia, eficiencia y tecnología a un sector que históricamente ha carecido de herramientas digitales avanzadas


## Características

-  **Comparación en tiempo real** de precios de productos agrícolas
-  **Gráficas históricas** de evolución de precios
-  **Alertas automáticas** de variaciones significativas
-  **Scraping automatizado** mediante n8n y cron jobs
-  **Panel de administración** con control de empresas y fuentes de datos
-  **Interfaz moderna** desarrollada con React, Tailwind y shadcn/ui
-  **Backend gestionado con Supabase** (autenticación, almacenamiento e información de productos)


## Tecnologías

| Área | Tecnologías |
|------|--------------|
| **Frontend** | React · Vite · TypeScript · TailwindCSS · shadcn/ui |
| **Backend / BBDD** | Supabase (PostgreSQL · Auth · Storage) |
| **Automatización** | n8n (Docker · Render cron job) |
| **Despliegue** | Render · Vercel · Netlify |


## Uso
1. Accede al dashboard para ver los productos disponibles.  
2. Usa el buscador para filtrar por nombre o categoría.  
3. Haz clic en un producto para ver su evolución de precios y proveedores.  
4. (Admin) Inicia sesión para agregar o configurar nuevas empresas.


## Próximos pasos

- [ ] Sistema de alertas personalizadas por email  
- [ ] Integración de IA para predicción de precios  
- [ ] Panel de métricas de scraping  
- [ ] API pública para terceros  

## Repositorios
- [Frontend](https://github.com/josemmp2005/fitoprice-frontend)
- [Backend](https://github.com/josemmp2005/fitoprice-backend)
- [N8N](https://github.com/josemmp2005/fitoprice-scraping)

## Autor
Desarrollado por **José M. M. P.**  
-  [Contacto profesional](mailto:josemayenp@gmail.com)  
 - [Portfolio](https://portfolio-jmmp.netlify.app/) 
