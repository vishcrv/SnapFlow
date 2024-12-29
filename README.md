### Landing Page

![patch#1](https://github.com/user-attachments/assets/d5ac7f4e-23f5-4884-9727-46c07b819e55)


Ensure that package.json dev script has "--experimental-https" enabled.
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

First, run the development server:

1. Install Next.js
Run this in your project directory:


```bun add next react react-dom```
or if you're using npm:
```npm install next react react-dom```

2. run
```
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.


## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.



### Patch 1 
(dec-29-2024)
 WORK IN PROGRESS !

> Landing page structure with animated scroll and call to action button

`page.tsx`
- Included `Navbar` component for navigation.
- Implemented a full-screen landing section with a gradient background.
- Integrated `ContainerScroll` component for scroll animation.
- Added a prominent CTA `button` with hover effects and animation.
- Styled typography with a gradient text effect for the `headline`.
- Spacing errors are there (***WIP***)

- component changes :

1. navbar (logo, list of links, dashboard button)
2. container-scroll 
3. button

website reference _(codes)_ :
shadcn.ui  (dark mode, button)
ui.aceternity.com (scroll animation, dashboard:navbar)
bg.ibelick.com (background gradient)



