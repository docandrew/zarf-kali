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

## Set up port forwarding
```
kubectl -n zarf-kali port-forward <name-of-kali-pod> 6901:6901
```

## Log into app
* Go to https://localhost:6901/
* Login with username: `kasm_user` password: `changeme`

