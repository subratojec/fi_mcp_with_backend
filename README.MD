# Fi MCP Project Setup

## MCP Server Setup

1. **Prerequisites**
   - Go 1.23 or later ([installation instructions](https://go.dev/doc/install))

2. **Navigate to MCP server directory**
   ```bash
   cd fi-mcp-dev
   ```

3. **Install Go dependencies**
   ```bash
   go mod tidy
   ```

4. **Start the MCP server**
   ```bash
   FI_MCP_PORT=8080 go run .
   ```

   The server will start on [http://localhost:8080](http://localhost:8080)

## Python Backend Setup

1. **Navigate to Python backend directory**
   ```bash
   cd python-backend
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate virtual environment**
   ```bash
   # On Linux/macOS
   source venv/bin/activate
   
   # On Windows
   venv\Scripts\activate
   ```

4. **Install Python dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Start the Python server**
   ```bash
   python main.py
   ```
