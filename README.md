# go-ai-coding-agent

A learning project on how to implement AI coding agents.
This project makes use of Anthropic Claude. 

Many thanks to Thorsten Ball for sharing his insights into the building process of AI agents.

## Usage

Export the anthropic API key first with

```
export ANTHROPIC_API_KEY="key here"
```

and then run

```
go run main.go
```

to start interacting with Claude.

### Example: simple file reading

You can ask the agent to answer the question inside the `question.txt` file with a prompt like:
`Can you answer the question in question.txt?`.

Alternatively you can ask it to explain the contents of the `main.go` file.

