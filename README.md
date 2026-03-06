Installation. 
1. You will need Node.js
2. Download the repository.
3. Upload to any convenient location.
4. Open CMD in the folder where the repository is located.
5. Write the following commands:
   - npm install --save-dev electron electron-builder
   - npm run dist:win //for Windows
   - npm run dist:nsis //for Linux
   - npm run dist:mac // for Mac
6. The folder "dist" appeared in the folder where you saved the repository. It contains the portable version and the full version of the program.
