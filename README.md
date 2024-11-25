# Stable Diffusion 3 - Matrix Bot

A Matrix bot for generating images using Stable Diffusion 3.

## Features
- Generate images from text prompts using Stable Diffusion 3.
- Easy to set up and run.
- Real-time interaction on Matrix.

## Prerequisites
- Python
- GPU with CUDA installed
- Matrix Developer account

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/neednotapply/stable-diffusion-3-matrix-bot.git
   cd stable-diffusion-3-Matrix-bot
   ```

2. Configure your tokens:
   - Open `config.json` and add your Matrix bot token and Huggingface token:
     ```json
     {
       "Matrix_bot_token": "YOUR-MATRIX-BOT-TOKEN-GOES-HERE",
       "huggingface_token": "YOUR-HUGGINGFACE-TOKEN-GOES-HERE"
     }
     ```

3. Run the bot using the batch script:
   ```bash
   sd3bot.bat
   ```

4. Setup the bot in Matrix Developer Portal. I can't help with this so you'll have to figure it out.

## Usage

- Use the `/sd3` command in Matrix followed by your prompt to generate an image.

## Contributing

Help make this better! Submit a PR if you have an improvement. 

## License

[LICENSE](LICENSE)

## Acknowledgements

- [Matrix.py](https://github.com/Rapptz/Matrix.py)
- [Huggingface](https://huggingface.co/)
- [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
