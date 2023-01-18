# Zarf package for Kasmweb's Kali Linux container

## Deploy zarf-kali
```
zarf init
zarf package deploy zarf-package-zarf-kali-amd64.tar.zst
zarf connect kali
```
Note: you may need to change `http` to `https` on older Zarf versions

## Login
Login with username: `kasm_user` password: `changeme`

