## کلمه‌بازی (۵۰ امتیاز)

یک رشته `reshte` و یک الگو `p` به شما داده می‌شود. پیدا کنید که آیا این رشته از الگوی مدنظر پیروی می کند یا نه.
<br/>
زمانی می‌گوییم یک رشته از یک الگو پیروی می‌کند که تناظری یک به یک بین هر حرف از الگو با یک کلمه غیرخالی از رشته وجود داشته باشد.

<br/>
<br/>

### مثال ها

نمونه اول:

```
Input:
    p = "xyyx"
    reshte = "ali amin amin ali"

Output:
    true
```

نمونه دوم:

```
Input:
    p = "xyyx"
    reshte = "ali amin amin mohammad"

Output:
    false
```

نمونه سوم:

```
Input:
    p = "dddd"
    reshte = "ali amin amin ali"

Output:
    false
```

نمونه چهارم:

```
Input:
    p = "abba"
    reshte = "amin amin amin amin"

Output:
    false
```

<br/>
<br/>

### محدودیت ها:

<div dir="rtl" >
<li><span dir="ltr">
1 <= p.length <= 300
</span>
</li>
<li><span dir="ltr">
1 <= reshte.length <= 3000 </span>
</li>
<li>
الگو فقط از حروف کوچک انگلیسی تشکیل شده است.
رشته فقط از حروف کوچک انگلیسی و فاصله(space) تشکیل شده است.
</li>
<li>
اول و آخر رشته هیچگونه فاصله‌ای وجود ندارد.
تمام کلمات داخل رشته با دقیقا یک فاصله از هم جدا شده‌اند.
</li>
</div>
