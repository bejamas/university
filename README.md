# GatherContent + Next.js demo

The open source GitHub repository is set-up to work with a GatherContent example project, publishing content to Vercel or Netlify, which then uses Next.js to present on the front end. You can adapt this to pull content from any of your projects, and see how quick you can build out websites and other experiences on top of GatherContent.

### Deploying

To deploy with **Vercel**, click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fbejamas%2Funiversity&env=GATHERCONTENT_API_USERNAME,GATHERCONTENT_API_KEY,GATHERCONTENT_PROJECT_ID&demo-title=Royal%20University%20of%20GatherContent&demo-description=GatherContent%20example%20project%2C%20publishing%20content%20to%20Vercel%20or%20Netlify%2C%20which%20then%20uses%20Next.js%20to%20present%20on%20the%20front%20end.&demo-url=https%3A%2F%2Funiversity.bejamas.io&demo-image=https%3A%2F%2Funiversity.bejamas.io%2Fwebsite-screenshot.png)

To deploy with **Netlify**, click:

[![Deploy with Vercel](https://www.netlify.com/img/deploy/button.svg)](https://github.com/bejamas/university)

### Required environment variables

```
GATHERCONTENT_API_USERNAME=<email>
GATHERCONTENT_API_KEY=<api-key>
GATHERCONTENT_PROJECT_ID=<project-id>
```

- `GATHERCONTENT_API_USERNAME` is your email address which you used to sign up to GatherContent
- `GATHERCONTENT_API_KEY` - follow [instructions](https://docs.gathercontent.com/reference#authentication) to find your API key
- `GATHERCONTENT_PROJECT_ID` - the easiest way to get the ID is to copy it from the URL. Go to your project, the structure will look like this: `gathercontent.com/content/<PROJECT-ID>/items`

### Local development

To run project locally, first you need to fork this repo or clone it:

```
git clone
```

Next, install all dependencies:

```
yarn
```

Create `.env` file and fill it up with all required environment variables

```
touch .env
```

Finally, you can start development server:

```
yarn develop
```
