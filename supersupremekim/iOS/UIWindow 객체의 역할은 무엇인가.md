# ๐ UIWindow ๊ฐ์ฒด์ ์ญํ ์ ๋ฌด์์ธ๊ฐ



- ### ์ฑ์ ์๊ฐ์  ์ปจํ์ธ ๋ฅผ ๋ด๋๋ค

- ### ํฐ์น ์ด๋ฒคํธ๋ฅผ ์ ๋ฌํ๋ค



### window - ๋ทฐ๋ค์ ๋ด๋ ์ปจํ์ด๋

#### ์คํฌ๋ฆฐ์ ํ์๋๋ ๋ทฐ์ ๊ณ์ธต ๊ตฌ์กฐ์์ ์ต์์ ๋ทฐ์ ์ญํ ์ ํ  ๊ณ ์ ์ ์ธ ๊ฐ์ฒด์ ์ญํ ์ ํ๋ค.

#### ๋จ ํ๋์ window ๊ฐ์ฒด๋ง ์์ฑํ๊ณ , ์ด ๊ฐ์ฒด๋ฅผ ํตํด์ rootviewcontroller๋ฅผ ์ค์ ํ  ์ ์๋ค.



### ์คํ ๋ฆฌ ๋ณด๋๋ฅผ ์ฐ์ง ์๋ ๊ฒฝ์ฐ, ๋ฉ์ธ window๋ฅผ ์ง์  ์์ฑํด์ผ ํ๋ค. ๋ฐฉ๋ฒ์ window์ UIWindowScene์ ์ง์  ๋ฃ์ด์ค์ผ ํ๋ค.

๊ตฌ์ฒด์ ์ผ๋ก๋ plistํ์ผ์ Application scene manifest์ ํ์ ์์ฑ ์ค Storyboard Name ํญ๋ชฉ์ ์ญ์ ํ๊ณ , Scene delegate ํ์ผ์์ ์ฑ์ ๋ฐ์นํ  ๋ ์คํ๋๋ ๋ฉ์๋์ธ ์ ์ผ ์ฒซ๋ฒ์งธ ๋ฉ์๋์์ windowScene์ ์์ฑํ๊ณ  ํด๋์ค์ ์ต์๋๋ก ๋์ด ์๋ window ์์ฑ์ ์ฌ์ ์ฃผ์ํด์ฃผ๊ณ , window์ root viewcontroller๋ฅผ ์์ฑํ์ฌ ์ค์ ํ๊ณ  window?.makeKeyAndVisible() ์ ์์ฑํด์ค๋ค.

