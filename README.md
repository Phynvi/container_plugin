# container

The container plugin implements inventory and bank support. The bank feature includes deposits, withdrawals, modes, and a command to open the bank.

## Installation

Install the plugin with Kryonic:

    kryonic install container

## Usage

Administrator users can open the bank by using the following command:

    ::bank

The plugin also exposes a few methods that can be called from other plugins:

#### open(player)

Open the bank.

#### deposit(player, slot, id, amount)

Deposit the item in the provided slot into the bank.

#### withdraw(player, slot, id, amount)

Withdraw the item in the provided slot from the bank.

## License

Released under an [MIT License](http://opensource.org/licenses/MIT)