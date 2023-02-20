## Project Description
This is a [Next.js](https://nextjs.org/) project using [NASA Open Api](https://api.nasa.gov/)

On Landing Page, it will display the image the technologies that NASA is working on every day to explore space, understand the universe, and improve aeronautics. Users can access to Polychromatic page by clicking the link on top of the page.

On Polychromatic page, it will display the image of daily imagery of Earth collected by DSCOVR's Earth Polychromatic Imaging Camera (EPIC) instrument at specific time. Users can also choose specific time on the table to see the image of Earth to be displayed on the top of the table. 
## Getting Started

1. First, run vscode and open terminal to create next.js file:
    ```
    npx create-next-app appname
    ```

2. Once next.js app is created, open the app folder in vscode.

3. In terminal, move to your app folder and install axios:
    ```
    npm i axios
    # or
    yarn add axios
    ```

4. You are all set to use the code provided. To see the result or the change you make, 
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.
