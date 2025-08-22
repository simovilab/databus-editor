# GTFS Editor

[![Nuxt UI Pro](https://img.shields.io/badge/Made%20with-Nuxt%20UI%20Pro-00DC82?logo=nuxt&labelColor=020420)](https://ui.nuxt.com/pro)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, web-based GTFS (General Transit Feed Specification) editor built with Nuxt 4 and Nuxt UI Pro. This application provides an intuitive dashboard interface for creating, editing, and managing GTFS feeds for public transit systems.

## 🎯 Project Objectives

### Primary Goals
- **Simplified GTFS Management**: Provide a user-friendly interface for transit agencies to create and maintain GTFS feeds without technical expertise
- **Data Validation**: Built-in validation to ensure GTFS compliance and data integrity
- **Import/Export Capabilities**: Support for importing existing GTFS feeds and exporting compliant GTFS packages
- **Real-time Editing**: Live editing with instant feedback and preview capabilities
- **Collaborative Workflow**: Multi-user support with role-based permissions and change tracking

### Key Features
- 📊 **Dashboard Overview**: Comprehensive view of feed statistics and health metrics
- 🚌 **Route Management**: Visual route editor with map integration
- 🗓️ **Schedule Editor**: Intuitive calendar and timetable management
- 📍 **Stop Management**: Geographic stop placement and editing tools
- 🔍 **Data Validation**: Real-time GTFS specification compliance checking
- 📤 **Export Tools**: Generate compliant GTFS ZIP packages
- 📥 **Import Tools**: Parse and import existing GTFS feeds
- 🗺️ **Map Integration**: Visual editing with interactive maps
- 👥 **Multi-user Support**: Collaborative editing with user management
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Technology Stack

- **Frontend Framework**: [Nuxt 4](https://nuxt.com/) with Vue 3
- **UI Components**: [Nuxt UI Pro](https://ui.nuxt.com/pro)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Type Safety**: [TypeScript](https://www.typescriptlang.org/)
- **Package Manager**: [PNPM](https://pnpm.io/)
- **Data Validation**: [Zod](https://zod.dev/)
- **Date Handling**: [date-fns](https://date-fns.org/)
- **Visualization**: [@unovis](https://unovis.dev/)

## 📋 GTFS Specification Support

This editor supports all core GTFS files and fields as defined in the [GTFS Reference](https://gtfs.org/reference/):

### Required Files
- `agency.txt` - Transit agency information
- `stops.txt` - Stop locations and details
- `routes.txt` - Transit routes
- `trips.txt` - Individual trip instances
- `stop_times.txt` - Stop time schedules
- `calendar.txt` - Service date ranges

### Optional Files
- `calendar_dates.txt` - Service exceptions
- `fare_attributes.txt` - Fare information
- `fare_rules.txt` - Fare rules
- `shapes.txt` - Route geometry
- `frequencies.txt` - Frequency-based service
- `transfers.txt` - Transfer rules
- `feed_info.txt` - Feed metadata

## 🎯 Target Users

- **Transit Agencies**: Public transportation authorities managing bus, rail, and other transit services
- **Transportation Consultants**: Professionals helping agencies implement GTFS feeds
- **City Planners**: Urban planners working on transit accessibility and route optimization
- **Developers**: Transit app developers needing to create or modify GTFS data
- **Researchers**: Academic and policy researchers analyzing transit systems

## Setup

Make sure to install the dependencies:

```bash
pnpm install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
pnpm dev
```

## Production

Build the application for production:

```bash
pnpm build
```

Locally preview production build:

```bash
pnpm preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

## Renovate integration

Install [Renovate GitHub app](https://github.com/apps/renovate/installations/select_target) on your repository and you are good to go.
