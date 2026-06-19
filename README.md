# Ecosistema Autónomo de Asistencia Conversacional (Restaurante Inteligente)

Este repositorio contiene la arquitectura lógica y el flujo de trabajo desarrollado en **n8n** para automatizar de manera omnicanal la operación de un restaurante. El sistema integra Inteligencia Artificial avanzada para gestionar pedidos, procesar reservaciones en tiempo real y resolver dudas de atención al cliente sin intervención humana manual.

## Características Principales

- **Atención Omnicanal:** Centralización de canales de comunicación para una experiencia de usuario unificada.
- **Procesamiento de Lenguaje Natural (NLP):** Uso de Agentes de IA y Prompt Engineering para clasificar la intención del usuario (Pedido, Reservación, Soporte).
- **Gestión de Reservaciones:** Sincronización automatizada con bases de datos para verificar disponibilidad en tiempo real.
- **Automatización de Pedidos:** Flujo estructurado para la toma de órdenes, cálculo de totales y confirmación de despacho.

## Tecnologías Utilizadas

- **Core Engine:** n8n (Workflow Automation)
- **AI & LLMs:** OpenAI API / Anthropic (Agentes Autónomos y RAG)
- **Data & Backend:** Webhooks, REST APIs, JSON Parsing
- **Integraciones:** Sistemas de mensajería omnicanal y gestión de bases de datos relacionales.

## Estructura del Repositorio

- `restaurante-inteligente-flow.json`: Archivo nativo de n8n que contiene todos los nodos, conexiones, funciones de JavaScript para transformar datos y configuraciones del agente de IA.
- `README.md`: Documentación técnica del proyecto.

## Instrucciones de Instalación

1. Descarga el archivo `restaurante-inteligente-flow.json` de este repositorio.
2. Abre tu instancia de **n8n**.
3. Crea un nuevo flujo de trabajo (Workflow).
4. En el menú de la esquina superior derecha, selecciona **Import from File** y elige el archivo `.json` descargado.
5. Configura tus propias credenciales y variables de entorno para las APIs utilizadas (Webhooks, OpenAI, etc.).
