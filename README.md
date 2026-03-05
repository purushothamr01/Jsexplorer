# JS Explorer 🕵️🔍

JS Explorer is a powerful, client-side only JavaScript enumerator and beautifier custom-built for bug bounty hunters, penetration testers, and security researchers.

![JS Explorer Preview](recon.png) 

## Features

- **Blazing Fast Local Execution**: Everything happens securely within your browser. No files or data are ever sent to an external backend server.
- **Intelligent Beautification**: Quickly turn unreadable, compressed, and minified JavaScript into beautifully structured code ready for analysis.
- **Deep Enumeration**: Automatically scans code to instantly extract critical endpoints, hidden secrets, and valuable reconnaissance data including:
  - Full URLs, Domains, and Subdomains 
  - Internal IPs, Ports, and IPv6 Addresses
  - API Endpoints, Routes, and Versioned APIs (v1, v2)
  - GraphQL and WebSocket Endpoints
  - Hardcoded Secrets, Tokens, API Keys, and Cloud Credentials (AWS, Firebase, etc.)
  - JWTs and their seamlessly decoded payloads
  - 3rd Party Integrations and Configured Headers
- **Cyberpunk UI**: A stunning, modern interface featuring custom frosted multi-layered glass panels, neon accent glows, and a responsive layout that works flawlessly on desktop and mobile.
- **Export Data**: Easily export all discovered endpoints and secrets as properly structured JSON for integration into your broader pentesting toolchain.

## How to Use

1. **Open the App**: Simply open `index.html` in any modern web browser.
2. **Load Code**: You can load code in three ways:
   - Provide a direct URL to a JS file (utilizes a CORS proxy for seamless fetching).
   - Upload any local `.js`, `.json`, or `.txt` file directly into the tool.
   - Paste raw minified code directly into the editor view.
3. **Analyze**: Click the **Beautify Code** button to instantly format the code and trigger the deep enumeration engine.
4. **Export**: Review the findings dynamically in the sidebar or hit the "Copy" button to grab a JSON payload of everything discovered.

## Built With

- **HTML5 & Vanilla JS & CSS3**
- **CodeMirror**: For the incredibly smooth code editing experience.
- **JS-Beautify**: For untangling spaghetti code natively in the browser.

## Contributing

Contributions are always welcome. Have a new extraction Regex payload or a UI improvement idea? 
1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

---

*Disclaimer: JS Explorer is designed for ethical hacking, bug bounty hunting, and educational purposes. Do not use this tool on systems or codebases you do not have explicitly written permission to test.*
