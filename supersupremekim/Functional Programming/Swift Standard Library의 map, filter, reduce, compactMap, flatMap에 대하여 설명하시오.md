# ๐งโ๐ป Swift Standard Library์ map, filter, reduce, compactMap, flatMap์ ๋ํ์ฌ ์ค๋ชํ์์ค



map - ์ด๋ค array์ ์์๋ฅผ ์ธ์๋ก ๋ฐ์ ์ธ์๋ฅผ ๋ณ๊ฒฝํ๊ณ  ๋ณ๊ฒฝ ๊ฐ์ ๋ฆฌํดํ๋๋ฐ, ๊ทธ ์์๋ค์ ์ขํฉํ์ฌ ์๋ก์ด ๋ฐฐ์ด์ ๋ง๋๋ ํจ์๋ฅผ ์ธ์๋ก ๋ฐ๋ ๊ณ ์ฐจ ํจ์.

filter - ์ด๋ค array์ ์์๋ฅผ ์ธ์๋ก ๋ฐ์์ ์ธ์์ ์ด๋ค ์์ฑ์ ํน์  ๊ฐ๊ณผ ๋น๊ตํด์ bool ๊ฐ์ ๋ฆฌํดํ๋ ํจ์๋ฅผ filter๋ก ์ ๋ฌํ๋๋ฐ, ์ด ๋ true๋ฅผ ๋ฆฌํดํ ์ธ์๋ง์ผ๋ก ์๋ก์ด ๋ฐฐ์ด์ ๋ง๋๋ ๊ณ ์ฐจ ํจ์.

reduce - ์ด๊น๊ฐ์ ์ค์ ํ๊ณ  , array์ ๋ ์์๋ฅผ ํ๋ผ๋ฏธํฐ๋ก ๋ฐ์ ๋ํ ๊ฐ์ ์ด๊น๊ฐ๊ณผ ๋ํ๊ณ , ์ด ๊ฐ์ด ์ด๊น๊ฐ์ด ๋๋ฉฐ ์์๋ค์ ๋ํด๋๊ฐ๋ ํจ์๋ฅผ ๋ฐ๋ ๊ณ ์ฐจํจ์.

compactMap - map์ ์คํํ  ๋, array์ ์์ ์ค nil์ด return ๋ ์์๋ฅผ ์ ์ธํ ์์๋ค๋ก ์๋ก์ด ๋ฐฐ์ด์ ๋ง๋๋ ๊ณ ์ฐจํจ์.

flatMap - array์ ์์๋ค์ด ๋ squence๋ฅผ ์ด๋ฃจ๊ณ  ์์ ๋, squence๋ค์ flatํ๊ฒ ๋ง๋ค์ด array๋ฅผ ์ผ์ฐจ์ array๋ก ๋ง๋๋ ๊ณ ์ฐจํจ์.