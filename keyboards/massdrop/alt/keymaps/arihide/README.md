`make massdrop/alt:arihide`

を実行すると、

`.build/massdrop_alt_arihide.hex`

ができるので、このファイルを[mdloader](https://github.com/Massdrop/mdloader)を用いてインストールする

`./mdloader_mac --first --download .build/massdrop_alt_arihide.hex --restart`
