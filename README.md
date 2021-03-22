JSON Web Token (JWT, sometimes pronounced JOT) an internet standard for creating JSON-based access tokens that assert some number of claims. The tokens are signed either using a private secret or a public/private key.

- Session-Based Auth
- JWT Based Auth
- Refresh Tokens
- Asymmetric JWT

# What is JWT?
- JSON Web Token
- Completely stateless
- 3 parts: header.data.signature
- Signature encrypt can be symmetrical or asymmetrical
- Symmetrical require same key to create JWT and validate
- Asymmetrical private key JWT, public key validates

# Pros and Cons
Pros|Cons
---|---
Stateless|Sharing secrets in Microservices
Great for APIs|Key management
Secure|Very tricky to consume correctly
Carry user info (username)|Storage of refresh token
Can store info that derive UX|Token revocation and control
No need for centelized database|

