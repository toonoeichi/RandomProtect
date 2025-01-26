<center>
<q>Have you ever have problem someone trying to access your site</q>

<span>via your public ip? or maybe your forward dynamic dns?</span>
</center>

<h1 align=center>RandomProtect</h1>
<p align=center>Simple and (yet) funny way to protect site scraping.</p>

<hr>

Build from ground up , (meme) and simple HTML and some JavaScript to spice thing up. This (not) groundbreaking technology that we called

```javascript
window.location.href = https://www.youtube.com/watch?v=dQw4w9WgXcQ;
```
<center>
<q><b>Redirect people straight to Rickroll!</b></q>
<p>used for protect other to access anything else except what supposed to!</p>
</center>

> [!NOTE]
> **Still recommended to use Cloudflare Proxy at all cost and only Open the Port that needed!** Since this doesn't help with DDoS Attack, Port Scanning, DNS Dumpster and anything , **only to protect someone typing the address on the browser or (some) bot scraping your IP to do some nasty piece of s-**

But instead only rickroll, we put another meme (or maybe anime song) link on Youtube and random it everyone they tried to visit!
<hr>

# How to use!

You can either
- Config your reverse proxy to use this url as default page.
```
rp.aoeyoei.xyz
```
- Self-hosted on your server and point default to there.
- Deploy on Github , Vercel , or other as your choice, and point your server , reverse proxy to it.

and so much more...

<br>

and you can try it by visiting [rp.aoeyoei.xyz](rp.aoeyoei.xyz)!

<hr>

# Lists on Links
#### Last update on 26th January 2025

| Category | Name | Location | Description |
| -------- | ---- | ------ | ----------- |
| Default | Default | [url/default.json](url/default.json) | Default Link that play on everyday.
| Day | New Year Day | [url/day/new-year.json](url/day/new-year.json) | New Year Song (Only appear only on January 1st.)
| Anime (Ensemble Stars) | Fine's Song | [url/anime/enstar/fine.json](url/anime/enstar/fine.json) | Song from fine, a Unit from Starmaker Production from Ensemble Stars (Have Chance 1 from 10 on everyday.)

## To Do List

| Category | Name | Description |
| -------- | ---- | ----------- |
| Day | Valentine Day | Love Song for Lover on Valentine Day [Even through I still single T^T] (Only appear only on Feburary 14th.)
| Anime (Ensemble Stars) | Eichi's Birthday | Song sing (mainly) by Eichi Tenshouin. (Appeared on his birthday. [10th January]) &#124; This one will disabled all the Ensemble Star Song to be included on the list for that day.

## Want to be next?

You can fork this repo and add many song as you like.

```
Song Dir : url\[category]\[name].json
```

Recommended only song, <b>I may declined your pull if you put video instead of song.</b> Also you can added new Category if you want. <b> but not removing other people (or my) song from the repo. </b> This is example of the json file
```
{
    "sites": [
        "https://www.youtube.com/watch?v=dQw4w9WgXcQ",
        "https://www.youtube.com/watch?v=yPYZpwSpKmA",
        "https://www.youtube.com/watch?v=H9891PGJl6Y"
    ]
}
```

### Also, Don't forget to update the list (if you add new Category or List.) Like

| Category | Name | Location | Description |
| -------- | ---- | ------ | ----------- |
| Artist | Rick Ashley | url/artist/rickroll.json | Song sing by Rick Ashley.

```markdown
| Category | Name | Location | Description |
| -------- | ---- | ------ | ----------- |
| Artist | Rick Ashley | [url/artist/rickroll.json](url/artist/rickroll.json) | Song sing by Rick Ashley.
```
---
# To Do

- Add more statement and rate of the song to appeared on the list
- (maybe) move to Svelte for smooth redirect.

---
#### Made with ❤️ and 🍻 By Cartoon Kritthapath Yaviraj (ToonOeichi) <3 UwU | 1.0.0.012625