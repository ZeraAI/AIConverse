![tiger ai](https://github.com/ZeraAI/AIConverse/assets/43397999/1abb5fde-6ba3-4517-b665-0d094f4116a6)

# ChatGPT Integration with C#

This project demonstrates the integration of ChatGPT, a language model developed by OpenAI, with C# using the OpenAI API. It allows you to interact with the ChatGPT model and generate human-like responses to user inputs.

## Prerequisites

To run this project, you'll need the following:

- .NET Core SDK 7.0.302
- OpenAI API key

## Installation

1. Clone the repository: `git clone git@github.com:ZeraAI/AIConverse.git`
2. Navigate to the project directory: `cd AIConverse`
3. Set your OpenAI API key in the `appsettings.json` file.

## Usage

1. Build the project: `dotnet build`
2. Run the application: `dotnet run`
3. Enter your input and press Enter.
4. The application will send the input to the ChatGPT model and display the generated response.

## Configuration

Make sure to set your OpenAI API key in the `appsettings.json` file. Replace `YOUR_API_KEY` with your actual API key:

```json
{
  "OpenAI": {
    "ApiKey": "YOUR_API_KEY"
  }
}
```

## Customization

You can customize the behavior of the ChatGPT integration by modifying the code in the `ChatGptService.cs` file. Adjust the parameters passed to the `OpenAIService.Complete()` method to control the response generation.

## License

This project is licensed under the [license name]. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [OpenAI](https://openai.com) for providing the ChatGPT model and API.
