# Express-Authentication-with-JWT-Authentication-or-Authorization-Template

To use Bearer tokens for authorization instead of query parameter:
- Comment ExtractJWT.fromUrlQueryParameter in authentication/auth.js
- And uncomment ExtractJWT.fromAuthHeaderAsBearerToken() in authentication/auth.js
