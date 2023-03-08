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

- `head` : You udpate your title and meta-information inside the `Head` component provided by next. you do that by importing `next/head`. Notice the difference between capital and lowercase letter that comes in `<head>` HTML element. You can use it to other compoenent.
- `script` : You can add any script tag inside the `Head` but use `next/script` component to take care of placing script properly. You can check out the use-case on the [first-post](pages/posts/first-post.js). Uncomment the script and see it in play. That is an example of how you include any third party script.
- `styling`: nextJs supports all kind of css, cass preprocessor like sass, css-in-js, etc. You can use modules as well.

only thing you have to take care of, if you want a global css, you need to have an `_app.js` component as a top-level react component and import the global css there.
