# Implementation

This section explains how to publish `llms.txt` and `llms-full.txt` correctly after they have been prepared.

## Goal

The goal is to make the files publicly available in the website root so AI systems can find them easily and associate the site with the intended business, brand, author, and topic signals.

## Where the files should live

Upload the files to the public root of the main domain.

The expected URLs are:
- `/llms.txt`
- `/llms-full.txt`

In most setups, this means placing the files in the same directory as the site homepage or the same root directory where `robots.txt` and `sitemap.xml` are served.

## What to upload

- `llms.txt` — the concise version.
- `llms-full.txt` — the expanded version with broader context and entity information.

Use plain text and keep the filenames lowercase and exact.

## How to deploy

Choose the deployment method that matches the platform:

- **WordPress:** upload the files through the hosting file manager or FTP/SFTP into the site root.
- **Static sites:** place the files in the public or root build directory.
- **Custom stacks:** copy the files to the web root of the domain.
- **Managed hosting:** use the file manager or deployment settings provided by the host.

The important part is not the tool, but the location: the files must be reachable at the public root URL.

## Deployment checklist

Before you consider the job done, verify that:

- both files open in the browser without login;
- the URLs return a 200 response;
- the content is served as plain text;
- the files are not redirected to another location;
- the files are not blocked by robots or security rules;
- the file names are correct and lowercase;
- the content matches the final approved version.

## Recommended order

Use this order for deployment:

1. Finalize strategy, positioning, and ICP.
2. Prepare the llms files.
3. Upload them to the root directory.
4. Check public access.
5. Review how AI systems interpret the site.
6. Improve the website architecture after launch.

## Important note

Do not treat upload as the final step.

Publishing the files only makes sense when the site already reflects a clear brand strategy, content structure, entity logic, and conversion path. The files should describe a strong system, not try to compensate for a weak one.

## Best practice

If the site is a B2B business with multiple channels, make sure the files reflect the broader ecosystem:
- website,
- LinkedIn,
- YouTube,
- podcast,
- service pages,
- author pages,
- topic hubs.

The goal is to help AI understand the business as a whole, not only one isolated page.
