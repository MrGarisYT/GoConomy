📦 Features
Currency System: Manage virtual currencies for players.

Transactions: Track and record player transactions.

Integration: Compatible with popular economy plugins like EssentialsX and Gringotts.

API Access: Provides a plugin API for developers to extend functionality.
🚀 Installation
Download the Plugin:

1. Clone this repository:
git clone https://github.com/YourUsername/economy-plugin.git
Or download the ZIP file from the releases page.

2. Build the Plugin:

Navigate to the project directory:
cd economy-plugin
Build the plugin using Go:
go build -o EconomyPlugin.so -buildmode=plugin

3. Deploy the Plugin:

Place EconomyPlugin.so into your EndStone server's plugin directory.

4. Restart the Server:

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
import "github.com/MrGarisYT/GoConomy/api"
