# OmniPIMS Frontend  
Vite + Bootstrap 5 UI

OmniPIMS Frontend is a lightweight user interface that interacts with the OmniPIMS API.  
It provides administrative tools for defining schemas, creating attributes, and managing dynamic entities.

## ✨ Features
- Schema builder UI
- Attribute editor
- Entity management interface
- Bootstrap 5 responsive design
- Minimalistic & clean layout
- API-driven forms and tables
- Docker-ready build

## 🛠 Tech Stack
- Vite
- JavaScript / TypeScript (optional)
- Bootstrap 5
- Axios (for API calls)

## 📂 Project Structure
``
/src
/components
/pages
/services
/styles
main.js
index.html
Dockerfile
``

## ▶ Running Locally

### Install
``npm install``


### Dev Server

``npm run dev``


### Build
``npm run build``


## 🐳 Docker
Build:

``docker build -t opims-frontend .``

Run:

``docker run -p 5173:80 opims-frontend``

## 🔌 Configuration
The frontend expects an environment variable:

``VITE_API_BASE_URL=http://localhost:3000``

Create a `.env` file with the URL of your backend.

## 📄 License
Apache 2.0 License.

