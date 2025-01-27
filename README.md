# First AI Agent Bot Using Botpress

This project is a **Botpress-based AI agent** designed to interact with users, process images, and dynamically generate updated images with added furniture (e.g., sofas, beds, decor). The bot leverages the **Replicate API** for AI-powered image editing, allowing users to upload a room image and receive a modified version with their desired furniture items seamlessly integrated.

## Key Features
- **Image Upload & Processing**: Users can upload room images and select furniture items to add.
- **AI-Powered Editing**: Utilizes the `instruct-pix2pix` model from Replicate for realistic image modifications.
- **Dynamic Workflow**: Built with Botpress workflows and custom actions for seamless user interaction.
- **Customizable**: Easily extendable to support additional furniture types or editing prompts.

## Use Cases
- Interior design visualization.
- Virtual staging for real estate.
- Interactive furniture placement.

## Tech Stack
- **Botpress**: For bot development and workflow management.
- **Replicate API**: For AI-based image editing.
- **JavaScript**: Custom actions for API integration.

## How to Use
1. Upload a room image.
2. Select a furniture item (e.g., sofa, bed, decor).
3. Receive a modified image with the selected item added.
