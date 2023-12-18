# Smart Web Application with Computer Vision Capabilities

This project is a web application built with Blazor that utilizes Azure AI Vision and Azure OpenAI cognitive services to analyze and generate images based on prompts and URLs. The application integrates computer vision capabilities, including image recognition, object detection, and natural language processing.

## Prerequisites

Before getting started, make sure you have the following:

* Azure account
* Either an Azure OpenAI endpoint and apiKey or an OpenAI API key
* VS Code
* Docker..
* Dev Containers extension for VS Code

## Installation

To install and run the project, follow these steps:

1. Clone the repository.
2. Open the project in VS Code.
3. VS Code will prompt you to open the project in a dev container. Click 'Reopen in Container'.
4. Restore the packages by running `dotnet restore`.
5. Set the required environment variables:
    * OpenAI API key or Azure OpenAI API key: `export OPENAI_API_KEY=<your_api_key>`
    * Azure OpenAI endpoint (if using Azure OpenAI): `export OPENAI_ENDPOINT=<your_endpoint>`
    * Azure Computer Vision API key: `export VISION_API_KEY=<your_api_key>`
    * Azure Computer Vision endpoint: `export VISION_ENDPOINT=<your_endpoint>`
6. Run the project using `dotnet run`.

## Usage

[Provide instructions on how to use the computer vision capabilities in your web application]

## Contributing

[Explain how others can contribute to your project]

## License

[Specify the license under which your project is distributed]

## Packages used

* [Betalgo OpenAI](https://github.com/betalgo/openai)
* [Azure OpenAI](https://www.nuget.org/packages/Azure.AI.OpenAI/1.0.0-beta.10)
* [Azure.AI.Vision.ImageAnalysis](https://www.nuget.org/packages/Azure.AI.Vision.ImageAnalysis/0.15.1-beta.1)