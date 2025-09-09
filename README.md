# Reka API Examples with Typescript

![Reka AI](assets/reka-ai-cover.jpeg)

[![Join our Discord](assets/discord-invite.png)](https://link.reka.ai/discord)

This repository showcases how to use the **Reka Research** to build intelligent apps that can search the web, structure responses, and support reasoning. It’s designed to help developers learn how to integrate and use Reka Research with different tools and frameworks.

##  📋 More Examples in Other Languages

- [Reka api-examples with Python](https://github.com/reka-ai/api-examples)
- [Reka api-examples with .NET](https://github.com/reka-ai/api-examples-dotnet)

## 📚 What's in this repo

| Folder/File                                | Description                                                                |
|--------------------------------------------|----------------------------------------------------------------------------|
| `reka-restaurants/`                        | App for researching and finding restaurants with Reka Research             |


##  🖥️ Getting Started (Typescript)

1. **Install requirements**  

   Make sure you have Node.js (version 18 or higher) and npm installed on your system.
   
   ```bash
   cd typescript/reka-restaurants
   npm install
   ```

2. **Get your Reka API Key**  

   Sign up at [Reka Platform](https://platform.reka.ai) and get your API key.

3. **Set environment variable**

   ```bash
   export REKA_API_KEY=your_api_key_here
   ```

4. **Run the app**
   
   ```bash
   npm run build
   npm start
   ```
   Open your browser and navigate to http://localhost:5173

## 🧪 Why use this repo?

- Learn how to use Reka Research with requests and OpenAI SDK
- Build agents that can think step-by-step and cite sources
- Learn to control structured outputs using `response_format`
- Control domain scope and search behavior using `web_search` config

## 🛠 Recommended Use Cases

- Web search with control over allowed domains
- Research agents with explainable reasoning steps

## 🤝 Contributions

Feel free to open issues or submit PRs to add more examples or improve existing ones.
