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
```
## Example Output
```
DATE = 2021-06-01 20:37:56 CEST;
IP = 197.x.x.x;
X_FOR = 127.0.0.1;
REFERRER = Mozilla/5.0 (PlayStation 5 3.03/SmartTV) AppleWebKit/605.1.15 (KHTML, like Gecko);
AGENT = Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:88.0) Gecko/20100101 Firefox/88.0;
POST = username=test&password=fake&submit=true;
GET = show=true&message=success;;
COOKIE = PHPSESSID=a2re0o2fgqn7n8qe2cqpo20otp;

```

## Disclaimer
The following script should be used for **educational purposes only** since logging of `POST` data and `SESSIONS`  may lead to a violation of privacy.
