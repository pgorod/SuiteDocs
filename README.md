[![Netlify Status](https://api.netlify.com/api/v1/badges/2cb9437a-4da2-47de-9dc7-11477d85c3ae/deploy-status)](https://app.netlify.com/sites/suitedocs/deploys)

# SuiteDocs

This is the Project for the SuiteCRM Documentation Site which you can browse at [https://docs.suitecrm.com](https://docs.suitecrm.com).

## Contributing

You can find instructions about contributing at [http://docs.suitecrm.com/community/contributing-to-docs/](http://docs.suitecrm.com/community/contributing-to-docs/).

## Architectural Overview

- this site's source content is hosted here, on **GitHub**.
- it is generated by [**Hugo**](https://github.com/gohugoio/hugo) static-site builder
- it uses the **Learn theme**
- the content is written in **Asciidoc** and is converted using asciidoctor Ruby engine
- it is automatically deployed on **Netlify**

## Workflow

The official site is generated from the `master` branch.

Currently, we are using a very simple workflow: you can direct your Pull Request directly to the `master` branch. 
Eventually we may decide to use other levels of staging on different branches before pulling content into `master`.

If you perform extensive work on the site (for example, translating a lot of content into a different language, 
or working on a new complex site feature in Go) we can consider providing a separate branch for you. 
This will allow you to run Preview Deploys on Netlify so you (and the rest of the Community) can browse your version 
before deploying it to `master`.

## Additional languages

We know that many members of this community are eager to read this Documentation in their own language. This will eventually be possible, but as this site is in its initial stage, we will only be working on two additional languages - Spanish and Russian for now.

We will add more languages later on. 

You can open an Issue if you have any questions or comments. Thank you.


## License
SuiteDocs is licensed under the GNU Free Documentation License. See [LICENSE.md](./LICENSE.md) for full license details.

