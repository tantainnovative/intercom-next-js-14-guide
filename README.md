# Intercom Integration in Next.js 14 (App router)

This project demonstrates how to integrate Intercom chat widget into a Next.js 14 application. It provides a robust
setup to add Intercom to your Next.js projects using modern best practices for script loading and initialization.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (LTS version recommended, e.g., 14.x or 16.x)
- npm or Yarn
- Git

Additionally, you will need an Intercom account and your Intercom app ID to complete the integration.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/tantainnovative/intercom-next-js-14-guide.git
   cd intercom-nextjs-14
   ```

2. **Install the dependencies:**

   ```bash
   npm install
   ```

   or if you use Yarn:

   ```bash
   yarn install
   ```

3. **Set up the environment variables:**

   Create a `.env.local` file in the root directory of the project, and add the following line:

   ```plaintext
   NEXT_PUBLIC_INTERCOM_APP_ID=your_intercom_app_id_here
   ```

   Replace `your_intercom_app_id_here` with your actual Intercom app ID.

### Running the Application

To run the application locally:

```bash
npm run dev
```

or if you use Yarn:

```bash
yarn dev
```

This will start the development server on [http://localhost:3000](http://localhost:3000). Open this URL in your browser
to view the application.

## Project Structure

- `components/`: Contains all React components including `IntercomClientComponent`.
- `pages/`: Contains the Next.js pages.
- `public/`: Static files like images and fonts.
- `styles/`: CSS files for global styles.
- `types/global.d.ts`: TypeScript declarations for extending the global namespace.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

### Explanation

- **Project Description**: Begin with a brief introduction about what the repository is for.
- **Prerequisites**: List what the user needs before starting.
- **Getting Started**: Detailed steps to clone, setup, and run the project.
- **Project Structure**: A brief overview of how the project is organized.
- **Contributing**: Encourage contributions by specifying how others can contribute.
- **License**: Mention the type of license under which the project is released.
