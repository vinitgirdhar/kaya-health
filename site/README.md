# Kaya landing page

Static website with no build dependencies. Serve this directory as the document root.

## Local preview

From the repository root, run `python3 -m http.server 3000 --directory site`.

## Vercel

Import the GitHub repository into the intended Vercel account. Select `site` as Root Directory and Other as the framework. No build command is needed. Alternatively, run `vercel --prod` from this directory after authenticating and selecting the intended project.

## Download

`downloads/kaya-debug.apk` is the debug APK built from commit ebe0cc5f3a1dcf3d81505b39b79a6e901635168d (version 1.1.2). It is explicitly labeled as a testing build. Replace it with a properly signed release APK and update the page copy before marketing it as a production release.

## Outstanding assets

Original app screenshots have not been supplied and are not present in the repository. Do not substitute invented UI screenshots. Add authentic captures and accessible image descriptions before considering the requested screenshot gallery complete.

Deployment to an existing personal website requires its URL/project identity. No Vercel deployment has been completed by this change.
