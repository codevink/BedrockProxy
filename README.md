```markdown
# BedrockProxy

**BedrockProxy** is a lightweight and efficient proxy server for Minecraft Bedrock Edition, designed to facilitate seamless server management and enhance gameplay with advanced features and custom commands.

## Features
- **Seamless Server Management:** Easy server transfer and gamemode switching.
- **Enhanced Gameplay:** Commands for fullbright, jumpboost, fastbreak, low knockback, and more.
- **Custom Effects:** Control and apply various effects with ease.
- **Command Handling:** Robust and extendable command framework.

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/codevink/BedrockProxy.git
   cd BedrockProxy
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Configure:**
   Edit the `config.json` file to set your preferred settings.

4. **Run:**
   ```bash
   npm start
   ```

## Configuration
Configure the proxy by editing the `config.json` file:

```json
{
  "proxy_prefix": "bedrock",
  "default_ip": "127.0.0.1",
  "default_port": 19132
}
```

## Commands
- `/help`: Displays a list of available commands.
- `/time <day|night>`: Toggle between day and night in the server.
- `/flb <on|off>`: Enable or disable fullbright mode.
- `/trail <on|off>`: Toggle trail effects.
- `/transfer <IP> <Port>`: Transfer to another server.
- `/jb <amplifier>`: Set jumpboost effect.
- `/fb <amplifier>`: Enable or disable fastbreak effect.
- `/gm <mode>`: Set the gamemode (0: Survival, 1: Creative, 2: Adventure, 3: Spectator).
- `/lowkb <amplifier>`: Enable or disable low knockback effect.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or support, please contact t.me/codevink or vk.com/codevink.
```
