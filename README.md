Basic JWT

Endpoints:
- POST: /auth/register - For user registration
- POST: /auth/login - For login, after success you will get a token
- GET:  /api/hello - For authorized access, to test JWT logic

User JSON example:
{
  "username": "Test",
  "password": "Test"
}
