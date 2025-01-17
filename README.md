# dc-chat

A Discord auto-chat bot that sends random messages to a specified channel at random intervals.

## Features

- Customizable message delay intervals
- Random message selection from a predefined list

## Installation

1. Clone the repository:
```bash
git clone https://github.com/wxyz47/dc-chat.git
cd dc-chat
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Set up your configuration:
   - Edit `token.txt` to add your Discord token
   - Edit `messages.txt` to add your custom messages (one message per line)

## Usage

1. Run the script:
```bash
python3 main.py
```

2. Enter the required information:
   - Channel ID: The Discord channel ID where messages will be sent
   - Minimum delay: Minimum time (in seconds) between messages
   - Maximum delay: Maximum time (in seconds) between messages

3. The bot will start sending random messages from your messages.txt file at random intervals between your specified min and max delay times.

## Configuration Files

- `token.txt`: Contains your Discord authentication token
- `messages.txt`: Contains the messages to be sent (one message per line)

## Important Notes

- Use this responsibly and in accordance with Discord's terms of service
- Be mindful of rate limits and server rules
- Keep your token private and never share it with others

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

GitHub: [@wxyz47](https://github.com/wxyz47)
