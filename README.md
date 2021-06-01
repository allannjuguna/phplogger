# PhpLogger
This is a simple logger built in php<br>
The logger is capable of logging the following:
```
- Date
- User-Agent
- IP address
- X-Forwarded-For
- POST Data
- GET Requests
- Cookies/Sessions
- Referrer

```
## Example Output
```
DATE = 2021-06-01 20:37:56 CEST;
IP = 197.x.x.x;
X_FOR = 127.0.0.1;
REFERRER = https://localhost/phplogger/;
AGENT = Mozilla/5.0 (PlayStation 5 3.03/SmartTV) AppleWebKit/605.1.15 (KHTML, like Gecko);
POST = username=test&password=fake&submit=true;
GET = show=true&message=success;;
COOKIE = PHPSESSID=a2re0o2fgqn7n8qe2cqpo20otp;

```

## Disclaimer
The following script should be used for **educational purposes only** since logging of `POST` data and `SESSIONS`  may lead to a violation of privacy.
