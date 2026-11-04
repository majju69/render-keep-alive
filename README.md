   # render-keep-alive

   Pings my Render free-tier app every 10 minutes using GitHub Actions so it doesn't spin down.

   - Workflow: `.github/workflows/keep-alive.yml`
   - Target URL: https://card-6k1e.onrender.com
   - If GitHub disables the workflow after 60 days of inactivity, re-enable it from the Actions tab.
