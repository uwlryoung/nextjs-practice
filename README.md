# nextjs-practice

## App Router Course 
This is the completed code for the Next.js App Router Course. A starting template was provided (see [below](#app-router-course)). The website is a fullstack application where the user can keep track of a company's invoices, customers and other company information.

This web application makes use of CSS Styling, creating layouts and pages, routing/navigating between pages, connecting the frontend to a database, static and dynamic rendering, creating/editing forms (invoices), user & login authentication and authorization, etc.

## Usage / Installation
If you would like to see the completed website, clone or fork the project. In your terminal in the root of the project, run `npm i` to download all packages. Then type in `npm run dev` and open up http://localhost:3000/. You won't be able to login without setting up a database and adding a secret key (see [Putting Data into the Database](#putting-data-into-the-database)).  

## Putting Data into the Database
To login and add/edit data on the website, you will have to connect to a database. Although you could do this through any provider, I recommend doing this through Vercel-Postgres since Vercel created Next.js. (It's also already coded to use this in the completed project). You can learn about setting up your database here: https://nextjs.org/learn/dashboard-app/setting-up-your-database (a chapter in Vercel's tutorial). 

Once you have done that, you can then seed the data by running `npm run seed`.

If you want to login, you will have to add a secret key to the `.env `file. To get the `.env` file, check out the starter code [here](https://github.com/vercel/next-learn/tree/main/dashboard/starter-example). Copy and paste the `.env.example` file into the root of your project and rename it to `.env` You should be able to copy and paste all of the .env data you need from Vercel after you set up your database. 

## Next.js App Router Course - Starter Template

A starter template for the Next.js App Router Course was provided. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

I also highly recommend taking this tutorial if you are interested in learning Next.js.
