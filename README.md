# Cloudflare Workers Blog
[![LICENSE](https://img.shields.io/badge/license-Buildtest-blue.svg?style=flat-square)](https://github.com/LittleRey/Worker-Blog/edit/master/LICENSE.md)

# Use
Paste workers.js into the Cloudflare worker panel
# How to write an article

First create a Github project with a random name and then clone the project locally.

```
# Example
Git clone https://github.com/kasuganosoras/cloudflare-worker-blog
Cd cloudflare-worker-blog/
```

Go to the project folder and create a new post folder

```
Mkdir posts/
```

Write an article inside, the content is generally suffixed with .md, for example helloworld.md

After writing, go back to the project root directory (that is, the parent directory), and then create a new list.json
# List format
```json
[
  {
    "title":"name1",
    "time":"2019-06-01",
    "file":"posts/1.md"
  },
  {
    "title":"name2",
    "time":"2019-06-03",
    "file":"posts/2.md"
  },
  {
    "title":"name3",
    "time":"2019-06-07",
    "file":"posts/3.md"
  } <-- # There is no comma here #
]
```

