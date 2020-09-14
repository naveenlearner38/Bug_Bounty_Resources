## Broken Authentication

- Response manipulation
- Bruteforce
- Session Flaw
- No Rate-limting

## Authentication Bypass

* Do Intercept to get Response of Request

## OTP Bypass & Captcha Bypass

- Checking and modifiying Request and Response in Client Side (Using Burpsuite)

- In Response change this. It will break the application. 

    - success => flase -> true

    - error -> success.

    - Check 0000 or 123456 for default OTP. (Logic Flow)

    - Instead of OTP digits give Text like (0000 -> OTPBYPASSLIKEAPRO) in Request. After that give 1 or true if no response body available.

    - If there is any number like (0 - 9) change that to another number (1 - 9) mostly 1. Then may site break

## Account Take Over

- Account Takeover Based on User Id like ( uid, gid, other params like user_id, user=, etc) 

    - Change User Id in Response (In Local storage or Burpsuite Response)

- OTP will be get as Response itself sometime.

## Mitigations

- Don't check only in client side, check server side also

- Authentication with strong tokens like (JWT Tokens)

- Encrypt auth data