Economy Plugin for EndStone
An advanced economy plugin designed for EndStone servers, featuring currency management, player transactions, and integration with popular Minecraft economy systems.

📦 Features
Currency System: Manage virtual currencies for players.

Transactions: Track and record player transactions.

Integration: Compatible with popular economy plugins like EssentialsX and Gringotts.

API Access: Provides a plugin API for developers to extend functionality.

🚀 Installation
Download the Plugin:

Clone this repository:

bash
Copy
Edit
git clone https://github.com/YourUsername/economy-plugin.git
Or download the ZIP file from the releases page.

Build the Plugin:

Navigate to the project directory:

bash
Copy
Edit
cd economy-plugin
Build the plugin using Go:

bash
Copy
Edit
go build -o EconomyPlugin.so -buildmode=plugin
Deploy the Plugin:

Place EconomyPlugin.so into your EndStone server's plugin directory.

Restart the Server:

Restart your EndStone server to load the new plugin.

🛠️ Configuration
Config File: Located at plugins/EconomyPlugin/config.yml.

Settings:

currency_name: Set the name of the virtual currency (e.g., "Coins").

starting_balance: Define the initial balance for new players.

transaction_fee: Set a percentage fee for transactions.

🔧 Usage
Commands:

/balance: Displays the player's current balance.

/pay <player> <amount>: Transfers currency to another player.

/eco reload: Reloads the plugin configuration.

API Usage:

Import the plugin API in your custom plugins:

go
Copy
Edit
import "github.com/YourUsername/economy-plugin/api"
🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -am 'Add new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.

Please ensure your code adheres to the project's coding standards and includes appropriate tests.
