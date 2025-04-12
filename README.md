# spring-ai-quickstart-anthropic

This is an example of a simple Spring AI application that connects to
Anthropic LLMs, e.g. Claude AI.

## Requirements
* Anthropic API key configured in `src/main/resources/application.properties`

## Run the application

```
./mvnw spring-boot:run
```

## Test the application

```
http :8080

HTTP/1.1 200 
Connection: keep-alive
Content-Length: 266
Content-Type: text/plain;charset=UTF-8
Date: Tue, 11 Apr 2025 08:05:00 GMT
Keep-Alive: timeout=60

I'm Claude, an AI created by Anthropic. I aim to be helpful, honest, and
harmless. I won't pretend to be human, and I'm always direct about being
an AI. I'm happy to help you with tasks or have a conversation, while being
clear about my capabilities and limitations.
```

## References
* [Spring AI Anthropic Chat](https://docs.spring.io/spring-ai/reference/api/chat/anthropic-chat.html)
* [Anthropic Console](https://console.anthropic.com/)
* [Anthropic Models](https://docs.anthropic.com/en/docs/about-claude/models/all-models)
* [Get started with Spring AI and Anthropic](https://nevenc.com/get-started-with-spring-ai-and-anthropic)
