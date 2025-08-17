# GooseAI
AI integration mod for Desktop goose using any AI provider (i think any)

![image1](https://raw.githubusercontent.com/Vexicle/GooseAI/refs/heads/main/Images/image1.png)

talk to the goose using artificial intelligence!

Makes the AI sentient (sort of), read the source for more details

## How to setup

Choose an AI provider; I recommend mistral because they give away free API usage (thank you mistral) or you can use openAI or use a local AI. Any AI provider that has a openai similar API should work.

the json examples below show usage with the mistral API.
### 1. In the JSON file, replace "key" with your real API key that you got from whatever provider you've chosen:
```json
"api_key": "kr7ApdZkEZr063jC2lfg67zAEAV3PB6Zy",
```
make sure to leave a comma at the end to not break the json file

### 2. Replace "endpoint-url" to your provider's enpoint:
```json
"endpoint": "https://api.mistral.ai/v1/chat/completions",
```
### 3. Replace "ai-model" with your chosen AI model:
```json
"model": "mistral-tiny",
```

after this, you should be good to go! go to source to view more details regarding the configs

## Download:

Release: [Latest Releases](https://github.com/Vexicle/GooseAI/releases)

Source: [Source code](https://github.com/Vexicle/GooseAI/)

Author: [eternalshell](https://github.com/Vexicle)

----

{% include install_guide.md modname="GooseAI" iszip=false %}
