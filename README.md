# Boost CRM Status

Estado en tiempo real de los servicios de [Boost CRM](https://app.boost.com.gt), monitoreado via [Upptime](https://github.com/upptime/upptime).

## Servicios monitoreados

| Servicio | URL |
|----------|-----|
| Boost CRM (Web) | https://app.boost.com.gt |
| Boost API | https://boostapi.onrender.com/api |
| Boost API Health | https://boostapi.onrender.com/api/payments/webhooks/health |
| Boost Docs | https://boost-docs-blue.vercel.app |

## Como funciona

- GitHub Actions pinga cada endpoint cada 5 minutos
- Los resultados se guardan en este repositorio (carpeta `history/`)
- GitHub Pages genera la pagina de status automaticamente
- Si un servicio se cae, se crea un Issue automaticamente en este repo

## Setup

Este repositorio esta configurado con [Upptime](https://upptime.js.org). Los workflows corren automaticamente.

### Requisitos post-push

1. **GitHub Pages**: Settings > Pages > Source: "GitHub Actions"
2. **Permisos del workflow**: Settings > Actions > General > Workflow permissions: "Read and write permissions"
