# GitHub Profile Views Counter

![GitHub Profile Views Counter](https://raw.githubusercontent.com/BlueOrbitDevs/GitHub-Profile-Views-Counter/refs/heads/main/img/GitHub-Profile-Views-Counter.png)

<p align="center">
<a href="#"><img src="https://img.shields.io/static/v1?logo=discord&label=&message=Discord&color=36393f&style=flat-square" alt="Discord"></a>
<a href="https://github.com/BlueOrbitDevs/GitHub-Profile-Views-Counter/blob/main/LICENSE"><img src="https://img.shields.io/github/license/antonkomarev/github-profile-views-counter.svg?style=flat-square" alt="License"></a>
</p>

## Introduction

This project is a lightweight **GitHub Profile Views Counter**.

It is designed as an analytical instrument to track profile view activity from GitHub profile pages.
It is not meant to measure unique visitors, but total profile hits.

It counts how many times your GitHub profile has been viewed and displays them in your profile — **for free**.

![BlueOrbitDevs-profile-views-counter](https://raw.githubusercontent.com/BlueOrbitDevs/GitHub-Profile-Views-Counter/refs/heads/main/img/BlueOrbitDevs-profile-views-counter.png)

## Usage

### Create GitHub profile repository

GitHub magic will happen as soon as you create a new repository named **exactly** the same as your username.

![secret-profile-repository](https://raw.githubusercontent.com/BlueOrbitDevs/GitHub-Profile-Views-Counter/refs/heads/main/img/Create%20Repository.png)

### Add counter to GitHub profile

Add this line inside your profile repository `README.md`:

```markdown
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username)
````

> [!NOTE]
> Replace `your-github-username` with your real GitHub username.

---

## Make it personal

### Color

You can use any valid HEX color or one of the predefined names:

| color         | demo                                                                                  |
| ------------- | ------------------------------------------------------------------------------------- |
| `brightgreen` | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo1&color=brightgreen) |
| `green`       | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo2&color=green)       |
| `yellow`      | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo3&color=yellow)      |
| `yellowgreen` | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo4&color=yellowgreen) |
| `orange`      | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo5&color=orange)      |
| `red`         | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo6&color=red)         |
| `blue`        | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo7&color=blue)        |
| `grey`        | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo8&color=grey)        |
| `lightgrey`   | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo9&color=lightgrey)   |
| `blueviolet`  | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo10&color=blueviolet)  |
| `ff69b4`      | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo11&color=ff69b4)      |

**Named color**

```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&color=green)
```

**Hex color**

```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&color=dc143c)
```

---

### Styles

| style           | demo                                                                                    |
| --------------- | --------------------------------------------------------------------------------------- |
| `flat`          | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo12&style=flat)          |
| `flat-square`   | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo13&style=flat-square)   |
| `plastic`       | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo14&style=plastic)       |
| `for-the-badge` | ![](https://profileviews.blueorbitdevs.workers.dev/?username=demo15&style=for-the-badge) |
| `pixel`         | Invisible counter (1×1 pixel, no badge shown)                                           |

```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&style=flat-square)
```

---

### Label

```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&label=PROFILE+VIEWS)
```

> [!NOTE]
>
> Replace whitespace with `+` character in multi-word labels.

---

### Base number

You can provide a `base` number to add to the counter.
This is useful if you are migrating from another service.

For example, a user with 1000 views on another service who wants to migrate to GHPVC will use the following url
to ensure the 1000 views are accounted for:
```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&base=1000)
```

---

### Abbreviation

```md
![](https://profileviews.blueorbitdevs.workers.dev/?username=your-github-username&abbreviated=true)
```

---

## FAQ

### Can I see detailed statistics?

No. This project provides a **minimalistic counter only**.

### How to reset counter?

This service does **not provide a public reset option**.
The counter is persistent. Only the service owner can reset values directly in the database.

### Why does the counter increase on every reload?

This counts **page hits**, not unique users.
GitHub proxies all image requests through GitHub Camo, so visitor identity cannot be detected.

### Are you making money on it?

No. This is a free utility project.

---

## License

MIT

---

**Service powered by BlueOrbit Devs 💙**
[https://profileviews.blueorbitdevs.workers.dev](https://profileviews.blueorbitdevs.workers.dev)
