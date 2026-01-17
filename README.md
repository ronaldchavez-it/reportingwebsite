## Descripción
Este proyecto es un sitio web que genera automáticamente reportes a partir de datos almacenados en una lista de SharePoint. La información se procesa mediante un flujo en **Azure Logic Apps**, que se conecta a un **modelo de IA en Azure Foundry** para generar los reportes automáticamente.

El sitio web permite visualizar estos reportes de manera sencilla y centralizada.

## Tecnologías utilizadas
- **Frontend:** HTML, CSS, JavaScript (Index.html)
- **Automatización y flujo de datos:** Azure Logic Apps
- **Inteligencia Artificial:** Azure AI Foundry
- **Repositorio y despliegue:** GitHub, Azure Static Web Apps
- **Origen de datos:** Lista de SharePoint

## Cómo funciona
1. Los datos se almacenan en una lista de SharePoint.
2. **Azure Logic Apps** extrae estos datos automáticamente.
3. Los datos se envían a un modelo de IA en **Azure Foundry**, que procesa y genera los reportes.
4. Los reportes generados se muestran en el sitio web alojado en **Azure Static Web Apps**.

## Despliegue
Para desplegar el sitio web:
1. Clona el repositorio.
2. Sube los archivos a tu proyecto de **Azure Static Web Apps**.
3. Conecta tu flujo de **Logic Apps** y el modelo de **AI Foundry** según tu configuración.

## Contribuciones
Si deseas contribuir a este proyecto, abre un **pull request** y describe los cambios realizados.

## Contacto
Para más información, puedes contactarme en ronaldschavez@outlook.com  
