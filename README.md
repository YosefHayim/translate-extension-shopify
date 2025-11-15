# Shopify Translation Extension

This repository contains a Shopify app extension built with Remix and TypeScript to manage and automate multilingual content for Shopify stores. The project focuses on providing a streamlined translation workflow, integrating directly with Shopify’s APIs, and offering a clean, extendable architecture for localization tasks.

## Overview

The extension is designed to assist merchants in translating store content efficiently. It leverages Shopify’s app framework, Prisma for data handling, and a Tailwind-powered UI. The structure supports additional extension modules inside the `/extensions` directory, making the project suitable for scalable multilingual features.

## Features

- Translation management for Shopify content.
- Remix-based app logic with server/client routing.
- Tailwind CSS for consistent design.
- Prisma ORM for structured data access.
- Shopify extension configuration files included.
- Ready for deployment through Shopify’s app environment.

## Tech Stack

- TypeScript  
- Remix  
- Prisma  
- TailwindCSS  
- Shopify App Framework  
- Vite  
- Docker (optional for containerized workflows)

## Project Structure

- `/app` – Remix routes, loaders, actions, UI, logic.  
- `/extensions` – Shopify extension modules.  
- `/prisma` – Schema and migrations.  
- `/public` – Assets for the app.  
- Config files for Vite, ESLint, Prettier, Tailwind, and Shopify.

## Getting Started

Install dependencies:

```bash
pnpm install
