# Dail.Discord
A Discord bot to find relevant content related to your needs

## Overview

Dail.Discord is a Node.js-based Discord bot designed to help users find relevant content. With its customizable configuration settings, you can tailor the bot to suit your specific needs.

## Prerequisites

- Node.js (version `12.x` or higher)
- npm (Node Package Manager)
- Docker (for containerized execution)

## Installation (Local Development)

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name


2. npm install


3. Configure the project:

   You need to modify `list.js`, `options.js`, and `snails.js` based on your requirements. These files contain configuration settings that should be adjusted for your project to function correctly.

4. Create a `.env` file:

   Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env

5. node index.js

   This will start the application on your local machine.

## Running the Project with Docker

After the image is built, run the container using:

```bash
docker run -d -e TOKEN=your-token-value your-image-name
