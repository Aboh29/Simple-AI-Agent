# Simple AI Agent 🤖

A lightweight command-line AI agent built with Python to demonstrate core software engineering and DevOps concepts such as modular design, Git branching workflows, logging, memory management, and release tagging.

## Features

* Interactive command-line chat interface
* Session memory tracking
* Calculator tool for evaluating mathematical expressions
* Time tool for retrieving the current date and time
* Persistent conversation logging
* Help command for user guidance
* Graceful error handling
* Git feature branch workflow implementation
* Versioned release (`v1.0.0`)

---

## Project Structure

```text
simple-ai-agent/
│
├── agent.py          # Main application entry point
├── tools.py          # Calculator and time tools
├── memory.py         # Session memory management
├── logger.py         # Persistent conversation logging
├── README.md         # Project documentation
├── .gitignore        # Git ignore rules
└── logs/             # Conversation log files (generated)
```

---

## Requirements

* Python 3.8+

Check your Python version:

```bash
python --version
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Aboh29/Simple-AI-Agent.git
cd Simple-AI-Agent
```

---

## Running the Agent

Start the application:

```bash
python agent.py
```

Example startup:

```text
==================================================
  Simple AI Agent (v1.0.0)
==================================================
Try: 'calc 4 + 5' or 'what time is it' or 'help'
Type 'exit' to quit.
```

---

## Available Commands

| Command             | Description                       | Example            |
| ------------------- | --------------------------------- | ------------------ |
| `calc <expression>` | Evaluate mathematical expressions | `calc 12 * 4`      |
| `time`              | Display current date and time     | `what time is it?` |
| `help`              | Show available commands           | `help`             |
| `exit` or `quit`    | Exit the application              | `exit`             |

---

## Example Session

```text
You: help

Agent: Available commands:
  calc <expr>   e.g. 'calc 12 * 4'
  time          ask what time it is
  help          show this message
  exit / quit   end the session

You: calc 10 * 96
Agent: 10 * 96 = 960

You: what time is it?
Agent: It is currently 00:14:27 on Friday, 26 June 2026.

You: exit
Agent: Goodbye! We had 11 turns this session.
```

---

## Git Workflow Used

This project was developed using a feature-branch workflow.

### Implemented branches

* `feature/tools`
* `feature/logging`
* `feature/cli-polish`

### Key milestones

* Initial project skeleton
* Memory module integration
* Tool integration
* Persistent logging
* CLI improvements
* Stable release tagging (`v1.0.0`)

---

## Release History

### v1.0.0

* Added calculator and time tools
* Added session memory
* Added persistent logging
* Added help command
* Improved error handling
* Finalized CLI experience

---

## Future Improvements

* Natural language understanding
* External API integration
* Unit testing
* Configuration files
* Docker support
* Web interface

---

## Author

**AbohA**

GitHub: https://github.com/Aboh29

---

## License

This project is licensed under the MIT License.
