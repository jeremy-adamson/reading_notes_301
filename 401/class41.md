# React Part 4

## Questions

* Explain the concept of dynamic routes in Next.js and how they differ from static routes.
  * Static routes are hard-coded and will not change as the site is updated however dynamic routes can be modified on the fly automatically as the user adds to or deletes information the site contains. Typically there will be a static prefix and the dynamic portion is tacked on the end of the static portion.

* Describe the process of deploying a Next.js application. What are the key steps in volved and what are some deployment paltforms you can use?
  * The common deployment platform for Next.js is Vercel by creating an account, importing nextjs-blog, and give access to all repositories. Environment variables may need to be setup depending upon the site.

* How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.
  * Typically static files are placed in the root directory typically under a public folder for ease of access since the dynamic portions can be generated or deleted as needed. To access the static file all that is needed it to go into public/file and that's it

## Reading

* [Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)
* [Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)
* [Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)
* [Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-serving)
