# JSON Web Tokens (JWT) 

## Introduction
JSON Web Tokens (JWTs) are a compact, URL-safe means of representing claims between two parties. They are commonly used for authentication and authorization purposes in stateless, token-based systems.

## JWT Basics
### What is a JSON Web Token (JWT)?
A JSON Web Token (JWT) is a compact, URL-safe representation of claims transmitted between parties. It consists of three parts: a header, a payload, and a signature.

### When should we use JSON Web Tokens?
JSON Web Tokens can be used in various scenarios, particularly in stateless, token-based authentication systems. They are commonly used when there is a need for secure transmission of information between parties and when the server needs to authenticate and authorize clients.

### Claims are expected in which structural component of a JWT?
Claims are expected to be present in the payload component of a JWT. The payload contains the actual data or claims being transmitted between parties.

### Are JWTs secure?
JWTs themselves do not provide inherent security. The security of JWTs depends on proper implementation and adherence to security best practices. Measures such as verifying the signature, properly handling sensitive data, and protecting the private key used for signing the JWT are crucial for ensuring the security of JWT-based systems.

## Security Considerations
### If I get a JWT and I can decode the payload, how can we call that secure?
If you can decode the payload of a JWT, it means that the information within the token is readable. However, the security of the JWT lies in the verification of the signature. Only by verifying the signature using the shared secret or public key can you ensure that the token has not been tampered with and originated from a trusted source.

### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
The sender and receiver both need to know the shared secret or private key used for signing the JWT. This shared secret is appended to the signature during the token creation process. It is essential for the receiver to possess the same secret in order to verify the signature and validate the authenticity of the token.

### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
To securely send and receive the concatenated content and secret to a non-technical recruiter, encryption and secure communication channels can be employed. Encryption techniques can be used to protect the shared secret during transmission, ensuring that it remains confidential and cannot be intercepted by unauthorized parties. Secure communication channels, such as encrypted email or secure file transfer protocols, can be utilized to transmit the information securely.

## Usage and Benefits
### Why use JWT?
JWTs offer several advantages, making them a popular choice for authentication and authorization:
- Compactness and self-contained nature: JWTs are compact, allowing them to be easily transmitted over networks. They contain all the necessary information within the token itself, reducing the need for frequent database queries.
- Statelessness: JWTs are stateless, meaning the server does not need to store session information. This makes them scalable and suitable for distributed systems.
- Easy integration: JWTs can be easily integrated into various platforms and frameworks due to their standardized format and widespread support.

### What are the three components (the structure) of a JWT signature?
The JWT signature consists of three components:
1. Header: Contains the algorithm used for signing the token and the token type.
2. Payload: Contains the claims or information being transmitted.
3. Signature: A hash created by combining the encoded header, encoded payload, and a secret key. It ensures the integrity and authenticity of the token.

