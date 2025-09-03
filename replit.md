# Interstellar Web Proxy

## Overview
Interstellar is a web proxy service that provides access to various games and applications. The project serves as a proxy server with a web interface for accessing content.

## Recent Changes
- **2025-09-03**: Imported project and configured for Replit environment
- Upgraded to Node.js 18 for compatibility with @nebula-services/bare-server-node
- Configured server to run on port 5000 for Replit frontend
- Set up deployment configuration for autoscale

## Project Architecture
- **Backend**: Express.js server with bare server proxy functionality
- **Frontend**: Static HTML/CSS/JS files served from `/static` directory
- **Port**: 5000 (configured for Replit environment)
- **Host**: 0.0.0.0 (configured for Replit proxy access)

## Technical Stack
- Node.js 18+
- Express.js
- @nebula-services/bare-server-node for proxy functionality
- Static frontend with HTML/CSS/JS
- Package manager: npm

## Current State
The application is fully functional and running on Replit with proper configuration for the proxy environment.