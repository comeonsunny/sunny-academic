<!-- ---
title: Jump-ORAM
summary: An ORAM scheme achieves constant bandwidth blowup without server-side computation overhead.
tags:
  - Jump_ORAM
date: '2020-08-29T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Follow
    url: https://github.com/comeonsunny/Jump_ORAM
url_code: 'https://github.com/comeonsunny/Jump_ORAM'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Jump-ORAM 
The implementation of Jump-ORAM, the paper of which was submitted to INFOCOM. 
We programmed this project on [VS code](https://code.visualstudio.com/) and  ran it on Ubuntu20.04 with g++ as compiler. 
It is recommended to use the editor and running environment mentioned above. 

# Required Libraries
[libtomcrypt](https://github.com/libtom/libtomcrypt)

# Configuration
All Jump-ORAM configurations are located in ```Jump_ORAM/src/config.h```. 

## Highlighted Parameters:
```
#define BLOCK_SIZE 4-1024                                -> Block size (in KB)

#define DATABASE_SIZE 0.5-40                             -> Database size (in GB)

#define STASH_SIZE  2                                    -> Stash size

#define CACHE_SIZE  2                                    -> Data Cache size

const std::string SERVER_ADDR[NUM_SERVERS]               -> Server IP addresses
#define SERVER_PORT 5210                                 -> Define the port for client-server communications

```
# Build & Compile
Goto folder ``Jump_ORAM/`` and execute
``` 
mkdir build
cd build
cmake .. 
make
```

, which produces the binary executable file named ```Jump_ORAM``` in ``Jump_ORAM/build/``.
 -->
