The job tracker is A web app to organize and track internship applications across multiple job platforms.
# Features
-- Paste job posting URLs to automatically extract application data
-- Track applications from LinkedIn, Handshake, Indeed, and other major platforms
-- Update application status inline (Applied, Interview, Rejected, Offer, Accepted)
-- Export to Excel spreadsheet
-- Local data persistence with localStorage

# Tech Stack
Frontend
-- React 18 + TypeScript
-- Vite (build tool)
-- Tailwind CSS + shadcn/ui
-- React Hooks for state management
-- SheetJS (xlsx) for Excel export

Backend
-- None (fully client-side application)
-- localStorage for data persistence

Quick Start
#Install dependencies
npm install

Start dev server (runs on localhost:8080)
npm run dev

Build for production
npm run build

# Usage
Input
1. Paste job posting URL in the text field
2. Click "Add Job" - data auto-extracts and adds to table
3. Manually update status via dropdown as needed

Tracked Data (8 fields):

-- Company Name
-- Platform (LinkedIn, Handshake, etc.)
-- Internship Role
-- Application Date (auto-set)
-- Application Status (dropdown)
-- Remote/Hybrid/In Person
-- Paid/Unpaid
-- Job Description Summary

Output
-- Excel file: Internship_Tracking_[Date].xlsx
-- Contains all applications with current status
-- Download anytime via "Download as Excel" button

Data Storage:
-- All data stored in browser localStorage
-- Persists across sessions
--- Backup: Download Excel file regularly
-- Clear data: Clear browser storage

