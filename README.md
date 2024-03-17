# Guru: AI PDF Book Assistant

Guru is an innovative AI-powered assistant designed to transform the way students interact with their PDF textbooks. By leveraging advanced natural language processing and machine learning techniques, Guru allows students to upload their PDF books and engage in interactive sessions where they can ask questions, receive summaries, and clarify concepts directly from their textbooks. This README provides an overview of Guru, including its features, setup instructions, and usage.

## Features

- **PDF Book Upload**: Users can add new books by uploading the PDF file, providing the book name, and specifying the book class.
- **Interactive AI Chat**: After processing the PDF and extracting its text, Guru uses this context to answer questions, making study sessions more engaging and productive.
- **Dynamic Content Understanding**: Utilizes NLP to understand and generate responses based on the book's content.
- **Document and Conversation Management**: Supports uploading images from the PDF and managing conversation flow with the AI.

## Setup

### Prerequisites

- Xcode 12 or later
- Swift 5.3 or later
- iOS 14.0 or later
- An OpenAI API key for GPT-3

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-github/guru-ai-pdf-assistant.git
cd guru-ai-pdf-assistant
```

2. **Open the project in Xcode**

Launch Xcode and open the `Guru.xcodeproj` file.

3. **Add your OpenAI API Key**

Navigate to `QuizModel.swift` and locate the following line:

```swift
"Authorization": "Bearer <Your-OpenAI-API-Key>"
```

Replace `<Your-OpenAI-API-Key>` with your actual OpenAI API key.

4. **Build and Run**

Select your target device or simulator and hit Run.

## Usage

### Adding a New Book

- Tap on the "+" button on the home screen to add a new book.
- Provide the required details (book name, class, and upload the PDF file).
- Once added, the book will appear on your home screen for easy access.

### Interacting with the AI

- Select a book from your home screen to start a session.
- Type your questions or requests related to the book's content in the chat interface.
- Guru will process your request and provide answers, summaries, or clarifications based on the PDF content.

## Contribution

Contributions are welcome! Please feel free to submit pull requests, report bugs, and suggest features.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- Thanks to OpenAI for providing the GPT-3 API.
- This project was inspired by the challenges faced by students in interacting with static PDF content.

---
