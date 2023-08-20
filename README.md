# ReactJS and NextJS Snipets
### generate static files:
you need read this [article](https://nextjs.org/docs/pages/building-your-application/deploying/static-exports)

To enable a static export, change the output mode inside next.config.js
```
/**
 * @type {import('next').NextConfig}
 */
const nextConfig = {
  output: 'export', //add this line
 
  // Optional: Change links `/me` -> `/me/` and emit `/me.html` -> `/me/index.html`
  // trailingSlash: true,
 
  // Optional: Prevent automatic `/me` -> `/me/`, instead preserve `href`
  // skipTrailingSlashRedirect: true,
 
  // Optional: Change the output directory `out` -> `dist`
  // distDir: 'dist',
}
 
module.exports = nextConfig
```
