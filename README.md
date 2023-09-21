<p align="center">
  <a href="https://vercel.com">
    <img src="https://assets.vercel.com/image/upload/v1588805858/repositories/vercel/logo.png" height="96">
    <h3 align="center">Vercel Examples</h3>
  </a>
</p>

Enjoy our curated collection of examples and solutions. Use these patterns to build your own robust and scalable applications.
Find our examples here: https://examples.vercel.live/ we're going to be shipping new examples weekly. Stay tuned!

## Examples

- [Edge Functions](/edge-functions) – Edge Functions are currently in Public Beta on Vercel. [Read the docs here.](https://vercel.com/docs/concepts/functions/edge-functions)
- [Solutions](/solutions) – Demos, Architectures and Best Practices

### Adding a new example

To quickly start contributing with a new example, run the following commands:

```bash
npm i
npm run new-example
```

#### The pre-commit hook

We use [Husky](https://typicode.github.io/husky/#/) to manage the pre-commit [Git hook](https://git-scm.com/docs/githooks) in this repo. Husky configures hooks automatically during install, so you don't need to do anything special to get them working, but if it fails to install, you can run the following command to install it manually:

```bash
npm run prepare
```

## Read the Docs

- [Vercel Docs](https://docs.vercel.com/)
- [Next.js Docs](https://nextjs.org/docs)

If you have any questions or suggestions about the docs, feel free to [open a discussion](https://github.com/vercel/examples/discussions), or [submit a PR](https://github.com/vercel/examples/pulls) with your suggestions!

## Provide Feedback

- [Start a Discussion](https://github.com/vercel/examples/discussions) with a question, piece of feedback, or idea you want to share with the team.
- [Open an Issue](https://github.com/vercel/examples/issues) if you believe you've encountered a bug that you want to flag for the team.

{
Enjoy our curated collection of examples and solutions. Use these patterns to build your own robust and scalable applications. We're going to be shipping new examples weekly. Stay tuned!

Edge Functions – Build high-performance APIs that are deployed to every Edge Network region. Learn more.
Edge Middleware – Provide speed and personalization to your users. Learn more.
Solutions – Demos, Architectures, and Best Practices
Starter – Fully functional applications that encompass an idea as a robust starting point.
Vercel Templates

Multiple examples are being featured in Vercel's Templates, visit that page for more advanced filtering options.

For Vercelians

Examples that have front matter metadata will create a new Draft template in Contentful, for more steps on how to publish a template, read Publishing Templates.

Adding a new example

To quickly start contributing with a new example, run the following commands:

pnpm i
pnpm new-example
If the script above isn't used, make sure the example complies with the following:

It must have a .gitignore similar to plop-templates/example/.gitignore
It must have a package.json similar to plop-templates/example/package.json (usage of Next.js is optional). The license should be MIT

**It must have a README.md similar to plop-templates/example/README.md. The example has to be able to include a demo URL (the Vercel team will deploy it!) and if it requires environment variables, it must have a .env.example file and instructions on how to set them up. Take bot-protection-datadome as an example.
**To customize the Vercel Deploy Button take a look at the docs, useful if the deployment has required environment variables.
**If using Next.js, it must have a .eslintrc.json similar to plop-templates/example/.eslintrc.json

**All Next.js examples should be using the same styling and layout provided by @vercel/examples-ui, its usage can be seen in the plop template
Adding a template

If you would like the example to be featured in vercel.com/templates then also add the front matter metadata to the top of the readme, like in bot-protection-datadome. To know all the possible values for each metadata take a look at internal/fields.json.

If you want to add related templates to your template, copy the slug from the other template into the relatedTemplates field, for example for <vercel.com/templates/next.js/monorepo-turborepo> the slug is monorepo-turborepo, as written in solutions/monorepo/README.md

The pre-commit hook

We use Husky to manage the pre-commit Git hook in this repo. Husky configures hooks automatically during install, so you don't need to do anything special to get them working, but if it fails to install, you can run the following command to install it manually:

pnpm run prepare
Code changes automatically go through Prettier and ESLint when you make a commit, please do not skip these steps unless they're broken and in that case let us known by creating an issue.

Read the Docs

Vercel Docs
Next.js Docs
If you have any questions or suggestions about the docs, feel free to open a discussion, or submit a PR with your suggestions!

Provide Feedback

Start a Discussion with a question, piece of feedback, or idea you want to share with the team.
Open an Issue if you believe you've encountered a bug that you want to flag for the team.
