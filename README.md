# ServiceHub (monorepo)

## Overview
ServiceHub is a sample monorepo containing:
- backend: ASP.NET Core Web API
- frontend: Angular + Bootstrap
- mobile: Flutter app
- infra: IaC scripts (Terraform/Bicep)
- docs: API specs and architecture

## Tech stack
- Backend: .NET 8/9, ASP.NET Core Web API
- Frontend: Angular 16/18, TypeScript, Bootstrap 5
- Mobile: Flutter >= 3.x
- Infra: Terraform / Azure Bicep
- CI/CD: GitHub Actions (recommended)

## Local setup (quick)
### Backend
1. `cd backend/src`
2. `dotnet restore`
3. `dotnet run`

### Frontend
1. `cd frontend`
2. `npm install`
3. `ng serve`

### Mobile
1. `cd mobile`
2. `flutter pub get`
3. `flutter run`


## Branching
- `main` — production
- `develop` — integration
- `feature/<name>` — feature branches

## Contributing
See CONTRIBUTING.md

