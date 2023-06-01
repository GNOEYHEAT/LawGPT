# LawGPT

## Data structure
<pre><code>
LawGPT
├── data
├──├── example
├──├── raw
├──├──├── law : 한글 파일 형식의 법 데이터
├──├──├── precedent.csv : 크롤링한 판례 데이터
├──├── law_preprocess.csv : 전처리된 법 데이터
├──├── precedent_preprocess.csv : 전처리된 판례 데이터
├── utils
├──├── chromedriver.exe
      .
      .
      .
</code></pre>

## Environments
<pre><code>
pip install torch
pip install transformers
pip install accelerate
</code></pre>

## Run

* 1-precedent_crawling.ipynb : 판례 크롤링 코드
* 2-precedent_preprocess.ipynb : 판례 전처리 코드
* 3-precedent_crawling.ipynb : 법 한글 파일에서 엑셀 파일로 변환 코드
* 4-precedent_crawling.ipynb : GPT 모델링 코드
