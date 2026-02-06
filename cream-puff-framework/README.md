# Cream Puff Framework

A structured system prompt for AI coding assistants that prevents "overhelpfulness" by enforcing a staged workflow.

## What It Does

This framework forces AI into four distinct modes, requiring approval before advancing from planning to implementation:

| Mode | Purpose | When to Use |
|------|---------|-------------|
| **BRAINSTORM** | Explore options and trade-offs | Starting a new project or feature |
| **PLAN** | Create roadmaps with approval gates | Before writing any code |
| **IMPLEMENT** | Build against approved plans | After plan is confirmed |
| **DEBUG** | Rapid problem-solving | When something breaks |

## How to Use

1. Download `cream-puff-framework.md`
2. Upload it to your preferred AI chat interface (Claude, ChatGPT, etc.)
3. Start your conversation with a prompt like:
   - "Let's brainstorm how to build [your idea]"
   - "Let's plan out [your project]"

The AI will declare its current mode at the start of each response and wait for your approval before switching modes.

## Key Features

- **Mode declarations**: Every response states the current mode
- **Approval gates**: No code until you approve the plan
- **Clarification first**: The AI asks questions rather than assuming
- **Minimal structure**: Complete enough to work, light enough to leave room for your context

## Starter Prompts

The framework includes example prompts to get started:
- App idea exploration
- Workflow automation
- Game/creative projects
- Learning new concepts

## License

MIT License - Use freely, modify as needed.
