# ๐ TableView๋ฅผ ๋์ ๋ฐฉ์๊ณผ ํ๋ฉด์ Cell์ ์ถ๋ ฅํ๊ธฐ ์ํด ์ต์ํ ๊ตฌํํด์ผ ํ๋ DataSource ๋ฉ์๋๋ฅผ ์ค๋ชํ์์ค



### row์ ๊ฐฏ์๋ฅผ ๋ฆฌํดํ๋ tableview numberOfRowInSection ๋ฉ์๋์, UITableviewcell์ ๋ฆฌํดํ๋ tableview cellForRowAt ๋ฉ์๋๊ฐ ํ์ ๋ฉ์๋์ด๋ค.

### ๋๋ฒ์งธ cellForRowAt ๋ฉ์๋๋ tableview ํ๋ฉด์ ๋ณด์ฌ์ง ๊ฐ ์์ ๋ง๋ค ๋๋ง๋ค ํธ์ถ๋๋๋ฐ, tableview์ identifier์ ๋ง๋ reusable cell์ deque์์ผ์ cell์ ๊ตฌ์ฑํ๊ณ  ํด๋น cell์ ๋ฆฌํดํด์ฃผ๋ ๋ฐฉ์์ผ๋ก ์งํ๋๋ค.