# HTTPで使われる80番ポートを使用するパケットのみ
>tshark -i イーサネット -w ./capture -f "port 80"  
>tshark -r ./capture -Y http

# ネットワークインターフェイス調査方法
>netsh interface ip show interface

# 参考
https://knowledge.sakura.ad.jp/6311/
