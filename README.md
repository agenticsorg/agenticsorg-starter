# Autonomous Coding Starter Pack

Welcome to the Autonomous Coding Starter Pack! This project is designed to help you get started with autonomous coding using Roo Code and SPARC.

## What is SPARC?



## Getting Started

Follow these steps to set up your environment and start using Roo Code and SPARC.

### 1. Create a GitHub Repository

If you don't have one already, create a new repository on GitHub. This will host your project files and allow for version control.

1. Go to [github.com](https://github.github.com).
2. Click the "+" icon in the top right and select "New repository".
3. Choose a name and description for your repository.
4. Decide if you want it public or private.
5. **Initialize this repository with:**
   - Add a README file (This provides an initial structure).
   - Add .gitignore (Select a template based on your project's primary language, e.g., Python, Node).
   - Choose a license.
6. Click "Create repository".

### 2. Work on Your Files

You have a few options for working with your project files:

- **Local Development:** Clone the repository to your local machine using Git.
- **Codespaces:** Use GitHub Codespaces for an online VS Code IDE environment. This is highly recommended for a seamless experience.
- **VS Code with Remote Development:** Open your local VS Code and connect to your Codespace.

### 3. Set up Roo Code

Roo Code is a VS Code extension that enables autonomous coding capabilities.

1. Open VS Code.
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
3. Search for "Roo Code" and install the extension.

### 4. Explore Roo Code Features

Roo Code provides several features to assist with autonomous development:

#### Modes

Modes are different AI experts designed to complete specific tasks. You can configure which Language Model (LLM) each mode uses.

- **Architect:** Helps with the design and architecture of your program.
- **Ask:** Used for asking questions and getting quick information.
- **Debugger:** Assists in identifying and fixing code issues.
- **Orchestrator:** Coordinates tasks and other modes for autonomous workflows.
- **Documentation Writer:** Helps in creating and updating project documentation.

You can add or customize modes via the settings.

#### MCP Servers

MCP Servers are used for integrating with external services. More details will be covered in a separate session.

#### Settings

Configure your LLM API keys and preferred models in the Roo Code settings.

- For coding tasks, models like Sonnet 3.7 are recommended.
- For complex thinking tasks, models like Gemini 2.5 Pro are suitable.
- For general questions, any model can be used.


### 5. Add create-sparc by RUV (founder Agentics Foundation)

About
SPARC (Specification, Pseudocode, Architecture, Refinement, Completion) is a methodology and set of tools for structured, agentic development. It guides you through the software development lifecycle with the help of AI agents.

To initialize SPARC in your project, run the following command:

```bash
npx create-sparc init --force
```

- customized modes for more control and automation
