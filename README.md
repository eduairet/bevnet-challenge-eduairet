# BevNet Challenge

[BevNet](https://www.bevnet.com) coding challenge by Eduardo Aire Torres.

This repository contains the result of the challenge, it was created with the [mjml framework](https://mjml.io/) to make it as responsive as possible and to handle clients like Outlook. You can reach me out if there's any doubt about it at [hola@eduairet.com](mailto:hola@eduairet.com?subject=BevNet%20challenge%20Eduardo%20Aire)

## Content

1.  File provided by the recruiter: [index.html](./index.html)
2.  Source MJML file: [src/index.mjml](./src/index.mjml)
3.  MJML deliverable file (challenge file): [src/index.html](./src/index.html)

## Explanation

-   The footer and header (outlined sections in the following image) from the original file were injected into the `mjml` source file using `<mj-raw>`

![Example](./example-screenshot.png)

-   Dependencies and scripts in the repository are handled with `NPM` check [`package.json`](./package.json)
-   The script `npm run build` is used to generate the responsive `HTML` file that will be attached to the emails
-   The scripts `npm start` and `npm run server` are used for live development, you can run both using `npm run dev`
