# alpine-glibc-packages

## Sample command in Dockerfile
```
curl -fL https://raw.githubusercontent.com/orctom/alpine-glibc-packages/master/usr/lib/libstdc++.so.6.0.21 -o /usr/lib/libstdc++.so.6.0.21
```

## Packages
| package                 | required by           | usage                                        |
| ----------------------- | --------------------- | -------------------------------------------- |
| libstdc++.so.6.0.21     | nodejs,kibana         | ln -s /usr/lib/libstdc++.so.6.0.21 /usr/lib/libstdc++.so.6.new; mv /usr/lib/libstdc++.so.6.new /usr/lib/libstdc++.so.6 |
