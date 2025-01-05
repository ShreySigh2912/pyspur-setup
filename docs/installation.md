# Docker Desktop Installation Guide for Mac

## Step 1: Download Docker Desktop
1. Visit the official Docker Desktop download page:
   https://www.docker.com/products/docker-desktop/
2. Click on "Download for Mac with Apple Silicon"
3. Wait for the .dmg file to download

## Step 2: Install Docker Desktop
1. Double-click the downloaded `Docker.dmg` file to open it
2. Drag the Docker icon to your Applications folder
3. Close the installer window

## Step 3: Start Docker Desktop
1. Open Finder
2. Go to Applications
3. Double-click Docker to launch it
4. When prompted, enter your Mac password to allow system extensions
5. Wait for Docker Desktop to start (you'll see the whale icon in your menu bar)

## Step 4: Verify Installation
1. Open Terminal
2. Run these commands to verify installation:
   ```bash
   docker --version
   docker-compose --version
   ```

## Step 5: Run PySpur
After Docker Desktop is running:
1. Open Terminal
2. Navigate to your project directory:
   ```bash
   cd pyspur-project
   ```
3. Start PySpur:
   ```bash
   docker-compose up -d
   ```
4. Access PySpur at http://localhost:3000

## Troubleshooting
- If Docker Desktop fails to start, try restarting your computer
- Make sure you have enough disk space (at least 5GB recommended)
- Check System Preferences > Security & Privacy if you see security prompts
- For any installation issues, visit Docker's official documentation at https://docs.docker.com/desktop/install/mac-install/