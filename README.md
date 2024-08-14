# 🥷 Anonymous Feedback Application

This is a **Next.js** application designed to allow users to receive anonymous feedback. It uses the **OpenAI API** to generate message suggestions and **Resend API** for handling email communications.

## Features

- **Anonymous Feedback**: Users can send feedback anonymously.
- **Message Suggestions**: The app uses OpenAI API to provide message suggestions.
  
## Limitations

- **API Cost**: The current live project is limited by the cost associated with using certain APIs (OpenAI and Resend). The application is designed to work with minimal usage due to these constraints. But the features are implemented and can be used if you have the respective api keys .
- **Single User**: Only one user can sign up and use the application. This is due to API key restrictions where the email associated with the API key can only be used.
- **Message Suggestions:** As the OpenAI api key consts money , you can't get suggestions in a live link of this project . But the feature is implemented and can be used if you have the OpenAI api key.

## Setup

To run the application locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/anonymous-feedback-app.git
    ```
2. **Install dependencies**:
    ```bash
    cd anonymous-feedback-app
    npm install
    ```
3. **Set up environment variables**:
   
   Create a `.env` file in the root of your project and add your API keys:
    
4. **Run the development server**:
    ```bash
    npm run dev
    ```

5. **Open the application**:
   
   Visit `http://localhost:3000` in your browser to see the application in action.

## Usage

1. **Sign Up**: Sign up using the email associated with the Resend API key.
2. **Receive Feedback**: Share the link to your feedback form to receive anonymous feedback.
3. **Message Suggestions**: Utilize the AI-generated message suggestions to craft responses.

## Future Enhancements

- **Multi-User Support**: Implementing multi-user support when API cost limitations are resolved.
- **Enhanced Feedback Options**: Expanding feedback mechanisms beyond text-based inputs.
- **Improved UI/UX**: Making the application more user-friendly.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This is an early-stage project with certain limitations due to API costs, but contributions and suggestions for improvement are welcome!
