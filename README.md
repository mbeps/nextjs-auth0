This is a simple project demonstrating the use of Auth0 with Next.JS. It's primarily designed for testing and understanding the integration of these two powerful tools. This project helps in exploring how to handle user authentication in a Next.js application using Auth0. We've chosen to use the traditional `pages` directory of Next.JS as the newer `app` directory is currently not supported.

The core features of this sample project include user sign-in, sign-up, sign-out, as well as sign-in using third-party providers.

# **Requirements**
These are the requirements needed to run the project:

- Node 18 LTS
- Next.JS 12
- Auth0 account

# **Features**

Here are the main features you can explore with this sample:

- Users can sign in using email and password
- Users can sign up for a new account
- Users can sign in using third-party authentication providers
- Users can sign out

# **Stack**

The main technologies used in this project are:

- [**Next.js**](https://nextjs.org/): Next.js is a popular React framework for building server-side rendered (SSR) and statically generated web applications. 

- [**Auth0**](https://auth0.com/): Auth0 is a flexible, drop-in solution to add authentication and authorization services to your applications. It provides a universal authentication & authorization platform for web, mobile, and legacy applications.

# **Running Application Locally**

Follow these steps to run the application locally. 

## **1. Clone the Project Locally**
```sh
git clone https://github.com/your-github-username/auth0-nextjs-sample.git
```

## **2. Set Up Environment**
1. Copy the `.env.example` file and rename it to `.env.local`
2. Populate the `.env.local` with the required Auth0 secrets. You will need to create an Auth0 application to get these credentials. If you are unsure of how to do this, follow the [Auth0 Application Setup Guide](https://auth0.com/docs/get-started/create-applications).

## **3. Install Dependencies**
Navigate to your project directory and run the following command to install the necessary dependencies:
```sh
yarn install
```

## **4. Run Project**
Finally, you can run the project using this command:
```sh
yarn dev
```
The application should now be running at `http://localhost:3000`.

# **Note**
This project uses the traditional `pages` directory structure of Next.JS and not the newer `app` directory as the latter is currently not supported with this particular setup.

Enjoy exploring Auth0 with Next.JS!
