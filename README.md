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

### Listing files

Ask Claude `What files are in this directory?` and you will see it list the content.

### File creation and editing

You can ask it `Create a file hello.js that I can run with node that prints 'Hello World!' to the console`.

Running in the terminal `node hello.js` should produce the desired result.

The agent can also edit files. You can request for example ` Change the file hello.js so that the string printed is 'Hello Giovanni'`, and running the file will produce the new string.


