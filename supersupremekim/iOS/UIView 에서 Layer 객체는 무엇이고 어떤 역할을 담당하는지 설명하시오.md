# ๐  UIView ์์ Layer ๊ฐ์ฒด๋ ๋ฌด์์ด๊ณ  ์ด๋ค ์ญํ ์ ๋ด๋นํ๋์ง ์ค๋ชํ์์ค



### CALayer๋ CoreAnimation์ด ์ ๊ณตํ๋ ์์ ์ค ํ๋. ๊ฐ View๋ง๋ค ๋ฃจํธ layer๋ ํ๋์ฉ ์กด์ฌํ๋ค.



### ๋ทฐ์์ ์ปจํ์ธ ๋ ์ ๋๋ฉ์ด์์ ๊ทธ๋ฆฌ๋ ์์์ view๊ฐ ์ง์  ์ฒ๋ฆฌํ์ง ์๊ณ  core animation์ ์์ํจ. ๊ทธ๋ฌ๋ฉด CALayer๊ฐ ๋ทฐ ์์ ์ปจํ์ธ ์ ์ ๋๋ฉ์ด์์ ๊ทธ๋ฆฌ๋ ์์์ ๋ด๋นํ๊ฒ ๋จ.



### ๋ทฐ์ ์ํ ๋ฃจํธ layer๋ฅผ ํตํด shadow์ cornerRadius ๊ฐ์ ์ค์ ํ  ์ ์๋ค. ๋ํ cornerRadius ๊ฐ์ ๋ฐ๋ผ์ ์์ ์ปจํ์ธ ๊ฐ ์งค๋ฆฌ๊ฑฐ๋ ํ๋ ๊ฒฝ์ฐ๊ฐ ๋ฐ์ํ  ์ ์๋๋ฐ, Bool type์ธ clipsToBounds๋ฅผ ์ค์ ํ๋ฉด ๋ฐ๋ ๋ทฐ ํ๋๋ฆฌ ์์ญ์ ์ํด ์์ ์๋ ๋ด์ฉ์ ์๋ฅผ ๊ฒ์ธ๊ฐ ๋ณด์กดํ  ๊ฒ์ธ๊ฐ๋ฅผ ์ค์ ํ  ์ ์๋ค.