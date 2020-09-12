## Authentication Bypass

* Do Intercept to get Response of Request

- In Response change this. It will break the application. 

    - success => flase -> true

    - error -> success.

    - Check 0000 or 123456 for default OTP. (Logic Flow)

    - Instead of OTP digits give Text like (0000 -> OTPBYPASSLIKEAPRO) in Request. After that give 1 or true if no response body available.