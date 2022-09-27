
## Apple Store Clone w/ NextJS, TS, Tailwind, & Sanity

This project is built from the ground up using the tutorial by youtube creator "ILW Yennefer"(https://www.youtube.com/watch?v=DCTuw2P6DCU) to learn how to construct, plug in, and manage a deployed E-commerce platform from making it mobile-first reponsive on the frontend to structuring schemas and types so that sanity and next can seamlessly handle the user data management with Redux

## Fake User data to enter into stripe page to verify success page works
abc@gmail.com
fake credit card #: 4242 4242 4242 4242
exp date: 04/24 CVC: 424
Name on card: Jane Smith
United Arab Emirates

## Tech Used & Learning Takeaways

Tech: Next.js, Sanity.io, Redux Toolkit, TailwindCSS, TypeScript, Stripe API, Next-Auth, various animation libraies and code snippets

Takeaways: 
- Plugged in next-auth for signin using google dev console and sanity studio to allow the acknowledgement of credentials and successfully redirect user back to main site upon signin success.
- With every project compatibility issues pop up, here next-auth was initially incompatible with my node version 18. The most current vercel fix was to use the "--ignore-engines" flag but hopefully future versions fix that incompatibility.
- Stripe, Sanity, and vercels' own sites githubs provided some of the code and boilerplate used here, so keeping up on offical docs continues to be very useful to sculpting proper full stack apps from scratch.

# Next.js + Tailwind CSS Example

This example shows how to use [Tailwind CSS](https://tailwindcss.com/) [(v3.0)](https://tailwindcss.com/blog/tailwindcss-v3) with Next.js. It follows the steps outlined in the official [Tailwind docs](https://tailwindcss.com/docs/guides/nextjs).

```bash
yarn create next-app --example with-tailwindcss with-tailwindcss-app
```
