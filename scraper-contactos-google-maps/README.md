# Scraper de contactos a través de Google Maps 📍🌍

Automatización que permite extraer contactos y leads desde Google Maps de forma estructurada:

- Hace una petición a una URL de Google Maps (previamente configurada con resultados de búsqueda) y extrae las URLs de los negocios listados.
- Filtra y elimina URLs duplicadas, luego limita la cantidad de resultados para controlar el scraping.
- Recorre cada URL individualmente, espera un tiempo para evitar bloqueos y accede al sitio web del negocio si está disponible.
- Desde la web de cada negocio, extrae direcciones de correo electrónico y información relevante sobre el negocio.
- Finalmente, filtra vacíos y duplicados, y guarda los correos y la información extraída en una hoja de cálculo de Google Sheets (o cualquier otro destino que elijas).
