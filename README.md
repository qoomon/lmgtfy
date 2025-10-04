# lmgtfy
[Let me google that for you!](https://lmgtfy.qoo.monster/)


## Download Google homepage
```shell
wget \
    -erobots=off \
    --no-parent \
    --user-agent "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/140.0.0.0 Safari/537.36" \
    --convert-links \
    --adjust-extension \
    --page-requisites \
    --accept html,css,js,png,webp \
    'https://www.google.com/?gl=us'
```