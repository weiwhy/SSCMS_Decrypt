# sscms database decrypt

## Des Decrypt

```
 python3 sscms_decrypt.py
 
[+] Current Encrypt Data= 0NofLD4zWcY/jm+42NYzug==
[+] secretKey= f9c01027
[+] iv_hex= 1234567890abcdef
[+] 数据库类型：SqlServer

[+] Current Encrypt Data= B0SvIg6ExtjhllXf3vb9UwjmLKSRMlqQ1LIs6a8G0G/M1cWZ2ABJ6lvZOMlvKR+vM7/QKGc8pYo8t6sumMerqA==
[+] secretKey= f9c01027
[+] iv_hex= 1234567890abcdef
[+] 数据库配置信息：Server=192.168.77.200;Uid=sa;Pwd=p@ssw0rd2020;Database=sscms;
```

## sscms.json

```
{
  "IsNightlyUpdate": false,
  "IsProtectData": true,
  "AdminDirectory": "siteserver",
  "HomeDirectory": "home",
  "SecurityKey": "f9c01027278a387b",
  "Database": {
    "Type": "0NofLD4zWcY0slash0jm0add042NYzug0equals00equals00secret0",
    "ConnectionString": "B0SvIg6ExtjhllXf3vb9UwjmLKSRMlqQ1LIs6a8G0G0slash0M1cWZ2ABJ6lvZOMlvKR0add0vM70slash0QKGc8pYo8t6sumMerqA0equals00equals00secret0"
  },
  "Redis": {
    "ConnectionString": ""
  }
}
```
