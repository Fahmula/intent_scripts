# Home Assistant Intent Scripts

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Fahmula/intent_scripts/graphs/commit-activity)
<!-- Replace 'your-github-username' and 'your-repo-name' with your actual GitHub username and repository name -->

This repository contains a collection of intent scripts designed to enhance the conversational abilities of your Home Assistant's voice assistant. These scripts allow for more natural and intuitive interactions with your smart home.

## Getting Started

These are the steps required to get the intent scripts working.

### Prerequisites

*   **Home Assistant:** Ensure you have a working installation of Home Assistant.
*   **Music Assistant Integration (Optional):** The `play_music` script requires the [Music Assistant integration](https://www.home-assistant.io/integrations/music_assistant/). Install and configure it if you intend to use this specific script.

### Installation

1. **Enable Intent Scripts:**

    Add the following line to your `configuration.yaml` file to enable intent script processing:

    ```yaml
    intent_script: !include intent_script.yaml
    ```

2. **Create `intent_script.yaml`:**

    Create a file named `intent_script.yaml` in your Home Assistant configuration directory (usually `~/.homeassistant` or where your `configuration.yaml` resides). This file will house your intent script definitions. You can also change the name to something else, just make sure to change the name in the include statement above.

3. **Add Supporting Scripts:**

    The `scripts` folder contains additional helper scripts that are required for certain intents. Add these scripts to your Home Assistant instance through the **Automations & Scenes** section (under **Settings**).

    **Important:** These helper scripts may need to be adjusted to match your specific entity names and device configurations. Review the scripts carefully before using them.

## Usage

Once installed, you can use voice commands to trigger these intents through your configured Home Assistant voice assistant.
