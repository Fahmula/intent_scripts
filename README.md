# Home Assistant Intent Scripts

This repository contains intent scripts that I'm developing for Home Assistant conversation agents. These scripts aim to enhance the conversational capabilities of Home Assistant.

## Getting Started

1. **Enable Intent Scripts**  
   Add the following line to your `configuration.yaml` file:
   ```yaml
   intent_script: !include intent_script.yaml
   ```

2. **Create the Script File**  
   Ensure you have a `intent_script.yaml` file in your Home Assistant `config` directory.

3. **Additional Scripts**  
   Scripts located in the `scripts` folder should be added to the `scripts` section under Automations & Scenes in Home Assistant.  
   **Note:** These scripts may require adjustments to match your specific entities.

## Updates and Future Plans

I plan to regularly update these scripts and may add more that align with my interests. Stay tuned for improvements and new features!
