# ๐ ๋ถ์ฐ ์ฒ๋ฆฌ Distributed Processing

### Q01. Apache Beam์ ๋ํด ์์๋์? ๊ธฐ์กด ํ๋ก๊ณผ ์ด๋ค ์ฐจ์ด๊ฐ ์์๊น์?

### Q02. ์ข๊ฒ ๋ง๋ค์ด์ง MapReduce๋ ์ด๋ค ํ๋ก๊ทธ๋จ์ผ๊น์? ๋ฐ์ดํฐ์ Size ๋ณํ์ ๊ด์ ์์ ์ค๋ชํ  ์ ์์๊น์?

### Q03. ์ฌ๋ฌ MR์์์ ์ฐ์๋ก ์ต์ข๊ฒฐ๊ณผ๋ฌผ์ด ๋์ฌ๋, ์ค๊ฐ์ ์์์ด Fail๋ ์ ์์ต๋๋ค. ์์์ Fail์ ์ด๋ป๊ฒ ๋ชจ๋ํฐ๋ง ํ์๊ฒ ์ต๋๊น? ์์๋ค๊ฐ์ dependency๋ ์ด๋ป๊ฒ ํด๊ฒฐํ์๊ฒ ์ต๋๊น?

### Q04. ๋ถ์ฐํ๊ฒฝ์ JOIN์, ๋ณดํต ๋์คํฌ, CPU, ๋คํธ์ํฌ ์ค ์ด๋์์ ๋ณ๋ชฉ์ด ๋ฐ์ํ ๊น์? ์ด๋ฅผ ํด๊ฒฐํ๊ธฐ ์ํด ๋ฌด์์ ํด์ผ ํ ๊น์?

### Q05. ์๋ฌ์ ๋ฒ์น์ ๋ํด ๋งํด๋ด์๋ค. ๊ทธ๋ฌ๋ฏ๋ก ์ shared-nothing ๊ตฌ์กฐ๋ก ๋ง๋ค์ด์ผ ํ๋์ง ์ค๋ชํด๋ด์๋ค.

### Q06. shared-nothing ๊ตฌ์กฐ์ ๋จ์ ๋ ์์ต๋๋ค. ์ด๋ค ๊ฒ์ด ํด๋นํ ๊น์?

### Q07. Spark์ด Hadoop๋ณด๋ค ๋น ๋ฅธ ์ด์ ๋ฅผ I/O ์ต์ ํ ๊ด์ ์์ ์๊ฐํด๋ด์๋ค.

### Q08. ์นด์ฐ๋๋ผ๋ ๋งํ๊ฒ ๊ฐ์ต๋๋ค. ์ ๋งํ๊ฒ ๊ฐ๋์? ๊ทธ๋๋ ํ์ฉ์ฒ๊ฐ ์๋ค๋ฉด ์ด๋์ธ๊ฒ ๊ฐ๋์.

### Q09. TB ๋จ์ ์ด์์ ๊ธฐ์กด ๋ฐ์ดํฐ์ ์๊ฐ๋น GB๋จ์์ ์ ์ ๋ก๊ทธ๊ฐ ๋ค์ด์ค๋ ์๋น์ค์์ ๋ชจ๋  ๊ฐ์์์๊ฒ ๊ฐ๋ณ์ ์ผ๋ก ๊ณ์ฐ๋ ์ค์๊ฐ ์๋น์ค(์น)๋ฅผ ์ ๊ณตํ๊ธฐ ์ํ ์์คํ ๊ตฌ์กฐ๋ฅผ ๊ตฌ์ํด๋ด์๋ค.

### Q10. ๋์ฉ๋ ์๋ฃ๋ฅผ ๋น ๋ฅด๊ฒ lookupํด์ผ ํ๋ ์ผ์ด ์์ต๋๋ค. (100GB ์ด์, 100ms์ธ๋๋ก ํน์ ์๋ฃ ์ฐพ๊ธฐ). ์ด๋ค ๋ฐฑ์๋๋ฅผ ์ฌ์ฉํ์๊ฒ ๋์? ๋๋ฆฐ ๋ฐฑ์๋๋ฅผ ์ฌ์ฉํ๋ค๋ฉด ์ด๋ฅผ ๋ณด์ํ  ๋ฐฉ๋ฒ์ ๋ญ๊ฐ ์์๊น์?

### Q11. ๋ฐ์ดํฐ๋ฅผ ์ฌ๋ฌ ๋จธ์ ์ผ๋ก ๋ถํฐ ๋ชจ์ผ๊ธฐ ์ํด ์ฌ๋ฌ ์ ํ์ง๊ฐ ์์ ์ ์์ต๋๋ค. (flume, fluentd๋ฑ) ์์ ์์ค๋ก๋ถํฐ kafka๋ฑ์ ๋ฉ์์ง ์์คํ์ ๋ฐ๋ก ์ธ ์๋ ์์ต๋๋ค. ์ด๋ค ๊ฒ์ ์ ํธํ์๋์? ์์ฃ ?