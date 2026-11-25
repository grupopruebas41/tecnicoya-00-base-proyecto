# TécnicoYa Huancayo · Base del proyecto (núcleo compartido)

**Repositorio:** https://github.com/grupopruebas41/tecnicoya-00-base-proyecto
**Proyecto completo:** https://github.com/grupopruebas41/TecnicoYA-Huancayo

## ¿Qué hace esta sección?
Estructura mínima para que todo funcione: configuración de Laravel y React, rutas de la API, modelos, respuestas comunes, página de inicio pública y menú principal. Las demás secciones se agregan encima.

## Requisitos que cubre
Apoyo a todos los RF

## Responsables
Todo el equipo

## Contenido
| Tipo | Archivos |
|---|---|
| Backend (Laravel 12) | 55 |
| Frontend (React 18) | 49 |
| Pruebas | 34 |
| Otros | 11 |

Las carpetas conservan la misma ruta que en el proyecto completo (`backend/api/...`, `frontend/web/...`), para que se pueda volver a unir sin cambios.

### Backend
- `backend/README.md`
- `backend/api/.dockerignore`
- `backend/api/.env.example`
- `backend/api/.env.testing.example`
- `backend/api/.gitattributes`
- `backend/api/app/Http/Controllers/Controller.php`
- `backend/api/app/Models/Announcement.php`
- `backend/api/app/Models/ClientProfile.php`
- `backend/api/app/Models/District.php`
- `backend/api/app/Models/MediaFile.php`
- `backend/api/app/Models/ServiceRateVersion.php`
- `backend/api/app/Models/ServiceRequest.php`
- `backend/api/app/Models/TechnicianDocument.php`
- `backend/api/app/Models/TechnicianProfile.php`
- `backend/api/app/Models/TechnicianService.php`
- `backend/api/app/Models/User.php`
- `backend/api/app/Providers/AppServiceProvider.php`
- `backend/api/app/Shared/Http/ApiExceptionRenderer.php`
- `backend/api/app/Shared/Http/ApiResponse.php`
- `backend/api/app/Shared/Http/Idempotency.php`
- `backend/api/app/Shared/Rules/RuleBook.php`
- `backend/api/app/Shared/Rules/RulesUnavailable.php`
- `backend/api/artisan`
- `backend/api/bootstrap/app.php`
- `backend/api/bootstrap/cache/.gitignore`
- `backend/api/bootstrap/providers.php`
- `backend/api/composer.json`
- `backend/api/composer.lock`
- `backend/api/config/ai.php`
- `backend/api/config/app.php`
- `backend/api/config/auth.php`
- `backend/api/config/cache.php`
- `backend/api/config/cors.php`
- `backend/api/config/database.php`
- `backend/api/config/filesystems.php`
- `backend/api/config/logging.php`
- `backend/api/config/mail.php`
- `backend/api/config/marketplace.php`
- `backend/api/config/queue.php`
- `backend/api/config/sanctum.php`
- … y 15 archivos más

### Frontend
- `frontend/README.md`
- `frontend/web/.dockerignore`
- `frontend/web/.env.example`
- `frontend/web/.gitignore`
- `frontend/web/eslint.config.js`
- `frontend/web/index.html`
- `frontend/web/package-lock.json`
- `frontend/web/package.json`
- `frontend/web/src/App.jsx`
- `frontend/web/src/ServiceCarousel.jsx`
- `frontend/web/src/VideoExperience.jsx`
- `frontend/web/src/components/ConfirmDialog.jsx`
- `frontend/web/src/features/administration/Sprint02Common.jsx`
- `frontend/web/src/features/administration/forms.jsx`
- `frontend/web/src/features/administration/labels.js`
- `frontend/web/src/features/client/ClientPages.jsx`
- `frontend/web/src/features/client/client.css`
- `frontend/web/src/features/client/clientRules.js`
- `frontend/web/src/features/client/helpContent.js`
- `frontend/web/src/features/client/pages.css`
- `frontend/web/src/features/panel/PanelShell.jsx`
- `frontend/web/src/features/panel/icons.jsx`
- `frontend/web/src/features/panel/panel.css`
- `frontend/web/src/features/panel/shellContext.js`
- `frontend/web/src/features/panel/useDismiss.js`
- `frontend/web/src/landing.css`
- `frontend/web/src/landing/About.jsx`
- `frontend/web/src/landing/HeroBackground.jsx`
- `frontend/web/src/landing/Home.jsx`
- `frontend/web/src/landing/Shared.jsx`
- `frontend/web/src/landing/config.js`
- `frontend/web/src/landing/contact.js`
- `frontend/web/src/landing/hooks.js`
- `frontend/web/src/landing/navigation.js`
- `frontend/web/src/landing/polish.css`
- `frontend/web/src/main.jsx`
- `frontend/web/src/marketplace.css`
- `frontend/web/src/scroll/FrameCache.js`
- `frontend/web/src/scroll/ScrollServices.jsx`
- `frontend/web/src/scroll/scroll-services.css`
- … y 9 archivos más

### Pruebas
- `backend/api/tests/Pest.php`
- `backend/api/tests/Support/CommittedDatabase.php`
- `backend/api/tests/Support/Sprint01.php`
- `backend/api/tests/Support/Sprint02.php`
- `backend/api/tests/Support/Sprint03.php`
- `backend/api/tests/Support/Sprint04.php`
- `backend/api/tests/Support/Sprint07.php`
- `backend/api/tests/Support/concurrent-request.php`
- `backend/api/tests/TestCase.php`
- `backend/api/tests/bootstrap.php`
- `backend/api/tests/fixtures/banner-1600x420.png`
- `backend/api/tests/fixtures/sprint02/documento.pdf`
- `backend/api/tests/fixtures/sprint02/foto-con-exif.jpg`
- `backend/api/tests/fixtures/sprint02/foto.gif`
- `backend/api/tests/fixtures/sprint02/foto.png`
- `backend/api/tests/fixtures/sprint02/foto.webp`
- `backend/api/tests/fixtures/sprint02/no-es-imagen.jpg`
- `backend/api/tests/matching-fixture.json`
- `frontend/web/cypress/e2e/sprint-02/landing.cy.js`
- `frontend/web/src/LandingRedesign.test.jsx`
- `frontend/web/src/Sprint02Landing.test.jsx`
- `frontend/web/src/VideoExperience.test.jsx`
- `frontend/web/src/features/administration/forms.test.jsx`
- `frontend/web/src/features/administration/labels.test.js`
- `frontend/web/src/features/client/clientDesign.test.jsx`
- `frontend/web/src/features/panel/panel.test.jsx`
- `frontend/web/src/features/panel/shellModern.test.jsx`
- `frontend/web/src/landing/AboutExperience.test.jsx`
- `frontend/web/src/landing/HeroBackground.test.jsx`
- `frontend/web/src/landing/Intro.test.jsx`
- `frontend/web/src/landing/Polish.test.jsx`
- `frontend/web/src/landing/navigation.test.jsx`
- `frontend/web/src/scroll/scroll.test.jsx`
- `frontend/web/src/styles/palette.test.js`

## ¿Cómo se ejecuta?
Esta sección es una parte del sistema. Para ejecutarla se necesita la sección **tecnicoya-00-base-proyecto** y la de **base de datos**; el sistema completo se levanta con `docker compose -f infrastructure/docker-compose.yml up -d`.
