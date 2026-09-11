AgriCircular Buyer Dashboard — Integration Source

This package contains the frontend source for the independent Buyers Dashboard.

Main entry:
  src/App.tsx

Styles:
  src/index.css

For integration:
1. Copy the src/ folder into the main AgriCircular frontend (or merge the relevant components/routes).
2. Add any missing dependencies from package.json to the main project's package.json.
3. The prototype uses mock listing/request data and browser localStorage; it has no required backend, authentication, payments, maps, or external APIs.
4. The dashboard routes are defined in src/App.tsx using Wouter.

This is a cleaned frontend source package; deployment/workspace metadata is intentionally excluded.
