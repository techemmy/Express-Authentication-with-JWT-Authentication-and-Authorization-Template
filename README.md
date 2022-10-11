# Express-Authentication-with-JWT-Template

To use Bearer Authentication by passing the token in request.headers authentication:
- Comment ExtractJWT.fromUrlQueryParameter in authentication/auth.js
- And uncomment ExtractJWT.fromAuthHeaderAsBearerToken() in authentication/auth.js
