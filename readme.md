<h1 align="center">
	<img width="750" src="https://nikolaskama.me/content/images/2018/02/cf-detect.png" alt="Cloudflare-Detect.Now">
</h1>

<p align="center">A minimal service to check whether a site is running behind cloudflare.</p>

---

<p align="center">
	<sub>Visit <a href="https://cf-detect.now.sh"><code>cf-detect.now.sh</code></a> for a live demo. Check out my <a href="https://nikolaskama.me">blog</a> and follow me on <a href="https://twitter.com/nikolaskama">Twitter</a>.</sub>
</p>


<br>

# Installation & Configuration

Clone the repository and install all dependencies by running:

```
~ ❯❯❯ git clone https://github.com/k4m4/cf-detect.now
~ ❯❯❯ cd cf-detect.now/
~/cf-detect.now ❯❯❯ npm install
```

Subsequently, create a `.env` file and declare a variable called `SECRET` (for session security purposes):

```
~/cf-detect ❯❯❯ echo "SECRET=[your-secret-goes-here]" > .env
~/cf-detect ❯❯❯ npm start
```

You can then access the service by navigating to [`localhost:3000`](http://localhost:3000/).


<br>

# Deployment

First, [download `now`](https://zeit.co/download):

```
~ ❯❯❯ npm install -g now
```

Then, run `now` from *within* the directory of `CF-Detect.Now`:

```
~/cf-detect.now ❯❯❯ now
```


<br>

# Credits
- CF-Detect.Now was developed as part of my Node.js learning experience. I have uploaded the code with the intention of helping out others who are also trying to learn the node environment.
- Most of the styling was adapted from [Evil Rabbit](https://twitter.com/evilrabbit_)'s [front site](https://github.com/evilrabbit/front).
- Cloudflare's logo was taken from [seeklogo.com](https://seeklogo.com/vector-logo/294312/cloudflare).


<br>

# Related

- [cloudflare-detect](https://github.com/k4m4/cloudflare-detect) - Detect whether a site is running behind Cloudflare.


<br>

# License

Copyright (c) 2018 by Nikolaos Kamarinakis. Some rights reserved.

`CF-Detect.Now` is under the terms of the **MIT License**, following all clarifications stated in the [license file](license.md).

For more information on this project you can go ahead and email me anytime at **nikolaskam{at}gmail{dot}com**.