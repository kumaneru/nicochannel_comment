# nicochannel_comment

nicochannel.jp comment(s) downloader. 
适用于同款网站（理论上）
基于旧版脚本修改，避免日本人的光线污染。

## Usage/利用方法:

```
usage: nicochannel_comment.py [-h] [-v] [-o OUTPUT] [--allow-broken-timestamp] [nico_url]

nicochannel.jp comment(s) downloader.

positional arguments:
  nico_url              Video URL or Channel URL.

options:
  -h, --help            show this help message and exit
  -v, --verbose         Verbose log output
  -o OUTPUT, --output OUTPUT
                        Output directory / filename.
  --allow-broken-timestamp
                        Save comments that may have broken timestamps. It is recommended to add this option for videos       
                        longer than 8 hours.
```  
