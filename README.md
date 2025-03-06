# Scheduling Workflow

A project for managing scheduling workflows with development and production environments.

## Development

This project uses two main branches:
- `main` - Production branch
- `dev` - Development branch

### Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Run development server: `npm run dev`

### Workflow

1. Create feature branches from `dev`
2. Make your changes and commit
3. Create a pull request to `dev`
4. Once approved, changes will be merged to `dev`
5. Periodic releases will be made from `dev` to `main`

## Deployment

- Development deployments happen automatically when changes are merged to `dev`
- Production deployments happen automatically when changes are merged to `main`

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run linter
- `npm test` - Run tests