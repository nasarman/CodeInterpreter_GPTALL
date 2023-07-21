# GPT_CodeInterpreter Project 🤖

GPT_CodeInterpreter is an AI-driven project designed to carry out various tasks related to code interpretation. It is built on a plugin architecture that can easily extend new features.

## Video Demonstrations 🎥

To get a better understanding of GPT_CodeInterpreter's capabilities, you can watch the following video demonstrations:

<video src="https://github.com/boyueluzhipeng/GPT_CodeInterpreter/releases/download/v1.0.0/0718.mp4" controls title="https://szby.oss-cn-beijing.aliyuncs.com/07133.mp4"></video>
<video src="https://github.com/boyueluzhipeng/GPT_CodeInterpreter/releases/download/v1.0.0/07134.mp4" controls title="https://szby.oss-cn-beijing.aliyuncs.com/0718.mp4"></video>


This version adds the section for video demonstrations in English. The video links are clickable, allowing viewers to directly watch the demonstrations by clicking on them. If you have any other requirements or need further modifications, please feel free to let me know!

## Project Features

- **Plugin Architecture**: GPT_CodeInterpreter uses a flexible and extensible plugin architecture. Each plugin is a folder containing `functions.py` and `config.json` files, defining the functionality and configuration of the plugin.

### 🌟 Upcoming Features:

- **Official Plugin Integration🔌**: By processing the provided standard `openapi.yaml` from the official sources, we can automatically fetch the corresponding request URLs and method names. These will be combined with local functions and sent to GPT as if invoking local features. Upon user invocation, we'll categorize and request the respective API, ensuring real-time and precise feedback.

- **Role Masking🎭**: We've integrated numerous role-based features within our local plugins. For instance, the newly added `Vue` plugin can be used to modify local Vue projects effortlessly.

- **Join the Movement🤝**: We're actively inviting passionate individuals to collaborate with us on this project! Let's move towards a "metaGPT" future and co-develop an array of fascinating role plugins.

### 🌈 Future Plans:

- **Multi-client Interactions🔗**: When running multiple clients, we aspire for these clients to exchange messages, facilitating data transfer amongst different roles.

  **Preliminary Concept💡**:

  - **Server-side⚙️**: Operated by a GPT-4 "Administrator" preset role, its main duties will encompass assigning tasks based on users' "Role Masks" and preset objectives, and subsequently evaluating task completion rates.
  
  - **Client-side🖥️**: Users can autonomously register with the server and will then be able to receive dispatched tasks and feedback on task completion rates. It can execute certain tasks autonomously and also supports interaction via a web chat interface to accomplish associated tasks.

Let's look forward to the limitless possibilities these new features can offer! 🚀🎉

- **Function Manager**: The function manager is responsible for parsing and calling the functions defined in the `functions.py` file of each plugin.

- **AI Driven**: GPT_CodeInterpreter leverages the power of AI to understand and generate human language, enabling it to handle a variety of tasks related to code interpretation.

## Current Plugins

1. **General Plugin**: This plugin provides the functionality of displaying and uploading images.

2. **Python Interpreter Plugin**: This plugin includes a Python executor for running Python code, which is very useful for tasks such as data analysis and table processing.

3. **Vue Plugin**: Currently under development, this plugin is designed to work with Vue projects, automating the entire Vue project modification through the chat interface.

## Documentation

To get started with GPT_CodeInterpreter, please refer to the following documentation:

- 📚 [How to Install and Use GPT_CodeInterpreter](docs/install.md): Learn how to install and use GPT_CodeInterpreter in your projects.

- 🚀 [Publishing GPT_CodeInterpreter on Replit](docs/replit.md): A step-by-step guide on publishing GPT_CodeInterpreter on the Replit platform.

- 📝 [Understanding Environment Variables](docs/env.md) - 🔑 Configure GPT_CodeInterpreter with essential environment variables.

## Contributing

Contributions are welcome! Please read the contribution guide to learn how to contribute to this project.

## Contact

For any inquiries or collaboration opportunities, you can reach me via email at `402087139@qq.com`. 📧

## License

This project is licensed under the terms of the MIT license. 📜

This README now includes the link to the `env.md` file, indicated with the "Understanding Environment Variables" section. It also features an emoji flag (🔑) to highlight the importance of configuring environment variables for the project. If you have any more requests or need further assistance, please let me know!