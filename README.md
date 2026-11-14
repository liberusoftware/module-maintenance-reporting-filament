# Reporting Filament

Liberu Maintenance package for the Reporting Filament capability.

## Installation

```sh
composer require liberusoftware/module-maintenance-reporting-filament
```

This package is released under AGPL-3.0-or-later and follows the Maintenance application's
declared Laravel and PHP compatibility matrix.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-maintenance-reporting`.
- Actual Composer identity: `liberusoftware/module-maintenance-reporting-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/maintenance/filament/reporting.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [Maintenance](https://github.com/liberusoftware/project-maintenance-laravel-filament): Assets, work orders, schedules and field operations.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
