# OAuth2.0

OAuth 2.0 (OAuth2) is an open standard authorization framework that allows third-party applications to access user data without needing to know their credentials. Instead of sharing usernames and passwords, OAuth2 provides a secure, token-based mechanism for delegated access to resources hosted on another service, such as Google, Facebook, or GitHub.

## Simplified Explanation:
When logging into website there is option to choose sign In with google , sign in with facebook etc.

### Implementation
- Implemented SecurityConfiguration Class which Disables CSRF protection & Requires authentication for every request to the app. Enables OAuth2 login to allow users to authenticate using third-party providers like Google or GitHub. In this repository created with only Github.

- Added properties in application.yml files.
