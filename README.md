# Zarf package for Kasmweb's Kali Linux container

## Deploy zarf-kali
```
zarf init
zarf package deploy zarf-package-zarf-kali-amd64.tar.zst
```

## Get pod name
```
kubectl -n zarf-kali get pods
```

## Set up port forwarding and connect

Note: you may need to change `http` to `https` on older Zarf versions

```
zarf connect kali
```

## Login
Login with username: `kasm_user` password: `changeme`

