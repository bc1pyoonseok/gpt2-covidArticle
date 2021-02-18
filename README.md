
# GPT2 covidArticle
[![Run on Ainize](https://ainize.ai/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/ha-mulan/gpt2-covidArticle)




### Model information


    Base model: gpt-2 large
    Epoch: 22
    Loss: 0.1053
    Dataset:covid-19 Article

### About
	* it is the gpt2 large base model that generate text based on your input keyword
	*

### How to use

    * three ways to use Gpt2 covid article
    	* CLI
    	* Swagger
    	* Demo

### GET parameter

    keyword: keyword of covid article you want to generate


### Output format

    generated text


## * With CLI *

### Input example

    curl -X GET "https://master-gpt2-covid-article-ha-mulan.endpoint.ainize.ai/api/?keyword=deadly" -H "accept: string"
    

### Output example


   	deadly ill patients with confirmed COVID-19 by SARS-CoV-2 RT-PCR between March 1 and March 18, 2020.
	Outcomes were followed up to March 25, 2020.
	RESULTS: Among the 299 hospitalized patients with COVID-19, the median age was 59 years (interquartile range, 49-69; range, 20-91 years), and 138 (53.0%) were men.
	Of the deceased patients, 64 (24.9%) had a history of chronic medical illness, including diabetes (54 [20.4%]), hypertension (40 [14.9%]), chronic cardiovascular disease (24 [9.8%]), chronic kidney disease (16 [ 5.0%]), and malignancy (16 [5.0%]).
	The median time from hospital admission to death was 9 days (interquartile range, 7-12; range, 0-31).
	At the time of hospital admission, dyspnea (55 [22.6%]), cough (40 [14.9%]), and fatigue (26 [10.7%]) were the most common symptoms.
	The median time from illness onset to dyspnea was 7 days (interquartile range, 2-9; range, 0-13), and cough was present in 92.1% (152/299) of the 	deceased patients.


## * With swagger *

API page: [Ainize](https://ainize.ai/ha-mulan/gpt2-covidArticle?branch=master)

## * With a Demo *

Demo page: [End-point](https://master-gpt2-covid-article-ha-mulan.endpoint.ainize.ai)
