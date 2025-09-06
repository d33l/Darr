# Subzero Mini Bot - WhatsApp Bot Project

## Overview
This is a WhatsApp Bot project called "Subzero Mini Bot" that provides automated WhatsApp functionality with a web-based pairing interface. The bot supports multi-device connections, status viewing, auto-reactions, and various commands.

## Recent Changes
- **2025-09-06**: Initial import from GitHub and Replit environment setup
- Configured for port 5000 instead of original 7860
- Created missing pair.html file
- Set up Node.js workflow
- Configured deployment for VM hosting

## Project Architecture
- **Frontend**: HTML-based web interface (main.html, pair.html)
- **Backend**: Express.js server with WhatsApp integration via Baileys library
- **Main Components**:
  - `index.js` - Express server entry point
  - `pair.js` - WhatsApp bot logic and command handlers
  - `msg.js` - Message processing utilities
  - `Id.js` - ID generation utilities
  - `admin.json` - Admin phone numbers list

## Key Features
- WhatsApp bot pairing through web interface
- Auto-status viewing and reactions
- YouTube audio download commands
- Message handling with quoted replies
- Newsletter auto-reactions
- Admin notifications
- Anti-call functionality
- View-once message handling

## Technical Details
- **Language**: Node.js
- **Framework**: Express.js
- **WhatsApp Library**: Baileys
- **Port**: 5000 (configured for Replit)
- **Deployment**: VM hosting for persistent connections

## User Preferences
- Frontend should remain on port 5000
- Backend uses localhost for internal communications
- Bot supports multiple admin numbers via admin.json
- Session data managed through GitHub integration

## Dependencies
Key packages include:
- baileys (WhatsApp multi-device library)
- express (web server)
- pino (logging)
- jimp (image processing)
- moment-timezone (time handling)
- Various media processing libraries (sharp, ytmp3, etc.)