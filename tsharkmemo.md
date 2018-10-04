# HTTPで使われる80番ポートを使用するパケットのみ
>tshark -i イーサネット -w ./capture -f "port 80"
>tshark -r ./capture -Y http

# 参考
https://knowledge.sakura.ad.jp/6311/
