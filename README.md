![](src/public/images/banner.png)</br>
[![Licence](https://img.shields.io/github/license/shadowoff09/bcs-quotes)](https://github.com/shadowoff09/bcs-quotes/blob/main/LICENSE)
[![Deployments](https://img.shields.io/github/deployments/shadowoff09/bcs-quotes/bcs-quotes)](https://github.com/shadowoff09/bcs-quotes)
[![Commits](https://img.shields.io/github/last-commit/shadowoff09/bcs-quotes)](https://github.com/shadowoff09/bcs-quotes/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/shadowoff09/bcs-quotes)](https://github.com/shadowoff09/bcs-quotes)
[![Quotes](https://img.shields.io/badge/quotes-49-blue)](https://github.com/shadowoff09/bcs-quotes/blob/main/quotes.js)
[![Paypal](https://img.shields.io/badge/Paypal-Donate-blue)](https://paypal.me/diogogaspar123)
[![Ko-Fi](https://img.shields.io/badge/Ko--Fi-Donate-ff69b4)](https://ko-fi.com/shadowoff09)

# Better Call Saul quotes API

A simple API to retrieve some quotes from Better Call Saul!

:globe_with_meridians: Website: [https://bcs-quotes.vercel.app](https://bcs-quotes.vercel.app)

## API Documentation

### `GET /api/quotes`

Get a random quote in this format:

> [https://bcs-quotes.vercel.app/api/quotes](https://bcs-quotes.vercel.app/api/quotes)

    [
      {
        quote:
          "What’s the difference between a tick and a lawyer? The tick falls off when you’re dead!",
        author: "Jimmy McGill",
      },
    ]

### `GET /api/quotes/{number}`

Returns an array with `{number}` quotes e.g. `GET /api/quotes/5`.

> [https://bcs-quotes.vercel.app/api/quotes/5](https://bcs-quotes.vercel.app/api/quotes/5)

    [
      {
        quote:
          "Wow, my knight in shining armor. That is some sacrifice, quitting a job that you’ve been trying to tank since day one.",
        author: "Kim Wexler",
      },
      {
        quote: "The lesson is, if you’re gonna be a criminal, do your homework.",
        author: "Mike Erhmantraut",
      },
      {
        quote: "I pretend not to care, but he’s my brother. How can I not?",
        author: "Jimmy McGill",
      },
      {
        quote:
          "Why do they bury lawyers under 20 feet of dirt? Because deep down, they’re really good people.",
        author: "Jimmy McGill",
      },
      {
        quote:
          "If I had to do it all over again, I would maybe do some things differently. I just thought you should know that.",
        author: "Jimmy McGill",
      },
    ]

## Contributing

If you want to add some quotes, just add them in `src/quotes.js` file and do a pull request !

## Donate

If you liked this project feel free to donate me for future awesome projects!</br>

- [Paypal](https://paypal.me/diogogaspar123)</br>
- [Ko-fi](https://ko-fi.com/shadowoff09)

## Authors

- [@shadowoff09](https://www.github.com/shadowoff09)

## Other Versions

- [lucifer-quotes](https://github.com/shadowoff09/lucifer-quotes)
- [strangerthings-quotes](https://github.com/shadowoff09/strangerthings-quotes)

---

[![https://vercel.com?utm_source=shadowoff09&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=shadowoff09&utm_campaign=oss)


Made with :heart: and JavaScript.
