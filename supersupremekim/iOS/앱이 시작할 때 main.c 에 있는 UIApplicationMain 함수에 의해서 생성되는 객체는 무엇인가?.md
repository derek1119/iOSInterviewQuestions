# ๐์ฑ์ด ์์ํ  ๋ main.c ์ ์๋ UIApplicationMain ํจ์์ ์ํด์ ์์ฑ๋๋ ๊ฐ์ฒด๋ ๋ฌด์์ธ๊ฐ?



### UIApplication ์ฑ๊ธํด ๊ฐ์ฒด

๋ชจ๋  ์ฑ์ ํ๋์ UIApplication ์ธ์คํด์ค๊ฐ ์๋ค.

์ ์ ์ ์์ดํฐ์์ ์ฑ์ด ์คํ๋  ๋, UIApplication์ด ์คํ๋๊ณ  ์๋ ์ดํ๋ฆฌ์ผ์ด์ ์ค๋ธ์ ํธ์ ํด๋น๋๋ค.

UIApplication์ ํตํด appdelegate์ ์ ๊ทผํ  ์ ์๋ค.

`let appDelegate = UIApplication.shared.delegate as! AppDelegate`