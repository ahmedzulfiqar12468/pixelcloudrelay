# PixelCloud Relay - Access Manager

A comprehensive Electron-based access management system for DuoStream with relay PC control.

## Project Structure

- **relay-app**: Relay PC application for managing access, time limits, and user permissions
- **host-app**: Host PC application for approving relay connections and monitoring

## Features

### Relay PC Application
- Client token management and first-time approval
- Time limits per day, week, and month per client
- Connection scheduling (set specific times when clients can connect)
- Remaining time management and monitoring
- Automatic logout when time expires
- Concurrent user management
- PC shutdown permissions control
- Application termination permissions control

### Host PC Application
- Relay PC connection approval via Tailscale IP
- Password-protected connection authentication
- Real-time monitoring and status
- Client management interface

## Getting Started

See individual app directories for setup instructions.