# Challenges faced:

Finding the correct SDK version

Slow download speed from app store

Account verification delay

Understanding QR code scanning process
# Prodev Mobile Setup

## Steps Followed for Scaffolding

1. Navigate to Project Directory  
   cd prodev-mobile-setup

2. Initialize Expo Project  
   npx create-expo-app@latest .  
   - Used the latest Expo Router template  
   - Selected default options when prompted

3. Modify Home Screen  
   - Opened app/(tabs)/index.tsx  
   - Changed "Welcome!" to "First App Created"

4. Run the Application  
   npx expo start  
   - Scanned QR code with Expo Go app on Android  
   - App successfully loaded on physical device

## Observations from reset-project Command

After running npm run reset-project:

- What happened:  
  - The app directory was completely reset  
  - All tab navigation structure was removed  
  - A new minimal index.tsx file was created  
  - My custom text "First App Created" was replaced with default content

- Key takeaways:  
  - Command provides a clean slate for starting fresh  
  - Useful when wanting to rebuild app structure from scratch  
  - Warning: Permanently deletes existing code - use with caution

## Challenges Faced
- Finding correct SDK version on Expo Go
- Connecting phone to same network as computer
- Understanding the file-based routing structure