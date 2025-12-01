```bash
better-agents init .


▗▄▄▖ ▗▄▄▄▖▗▄▄▄▖▗▄▄▄▖▗▄▄▄▖▗▄▄▖
▐▌ ▐▌▐▌     █    █  ▐▌   ▐▌ ▐▌
▐▛▀▚▖▐▛▀▀▘  █    █  ▐▛▀▀▘▐▛▀▚▖
▐▙▄▞▘▐▙▄▄▖  █    █  ▐▙▄▄▖▐▌ ▐▌

 ▗▄▖  ▗▄▄▖▗▄▄▄▖▗▖  ▗▖▗▄▄▄▖▗▄▄▖
▐▌ ▐▌▐▌   ▐▌   ▐▛▚▖▐▌  █ ▐▌
▐▛▀▜▌▐▌▝▜▌▐▛▀▀▘▐▌ ▝▜▌  █  ▝▀▚▖
▐▌ ▐▌▝▚▄▞▘▐▙▄▄▖▐▌  ▐▌  █ ▗▄▄▞▘



Setting up your agent project following the Better Agent Structure.

✔ What programming language do you want to use? Python
✔ What agent framework do you want to use? Agno
✔ What LLM provider is your agent going to use? OpenRouter
To get your OpenRouter API key, visit:
https://openrouter.ai/keys
✔ Enter your OpenRouter API key: *************************************************************************
✔ What is your preferred coding assistant for building the agent? Cursor (not installed)
✔︎ Your coding assistant will finish setup later if needed

To get your LangWatch API key, visit:
https://app.langwatch.ai/authorize
✔ Enter your LangWatch API key (for prompt management, scenarios, evaluations and observability): ******************************************************
To get your Smithery API key (optional), visit:
https://smithery.ai/account/api-keys
Smithery enables your coding agent to auto-discover MCP tools to integrate with your agent.
✔ Enter your Smithery API key (Optional - press Enter to skip):
✔ What is your agent going to do? test
✔ Project setup complete!
✔ Your agent project is ready!
ℹ Project location: /mnt/d/github/chiisen/better-agents-html
✅ Project setup complete!
Initial prompt:
"You are an expert AI agent developer. This project has been set up with Better Agents best practices.

First steps:
1. Read and understand the AGENTS.md file - it contains all the guidelines for this project
2. Update the AGENTS.md with specific details about what this project does
3. Create a comprehensive README.md explaining the project, setup, and usage
4. Set up the Python with uv + pytest (install uv for them if they don't have it)
5. Review the .cursorrules and llms.txt files for Agno best practices
6. Execute any installation steps needed yourself, for the library dependencies, the CLI tools, etc
7. Use the LangWatch MCP to learn about prompt management and testing
8. Start implementing the core agent functionality
9. Instrument the agent with LangWatch
10. Use Scenario tests to ensure the agent is working as expected, integrate with the agent and consider it done only when all scenarios pass, check scenario docs on how to implement
11. If available from the framework, tell the user how to open a dev server give them the url they will be able to access so they can play with the agent themselves, don't run it for them


Remember:
- The LLM and LangWatch API keys are already available in the .env file, you don't need to set them up
- ALWAYS use LangWatch Prompt CLI for prompts (ask the MCP how)
- ALWAYS write Scenario tests for new features (ask the MCP how)
- DO NOT test it "manually", always use the Scenario tests instead, do not open the dev server for the user, let them do it themselves only at the end of the implementation with everything working
- Test everything before considering it done

Agent Goal: test"
Project location: /mnt/d/github/chiisen/better-agents-html
⚠️  To start with Cursor:
  1. Open Cursor
  2. Open the folder: /mnt/d/github/chiisen/better-agents-html
  3. Use the initial prompt above with Cursor Composer
```