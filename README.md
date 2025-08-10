To reproduce the error for the tooling team, follow these steps:

1. Clone or download this project to your local machine.
2. Make sure you have pnpm installed (`corepack enable` if needed).
3. In the project root, run:

   ```
   pnpm install
   ```

4. Then run:

   ```
   pnpm knip
   ```

5. You will see the error:

   ```
   ERROR: Error loading ~/playwright-ct/playwright/index.tsx
   Reason: Unknown file extension ".css" for ~/playwright-ct/src/App.css
   ```
