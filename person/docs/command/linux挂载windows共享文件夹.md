
```shell
mount.cifs //172.16.2.27/mkdocs blog/ -o user=phy,pass=KVM.123456
```

失败尝试添加选项再试：

```shell
mount.cifs //172.16.2.27/mkdocs blog/ -o user=phy,pass=KVM.123456,sec=ntlm
```

