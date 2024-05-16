# 🗓️ Holiday Bot for Telegram

Welcome to the Holiday Bot repository! This project contains the code for a Telegram bot that delivers holiday information, programmed using n8n. The bot provides users with details about upcoming holidays and additional features to enhance the user experience.

## 🚀 Features

- **Holiday Information**: Get information about public holidays directly in your Telegram chat.


## 🛠️ Usage
You can use it directly from telegram clicking on https://t.me/feriadoscl_bot

## 🛠️ Installation (only if you want to run your own bot instance)

1. Clone the repository:
   ```bash
   git clone https://github.com/asophila/feriadoscl_bot.git
   cd feriadoscl_bot
   ```

2. Import the n8n workflow:
   - Open your n8n instance.
   - Navigate to `Workflows` > `Import`.
   - Select the `feriadoscl_bot.json` file from this repository and import it.

3. Set up credentials:
   - Talk to @botfather to get your bot running, use the secret token to create telegram credentials on your n8n environment.

4. Activate the workflow:
   - Go to `Workflows`, find the imported Holiday Bot workflow, and activate it.

## 📋 Usage

Once the bot is running, you can interact with it on Telegram by sending commands:

- `/start` - Start the bot and get a welcome message.

## 🔜 Next Steps

Here are some exciting features planned:

* **Buttons**: Implement interactive buttons instead of random text inputs.
* **Monthly Queries**: Allow users to request holidays for a specific month.
* **Vacation Recommendations**: Recommend vacation days to maximize consecutive days off.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 💬 Contact

For questions or suggestions, please open an issue or contact the repository owner.

---

Happy holidays! 🎉
