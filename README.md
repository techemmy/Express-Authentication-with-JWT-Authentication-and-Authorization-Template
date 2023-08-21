# Express-Authentication-with-JWT-Template

It uses Passport with custom LocalStrategy, JWT for authentication, and Passport-jwt for authorization and protection of routes.

### To use Bearer tokens for authorization instead of query parameter:
- Comment ExtractJWT.fromUrlQueryParameter in authentication/auth.js
- And uncomment ExtractJWT.fromAuthHeaderAsBearerToken() in authentication/auth.js
