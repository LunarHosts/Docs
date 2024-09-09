# 子網域 DNS

## 登入網頁控制面板

前往 [https://web-control.lunarhosts.net:2222/evo](https://web-control.lunarhosts.net:2222/evo) 登入帳號。

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

### 從 **`Account Manager`** 類別裡面點選 `子網域管理`

<figure><img src="../../.gitbook/assets/WEB-Sub設定.png" alt=""><figcaption></figcaption></figure>

點選新增 **`子網域`**。

<figure><img src="../../.gitbook/assets/WEB-Sub設定-2.png" alt=""><figcaption></figcaption></figure>

輸入想要的名稱，再來選擇資料夾創建類型，最後按下儲存。

<figure><img src="../../.gitbook/assets/WEB-Sub設定-3.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
創建好後可以回到 DNS 管理去做查看，確認剛創的子網域有在 DNS 紀錄上，就可以接續下一步。
{% endhint %}

## 前往 Cloudflare 控制面板

前往 [https://dash.cloudflare.com/](https://dash.cloudflare.com/) 登入並選擇自己的網域。

<figure><img src="../../.gitbook/assets/WEB-CF設定.png" alt=""><figcaption></figcaption></figure>

### 新增 DNS 紀錄

點選 DNS 紀錄。

<figure><img src="../../.gitbook/assets/WEB-CF設定2.png" alt=""><figcaption></figcaption></figure>

點選新增紀錄，範例格式如下。

<figure><img src="../../.gitbook/assets/WEB-CF子網設定.png" alt=""><figcaption></figcaption></figure>

範例格式：

| Type |    Name   |     IPv4     | Proxy |
| :--: | :-------: | :----------: | :---: |
|   A  | subdomain | 160.30.99.68 |   開啟  |

{% hint style="warning" %}
注意！Name 的 @ 代表主網域，如果要手打主網域也是可行的。Proxy 一定要開啟。
{% endhint %}

新增結束後去瀏覽自己的網域，正常情況下會顯示下方圖片同樣的畫面。

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

這樣就完成了，開始建立自己的網站吧！！
