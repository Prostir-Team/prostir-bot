# prostir-bot

Discord bot for managing the Prostir Discord

## Usage

Follow these steps in order to setup your bot.

1. Clone repo;
2. Create a `config.json`;
3. Fill in the config by following the [example](./config.example.json);
4. Run `npm run deploycmds` to register commands on your server;
5. Start the bot by running the `node .` command.

### Required permissions and intents

The bot requires the Message Content Intent to be enabled.
It is used by `level_system` module to measure message length.
It needs to be enabled, whether that module will be used or not,
unless you edit the [index.js](./index.js) main file.

The bot needs following permissions to be enabled:

- Manage Channels (`voice_managing`)
- Manage Roles (`voice_managing`)
- Move Members (`voice_managing`)
- Send Messages (`level_system`)

## License

Read the [LICENSE](./LICENSE) file.
