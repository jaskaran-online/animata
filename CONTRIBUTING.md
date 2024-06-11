Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## Getting Started

To get a local copy up and running, please follow these simple steps.

### Prerequisites

Here is what you need to be able to run animata.

- Node.js (Version: >=18.x)
- Yarn _(recommended)_

## Development

### Setup

1. Clone the repo into a public GitHub repository (or fork https://github.com/codse/animata/fork).

   ```sh
   git clone https://github.com/codse/animata.git
   ```

2. Go to the project folder

   ```sh
   cd animata
   ```

3. Install packages with yarn

   ```sh
   yarn
   ```

4. Set up your `.env` file

   - Duplicate `.env.example` to `.env`

5. Setup Node

   If your Node version does not meet the project's requirements as instructed by the docs, "nvm" (Node Version Manager) allows using Node at the version required by the project:

   ```sh
   nvm use
   ```

   You first might need to install the specific version and then use it:

   ```sh
   nvm install && nvm use
   ```

   You can install nvm from [here](https://github.com/nvm-sh/nvm).

6. Start storybook

   ```sh
   yarn storybook
   ```

7. Start development server

   ```sh
   yarn dev
   ```

8. Open [http://localhost:3000](http://localhost:3000) in the browser to see the result.

## Contributing animations

1. Run `yarn animata:new` to create a new component. It will ask couple of questions and generate required files for you.
2. Create a new branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

If you have any questions, feel free to reach out to us.

## Folder structure

- `components/`: Contains all the components.
- `animata/`: Contains all the animations.
- `content/`: Contains the documentation pages.
- `public/`: Contains the static files.
- `app/`: Contains the main Next.js app.
- `templates/`: Contains the templates for the new components.

You will mostly be working in the `animata` and `content/docs` folders while creating new animations and documentation pages.