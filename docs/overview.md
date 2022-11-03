# Technical Documentation for Developer
</br>

## Application

The website is built with Nextjs. Nextjs is a flexible React framework that allows you to build blocks to help creating faster web applications. Another reason to choose Nextjs is that it is an exceptional choice for SEO rankings and creating dynamic web pages. Inside the app, state's information such as cart, userId, etc. are stored in Contexts, so those information can be passed down to other components when necessary. Reducers are also used to consolidate the state's update logic. State will be stored in localStorage, so whenever user refresh the page, state information will not be lost.
</br>

## Development Workflow
</br>

### Dependencies
Run the following command to install all dependencies on your working environment.
```bash
npm install
# or
yarn install
```
If you encounter any error regarding to error dependency tree, please try the following command instead.
```bash
npm/yarn install --legacy-peer-deps
# or
npm/yarn install --force
```


### Run the development server
Run the following command 
```bash
next dev
```
This command will run the application on development server. This is suitable when you are making changes and want to see it applied before deployment. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

