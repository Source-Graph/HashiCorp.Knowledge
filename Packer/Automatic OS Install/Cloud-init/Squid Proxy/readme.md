# example:
https://ubuntu.com/server/docs/install/autoinstall
```
version: 1
reporting:
    hook:
        type: webhook
        endpoint: http://example.com/endpoint/path
early-commands:
    - ping -c1 198.162.1.1
network:
...
proxy: http://squid.internal:3128/
```

# Doc:
https://ubuntu.com/server/docs/install/autoinstall-reference
>proxy
>type: URL or null
>default: no proxy
>can be interactive: yes
>
>The proxy to configure both during installation and for apt and for snapd in the target system.

