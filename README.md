# create-gmud

### This is action create a servicedesk basead in a issue

```yml
create-gmud:
    runs-on: ubuntu-latest
    name: 'create-gmud'
    steps:
      - uses: archaic10/create-gmud@v2
        with: 
          domain: <domain>
          basic-auth: <basic-auth>
          api-key: <api-key>
          auth-github: <auth-github>
          service-desk-id: <service-desk-id>
          request-type-id: <request-type-id>
          service: <service>
          tecnical-approval: <tecnical-approval>
          business-approval: <business-approval>
          url-pull-request: <url-pull-request>
          url-slifer-gmud: <url-slifer-gmud>
```
