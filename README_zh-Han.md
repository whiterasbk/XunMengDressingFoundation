# XunMengDressingFoundation(尋夢女裝基金會開源項目)

 [简体中文](https://github.com/whiterasbk/XunMengDressingFoundation/blob/master/README.md) | 繁體中文 | [English](https://github.com/whiterasbk/XunMengDressingFoundation/blob/master/README_en-us.md) | [日本語](https://github.com/whiterasbk/XunMengDressingFoundation/blob/master/README_ja.md) | [Рускии](https://github.com/whiterasbk/XunMengDressingFoundation/blob/master/README_ru.md)

定理 1: 
> 女裝只有零次和無數次
> 
> 穿藍白胖次的感覺真的很棒誒！
> 
> ---------------- 匿名用戶

對 `定理 1` 進行證明: 
首先, 假設一個可愛藍孩紙從 `15` 歲開始接觸女裝, 隨著年齡的增長, 往後穿女裝的時間 `dress_t` 和 穿正裝的時間 `undress_t` 之比 成正相關, 相關繫數為 k, 問到多少歲時不穿正裝?

證: 

> 可以用數學來解決這個問題, 假設藍孩紙從 15 歲開始到某個歲數 x 時不再穿正裝, 那麽在這個過程中: 
>
> dress_t + undress_t 應該等於他的年齡 x 減去 15
>
> 讓 dress_t 成為 f(x), undress_t 為 m(x), 則有 f(x) + m(x) = x - 15
> 
> 又依題 f(x) = k * m(x)
>
> 將這個關繫帶入前面的等式: k * m(x) + m(x) = x - 15  化簡: m(x) * (k + 1) = x - 15
> 
> 解出正裝時間 m(x)： m(x) = (x - 15) / (k + 1)
>
> 所以, 藍孩子不穿正裝的年齡 x 應為: x = (k + 15) / k
>
> 我們的目標是求解 正裝時間 m(x) 為 0 的時候, x 等於多少 即是 (x - 15) / (k + 1) = 0
>
> 這意味著 x - 15 = 0, 因為分母不可能為0, 所以我們解出 x = 15
>
> 因此, 正確的結論是, 在藍孩紙十五歲就不穿正裝, 與相關繫數 k 的大小無關
>
> 所以 這時候藍孩紙只能穿女裝, 原定理得證
> 
> ---------------- 查特 · 吉皮屜

這會帶來什麽問題? 對, 女裝也是需要錢買的, 但因為 `定理 1` 的存在, 會導致藍孩紙對女裝不可自拔, 這太可憐了!

這個項目的 目的就是籌集網際網路的力量, 幫助這些可憐的藍孩紙

## 可以做什麽

#### 協助翻譯

我們需要來自不同國家的力量, 將這份文檔翻譯成不同的文字, 讓我們的聲音被更多的人聽到

#### 完善文檔

如果妳有任何想法請幫助我們! 使用更好的措辭, 更有聲音的文字

## 起源

成立於2019年5月15日，意在幫助那些想要女裝而有沒有錢買女裝的男孩紙(比如尋夢就是一個活生生的例子)

## 也看看

[源repo遺跡](https://github.com/komeiji-satori/Dress)

[archive-dress-master](https://archive.org/details/dress-master.-7z)

[Misaka-0x447f/Dress](https://github.com/Misaka-0x447f/Dress)

## 吟詩作對

```dressing-up-language
  尋常仙子侶
  夢擁白雲邊
  女曲琵琶裏
  裝成錦繡前
```
