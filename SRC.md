# SRC.md - Portless

> Documentación de análisis de estructura de proyecto

## Información General

| Campo | Valor |
|-------|-------|
| **Nombre** | portless |
| **Tipo** | Herramienta de Desarrollo |
| **Descripción** | Reemplaza números de puerto con URLs .localhost estables para desarrollo local |
| **Stack** | Node.js, TypeScript |
| **Último análisis** | 2026-03-16 |

## Estructura

```
portless/
├── apps/            # Aplicaciones
├── packages/        # Paquetes npm
├── skills/          # Skills de agentes
├── tests/           # Tests
├── node_modules/    # Dependencias
├── pnpm-workspace.yaml  # Workspace config
├── turbo.json       # Turbo monorepo config
└── package.json     # Root package
```

## Características

- 🔗 URLs .localhost estables
- 🔒 Soporte HTTPS con certificados auto-generados
- 👤 Para humanos y agentes
- ⚡ Zero config

## Uso

```bash
portless myapp next dev
# -> https://myapp.localhost
```

## Estado

✅ Proyecto activo - npm install -g portless
