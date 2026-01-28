# Unit Converter

A simple and intuitive web-based unit converter built with Astro and Tailwind CSS. This project is based on the [roadmap.sh Unit Converter project](https://roadmap.sh/projects/unit-converter).

## Features

- **Length Converter**: Convert between meters, feet, inches, miles, and more
- **Weight Converter**: Convert between kilograms, pounds, ounces, grams, and more
- **Temperature Converter**: Convert between Celsius, Fahrenheit, and Kelvin
- Clean and responsive UI built with Tailwind CSS
- Fast performance powered by Astro

## 🚀 Project Structure

```text
/
├── public/
├── src/
│   ├── components/
│   │   ├── card.astro
│   │   ├── footer.astro
│   │   └── header.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── length.astro
│   │   ├── temperature.astro
│   │   └── weight.astro
│   └── styles/
│       └── global.css
└── package.json
```

## Prerequisites

- Node.js (v18 or higher recommended)
- pnpm (or npm/yarn)

## Getting Started

1. **Clone the repository** (or download the project):

   ```sh
   git clone <repository-url>
   cd unit-converter
   ```

2. **Install dependencies**:

   ```sh
   pnpm install
   ```

   > **Note for Windows users**: If you encounter module resolution errors, the project includes a `.npmrc` file with `node-linker=hoisted` to ensure proper dependency resolution.

3. **Start the development server**:

   ```sh
   pnpm dev
   ```

   The application will be available at `http://localhost:4321`

4. **Build for production**:

   ```sh
   pnpm build
   ```

   The built files will be in the `./dist/` directory.

5. **Preview the production build**:

   ```sh
   pnpm preview
   ```

## 🧞 Available Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`            | Installs dependencies                            |
| `pnpm dev`                | Starts local dev server at `localhost:4321`      |
| `pnpm build`              | Build your production site to `./dist/`          |
| `pnpm preview`            | Preview your build locally, before deploying     |
| `pnpm astro ...`          | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help`    | Get help using the Astro CLI                     |

## How to Use

1. Open the application in your browser at `http://localhost:4321`
2. On the home page, select the type of conversion you want to perform:
   - **Length**: meters, feet, inches, kilometers, miles, etc.
   - **Weight**: kilograms, pounds, ounces, grams, etc.
   - **Temperature**: Celsius, Fahrenheit, Kelvin
3. Enter a value in any unit field
4. The conversion results will appear instantly in all other unit fields

## Technologies Used

- **[Astro](https://astro.build)**: Modern web framework for building fast, content-focused websites
- **[Tailwind CSS](https://tailwindcss.com)**: Utility-first CSS framework for rapid UI development

## Learn More

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [roadmap.sh Unit Converter Project](https://roadmap.sh/projects/unit-converter)
