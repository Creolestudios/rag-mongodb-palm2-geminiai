# Retrieval Augmented Generation with Mongodb Vector, Palm-2 and Gemini AI

This project is a Node.js application that uses Google's generative language model and MongoDB for data retrieval and augmentation. It allows users to perform semantic similarity searches on data by leveraging vector embeddings stored alongside metadata. The RAG methodology enhances language generation by incorporating retrieval-based information.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- MongoDB
- Google's generative language model API key

### Installing

1. Clone the repository
2. Install dependencies with `npm install`
3. Create a .env file in the root directory and add the following keys:
  ```
  PORT=8000
  GOOGLE_PALM_API_KEY=Your_Google_Palm_API_Key
  MONGODB_URI=Your_MongoDB_URI
  GEMINI_LLM_API_KEY=Your_Gemini_LLM_API_Key
  ```
  Replace `Your_Google_Palm_API_Key`, `Your_MongoDB_URI`, and `Your_Gemini_LLM_API_Key` with your actual keys.
4. Run the server with `npm start`

## Running the tests

Currently, there are no tests available for this project.

## Deployment

This project can be deployed using any platform that supports Node.js applications, such as Heroku, AWS, or Google Cloud.

## Built With

- Express - The web framework used
- MongoDB - The database used
- Google's generative language model - Used for text generation

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Video Explanation
For a detailed video explanation of the project, [click here](https://drive.google.com/file/d/1jbVuYctNXP3hLK3zhHncsRPauRJFiMma/view?usp=drive_link).
