# NextJS-learner

This repo contains a general get starter pack of NextJS.

## Pages

Any pages you have goes under this folder. This is basically the `root` of your `routing`.

## Navigation

Navigation between pages are made via the `Link` component which you need to import from `next/link`.

Any sub-folder indside nav will act as the base of the router. for example, we have a directory inside _pages_ called _posts_. To go to that post we simple direct _posts/first-post_. This reudce the hassle of setting up router manually.

## Assests and meta data

Any static assets like images goes inside the top-level public directory.

- `image` : You have a image component provided by nextJS to handle the optimization. You need to import it as `next/image`.
