# ๐ ์ฑ์ด foreground์ ์์ ๋์ background์ ์์ ๋ ์ด๋ค ์ ์ฝ์ฌํญ์ด ์๋์?



### foreground (active, inactive)

- ์ฌ์ฉ์๊ฐ ์ฑ์ ๋ณด๊ณ  ์๋ ์ํฉ. ์์คํ ์์์ ์ฐ์  ์์๊ฐ ๋์ ์ํฉ



### background

- ์ฑ์ด ์ฌ์ฉ์ํํ ๋ณด์ด์ง ์๋ ์ํ๋ฅผ ์๋ฏธ
- ์ฌ์ฉ์์๊ฒ ๋ณด์ด์ง๋ ์์ง๋ง ๊ณ์ ์คํ๋  ์ ์์ ex) ์์ ์ดํ, ๋ค๋น๊ฒ์ด์ ์ดํ

#### ์ ์ฝ์ฌํญ

- ์ ์ ๋ฉ๋ชจ๋ฆฌ ๊ณต๊ฐ์ ์ฌ์ฉํด์ผ ํจ
- ๋ ๋ฎ์ ์์ ํ ๋น ์ฐ์  ์์
- ํ์์ ๋ฐ๋ผ ๋ฐฑ๊ทธ๋ผ์ด๋ ์ฑ ์ข๋ฃ ์ํด
- ์ฌ์ฉ์ ์ด๋ฒคํธ ๋ฐ๊ธฐ ์ด๋ ค์

#### ์ถ๊ฐ ์๊ฐ ๋ถ์ฌ

Location Service, ์ธ๋ถ ์์ธ์๋ฆฌ์ ํต์  (apple watch, homepods), ๋ธ๋ฃจํฌ์ค๋ฅผ ์ด์ฉํ ์์ธ์๋ฆฌ ์ฌ์ฉ, ์ฑ ์๋ฐ์ดํธ ์งํ, ํธ์ ์๋ฆผ



### ์ฑ์ ์ํ

1. Not running

   ์ฑ์ด ์คํ๋์ง ์์๊ฑฐ๋, ์์คํ์ ์ํด ์ข๋ฃ

2. Inactive

   Foreground ์ํ์ง๋ง, ์ด๋ฒคํธ ๋ฐ์ง ๋ชปํจ

3. Active

   foreground ์ํ์ด๋ฉฐ ์ด๋ฒคํธ๋ฅผ ๋ฐ์

4. Background

   ์ฑ์ด background์ ์์ผ๋ฉฐ ์ฝ๋๋ฅผ ์คํํ๊ณ  ์์

5. Suspended

   background์ด๋ฉฐ, ๋ฉ๋ชจ๋ฆฌ์๋ ๋จ์์์ผ๋ ์ฝ๋๋ฅผ ์คํํ๊ณ  ์์ง ์์

๊ฐ ์ํ์ ๋ฉ์๋ ์์์ ๊ตฌํํ๊ณ  ์ถ์ ๊ธฐ๋ฅ์ AppDelegate.swift์์ ๊ตฌํํ  ์ ์์