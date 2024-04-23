# MNG-8104

Start mitmproxy in one window:
https://mitmproxy.org/

Then run:
```
$ mvn -Dmaven.repo.local=local -s settings.xml clean package -Daether.connector.https.securityMode=insecure
```
