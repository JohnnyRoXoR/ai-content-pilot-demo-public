# AI Content Pilot Demo

AI Content Pilot is a toolkit for automating the creation and scheduling of social media posts using AI. The demo version provides a basic script for generating text using an OpenAI API and an example configuration file for scheduling posts.

## Features

* **Content generation**: Generates text based on a prompt using OpenAI's API.
* **Simple scheduling**: Reads a YAML configuration (`schedule.yaml`) for post times and content prompts.
* **Extensible design**: You can extend the script to integrate with platforms like Twitter, Telegram, or Discord.

## Quick Start

1. Install dependencies: `pip install openai pyyaml`.
2. Set your OpenAI API key in the environment variable `OPENAI_API_KEY`.
3. Run the script: `python content_pilot.py --config schedule.yaml`.

## Funding

Support further development by sponsoring or donating via the links in `FUNDING.yml`.
