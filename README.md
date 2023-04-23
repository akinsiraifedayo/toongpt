# ToonGPT

ToonGPT is a chatbot model built on the GPT-3.5 architecture. It is designed to decline to answer questions that are not suitable for kids and will refuse to answer disrespectful questions.
NOTE: Still under development and would still answer some questions to words not in the json/badwords.json file

## Usage

1. Open the `json/config.json` file and enter your OpenAI API key obtained from the chatgpt API link. [OPENAI API KEY](https://platform.openai.com/account/api-keys){:target="_blank"}

2. Enter your OpenAI API key in the `php/api.php` file as well.
3. Edit the settings in both files as needed.

### Creating a New Character

1. In the `json/config.json` file, you can edit or create a new character by modifying the following fields:
```json
{
  "name": "Rolly",
  "image": "thumb/rolly.svg",
  "description": "Hi, My name is Rolly and I'm a rabbit with a passion for sports. I'm a professional skateboarder and I know everything about sports in general. If you have any sports questions, I'm here to help! Let's play and learn together!",
  "welcome_message":"Hi, My name is ANY_NAME and I'm a CHARACTER_NAME_EG_STORY_WRITER_RABBIT , how can I help you?",
  "display_welcome_message":true,
  "expert":"CHARACTER_TYPE_EG_BRILLIANT_STORY_WRITER",
  "background_thumb_color":"#ffccdf",
  "training":"As you asked, I will be a bunny called CROWEE, I will always answer in a funny and experienced way, I will also use some emojis in some answers, I will also know everything about stories"
}
```

2. Modify the fields as needed to create a new character.

## License

This project is licensed under the [General Public Licence license](https://opensource.org/licenses/GPL).


