# ScentiSync

A comprehensive operations management system with MongoDB integration.

## Features

- **Dynamic Table View**: Resizable columns, sorting, filtering and advanced search
- **MongoDB Integration**: Connect with MongoDB database for real-time data
- **RESTful API**: Complete API for tables and rows operations
- **Responsive Design**: Works on desktop and mobile devices

## Structure

- Operations page with collapsible sidebar
- Table view with dynamic columns and data
- API endpoints for operations, tables and rows
- MongoDB connection and schema validation

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- MongoDB/Mongoose
- Tailwind CSS
- DaisyUI

## API Endpoints

- `/api/operations/structure` - Get navigation structure
- `/api/tables` - CRUD operations for tables
- `/api/tables/[id]/rows` - Manage rows within tables
- `/api/tables/[id]/rows/[rowId]` - Individual row operations

## Getting Started

```bash
npm install
npm run dev
```