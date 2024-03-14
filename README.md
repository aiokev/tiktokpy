# TikTok

An Asynchronous API Wrapper for TikTok that requires no authentication keys

## Example

```py
from tiktok import TikTok as tt
tiktok = await tt.get_data(self = self, url = url)
video = await tiktok.get_video_binary(self = self)
```
