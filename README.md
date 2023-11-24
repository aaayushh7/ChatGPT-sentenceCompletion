
# GoGPT Sentence Completion Tool

GoGPT Sentence Completion Tool is a powerful and efficient Go (Golang) application that leverages the OpenAI GPT (Generative Pre-trained Transformer) API to intelligently complete sentences. Whether you're writing articles, generating creative content, or enhancing your chatbot's responses, GoGPT provides a seamless integration of GPT capabilities into your Go projects.


## Key Features

 -> GPT-Powered Sentence Completion

 -> Easy Integration
 
 -> Contextual Understanding
## Usage

#### Clone the repo

```http
  git clone https://github.com/aaayushh7/ChatGPT-sentenceCompletion.git
```

#### Give your prompt

```http
  resp, err := client.Completion(ctx, gpt3.CompletionRequest{
		Prompt:    []string{"YOUR PROMPT HERE!"},
		MaxTokens: gpt3.IntPtr(30),
		Stop:      []string{"."},
		Echo:      true,
	})
```
#### Run tidy to download 3rd parties
```http
    cd ChatGPT-sentenceCompletion
    go mod tidy
```

#### Run the go program

```http
    go run main.go
```

Takes two numbers and returns the sum.


## Contributing

Contributions are always welcome!

If you have ideas for improvement, additional features, or bug fixes, feel free to open an issue or submit a pull request.

Please adhere to this project's `code of conduct`.

