# Colombo Stock Exchange (CSE) API Documentation 📘📈  
Unofficial, OpenAPI-based documentation for the CSE’s public API endpoints.

---

## Overview 
This repository provides a **single source of truth** for the Colombo Stock Exchange (CSE) public API — defined using the **OpenAPI 3.0.3 specification**.  
All endpoint definitions, parameters, examples, and response structures are maintained inside the `openapi.yaml` file.

A simple `index.html` is included, which loads the YAML file through **Swagger UI** for an interactive, user-friendly view of the API documentation.

This project is inspired by earlier community work, especially  
[@GH0STH4CKER](https://github.com/GH0STH4CKER) whose initial API exploration helped kickstart this version.

---

## Features 
- Fully consolidated **OpenAPI 3.0.3** spec  
- All endpoint documentation stored in **one file** (`openapi.yaml`)  
- Interactive documentation via **SwaggerUI**  
- Examples added where applicable  
- Easy to clone, serve, and explore  

---

## How to Use 

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sihasmk/CSE-API-Docs.git
   ```
2. Open the project folder.
3. Serve `index.html` using any static server or Live Server extension:
   - VS Code: Right-click → **Open with Live Server**
   - Or use:
     ```bash
     python3 -m http.server
     ```
     and open `http://localhost:8000`.

You’ll see a fully interactive Swagger UI loaded with `openapi.yaml`.

---

## Contributing
I’m open to collaboration!  
Feel free to:
- Submit issues  
- Suggest improvements  
- Open pull requests  

Constructive contributions are always welcome.

---

## License
This project is open source. See the `LICENSE` file in the repository for details.

