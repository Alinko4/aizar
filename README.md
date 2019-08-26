# #!/ AizarSender 📧 ~ ChangeLog 📝
### @v0.1 - 13 August 2019 🕕
> first release
### @v0.2 - 23 August 2019 🕕
#### fixed bug 🐞
* error if using the `{` or `}` symbol in `header.txt`
* error if using non-Latin characters in `config.ini`
* incorrect `from mail` format if using `non-Latin` characters in `config.ini`
* fixed `random tags` that didn't work in some `html syntax` > [goGJPMa.png](https://i.imgur.com/goGJPMa.png)
* fixed some `random tags` that didn't work due to conflicts with the `os module` and also replace it with the `pathlib module` > [SnJg1h4.png](https://i.imgur.com/SnJg1h4.png)
* fixed `random tags` that didn't work if you use different lengths in each tag > [Up45PA8.png](https://i.imgur.com/Up45PA8.png)
* fixed `incorrect time format` > [EWFtZmb.png](https://i.imgur.com/EWFtZmb.png)
#### added features ➕
* adding `multiple attachment` support > [QvUILOx.png](https://i.imgur.com/QvUILOx.png)
* adding `custom attachment name` support > [SSPsFj8.png](https://i.imgur.com/SSPsFj8.png)
* adding `custom random tag` > [CTWL68X.png](https://i.imgur.com/CTWL68X.png)
* adding `new ##random_md5## tag` > [Ecl0tMk.png](https://i.imgur.com/Ecl0tMk.png)
* adding `pre-installed modules` to the `AizarSender`, so there is no need to install the required modules > [edcku0U.png](https://i.imgur.com/edcku0U.png)
* adding `more failed log` > [nRphevh.png](https://i.imgur.com/nRphevh.png)
* adding `time elapsed` > [zVInciZ.png](https://i.imgur.com/zVInciZ.png)
#### updated features ⚙
* updating the `mime structure` > [FmXH7sL.png](https://i.imgur.com/FmXH7sL.png), [mime-nesting-structure](https://i.imgur.com/5Wm1Z7a.png)
* updating the `random tag generator` method (more efficient and faster)
* updating and add several `date format` variations > [DQvBrQW.png](https://i.imgur.com/DQvBrQW.png)
* updating and add several `domain providers` to `##random_email##` tag
### @v0.3 - 25 August 2019 🕕
#### fixed bug 🐞
* error if using blank `from mail`
* error if using `custom hostname`, because cant use `custom from mail`
#### added features ➕
* adding `use to` (how many `'to address'` do you want to `use` when sending `email`?) & `switch to` (switching `'to address'` when `reaching` how many `email`?) while using `To + Bcc method` > [RJXC82w.png](https://i.imgur.com/RJXC82w.png)
* adding `automatically` change `from email` (if you use a `custom hostname`) to `current SMTP User` when sending
#### updated features ⚙
* updating the `mime structure` > [pfyRIa6.png](https://i.imgur.com/pfyRIa6.png), [mime-nesting-structure](https://i.imgur.com/5Wm1Z7a.png)
* updating `To Address` & change as a file (`to.txt`) so you can add bulk `To Address` while using `To + Bcc method` > [VtuUSWO.png](https://i.imgur.com/VtuUSWO.png)
* updating `X-Priority` format > [pPSPNGE.png](https://i.imgur.com/pPSPNGE.png)
