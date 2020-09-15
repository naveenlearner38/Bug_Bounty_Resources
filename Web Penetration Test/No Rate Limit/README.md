
## No Rate Limit

- If server does accept N Requests without interuption, that is No Rate Limit

* Do Intercept to get Response of Request ( Use Intruder in Burpsuite )

## Attacking - Burpsuite

- Use Intruder and set position, add payload and start attack. If delay needed, use throttle ( 5000 ms = 5s)

- Set Throttle to Server Don't think for DDos Attack.

## Account Take Over (OTP Bypass) - Bruteforce

- Send the request to Intruder -> Payload Type(Numbers) -> Give Grep match in Options for wrong OTP (Optional) -> Attack -> Copy Right Response -> Paste instead of Wrong OTP Response 