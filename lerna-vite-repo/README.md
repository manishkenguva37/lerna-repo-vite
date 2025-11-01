# lerna-vite-repo

This repository is a monorepo setup using Lerna and Vite, designed for managing a frontend application and a UI library.

## Project Structure

```
lerna-vite-repo
├── packages
│   ├── app-frontend        # Frontend application
│   └── ui-library          # UI component library
├── package.json            # Root configuration for the monorepo
├── lerna.json              # Lerna configuration
├── pnpm-workspace.yaml     # pnpm workspace configuration
├── tsconfig.base.json      # Base TypeScript configuration
├── .eslintrc.cjs           # ESLint configuration
├── .prettierrc             # Prettier configuration
└── .gitignore              # Git ignore file
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd lerna-vite-repo
   ```

2. **Install dependencies:**
   ```
   pnpm install
   ```

3. **Run the frontend application:**
   ```
   cd packages/app-frontend
   pnpm run dev
   ```

4. **Build the UI library:**
   ```
   cd packages/ui-library
   pnpm run build
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.