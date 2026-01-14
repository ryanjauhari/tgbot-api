# TGBot Server
Digunakan untuk membuat sendiri server khusus berkomunikasi dengan server telegram secara lokal di bandingkan menggunakan api.telegram.org karena latency nya 800Ms dari indonesia di jakarta. Dengan ini koneksi bisa di pangkas menjadi sekitar 5ms.

## Table of Contents
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Documentation](#documentation)
- [Moving a bot to a local server](#switching)
- [Moving a bot from one local server to another](#moving)
- [License](#license)

<a name="cara install"></a>
## Cara Install
Simple, pergi ke bagian relases untuk cara install dan kamu akan dapat versi buid untuk Ubuntu 22.4 dengan arsitektur AMD64 atau ARM64
Atau compile sendiri di sini :

```sh
git clone --recursive https://github.com/ryanjauhari/tgbot-api.git
cd telegram-bot-api
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build . --target install
```
