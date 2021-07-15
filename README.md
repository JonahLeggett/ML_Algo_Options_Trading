 ## Machine Learning Algorithm for Options Trading
 
 
<img width="848" alt="Screen Shot 2021-07-07 at 6 32 48 PM" src="https://user-images.githubusercontent.com/80833988/124848463-bcee2200-df51-11eb-886d-85228b6cbc85.png">


> "In 2018, the Chicago Board Options Exchange reported that over $1 quadrillion worth of options
were traded in the US.
"



📌 In this Project, we assumed the role of a quantitative analyst for using a FinTech investing platform. This platform aims to offer investor sophisticated Options Trading mechanism. Using Machine Learning to evaluate our trading algorithm written in Python we strive to remove uncertainty and a human factor to automate Options investment decision making.



## Table of content 📔
- [An executive summary](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#an-executive-summary)
    - [How this project relates to fintech and machine learning?](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#how-this-project-relates-to-fintech-and-machine-learning)
- [Software Version Control](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#software-version-control)
- [Data Collection and Preparation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#data-collection-and-preparation-10-points)
    - [Libraries](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#libraries)
- [Machine learning](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#machine-learning-40-points)
- [Documentation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#documentation)
- [Presentation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#presentation)
    - [Machine Learning]()
    - [Work with data]()
    - [Results]()
    - [Working on issues]()
    - [Next Steps]()
- [How to install](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#how-to-install)
- [Our team](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#team)
- [Licence](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#license)
- [Links](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#links)



## An executive summary

> " For out second project we decided to take challenging, but most rewarding approach - to work on our passion project.
"
##### How this project relates to fintech and machine learning?

We are using the power of Python, machine learning and neural network to build a sophisticated algorithmic trading bot. 
Specifically, we would like to in depth explore stock options trading 

>“Option contracts are a financial derivative that represents the right, but not the obligation, to buy (call) or sell (put) a particular security before expiration date…..
Because of the huge diversity of historical options data and their relatively few applications, no open source dataset exists."



## Software Version Control 


- Repository [ML_Algo_Options_Trading](https://github.com/JonahLeggett/ML_Algo_Options_Trading.git) was created on GitHub.

- Our team made sure files were frequently committed to repository. 

- Commit messages with appropriate level of detail included with each commit. Moreover you can find well  commented code in our Jypyter Notebook with analyses and explained results for user lacking a technical understanding

- Repository organized, relevant information about the project files included. 




## Data Collection and Preparation (10 points)

* API calls from multiple sourses, working on multiple databases created by using Python and Python library. 

#### Libraries 

*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* With the combination of Pandas and Jupyter Notebook, you can efficiently import, prepare, and analyze data of any type or quantity.
* We created a Google Collab group to take advantage of the speed and convenience of collaborative cloud environment.
* Following libraries were used to analyze the data 

[
<img width="686" alt="Screen Shot 2021-07-14 at 7 31 39 PM" src="https://user-images.githubusercontent.com/80833988/125718772-f6bdf922-fdff-4b1d-87e3-f5a9dc2b2f63.png">
](url)




🆕 We used following new libraries not covered in Bootcamp course 

<img width="361" alt="Screen Shot 2021-07-13 at 6 53 33 PM" src="https://user-images.githubusercontent.com/80833988/125548152-09ff4209-0955-4c09-bb42-23c2e1f96a18.png">



〰️ [yfinance](https://finance.yahoo.com/quotes/Historical,Option,DATA,Implied,Volatility,EOD/view/v1) is a popular open source library developed by Ran Aroussi as a means to access the financial data available on Yahoo Finance.
Yahoo Finance offers a range of market data on stocks, bonds etc. It also offers market news, reports and analysis and additionally options and fundamentals data- setting it apart from some of it’s competitors

〰️ FinTA (Financial Technical Analysis) supports over 80 trading indicators.

〰️ [sentiment-investor](https://sentimentinvestor.com/) APIs for stock social media data
Get high quality, granular data, on what people are saying on various social platforms about stocks and cryptocurrencies




## Machine Learning (40 points)
* Jupyter notebook and Google Colab. We used group work feature in Google Collab to be able to simultaneously work on code and make a changes in real time.
* We created ....... mashine learning models

##### Linear and Polynomial Regression

We are using both linear and polynomial regression  machine learning models, depends on what kind of prediction we are trying to make and the occuring trend.


<img width="463" alt="Screen Shot 2021-07-13 at 6 51 19 PM" src="https://user-images.githubusercontent.com/80833988/125547952-636a2a91-d547-49ad-8885-fc09328423bc.png">

>"Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data.
Polynomial regression is a form of regression analysis in which the relationship between the independent variable x and the dependent variable y and considered to be a special case of multiple linear regression
"

* Models fit to the training data. (5 points) 
* Trained models evaluated by using the testing data. Calculations, metrics, or visualizations that are needed to evaluate the performance included. (10 points) 
* Predictions shown by using a sample of new data. Predictions compared if more than one model was used. (3 points) 
* PNG images of your visualizations saved to distribute to the class and instructional team and to include in your presentation and the README.md file for your repo. (2 points) 
* One new machine learning library, machine learning model, or evaluation metric used that the class hasn't already covered. (10 points) 



## Documentation 

* You can find Code in Jupyter Notebook is well commented with concise, relevant notes. 

* GitHub README.md file includes a concise project overview. We followed step by step [Technical requirements](https://courses.bootcampspot.com/courses/740/pages/16-dot-16-dot-5-technical-requirements?module_item_id=194212) for grading team convenience.

* GitHub README.md file includes detailed usage and installation instructions [How to install]()
* GitHub README.md file includes examples of the application AND the results with progected revenue.


## Presentation 

### Machine Lerning model

* The selected model. (5 points)
    * Describe the machine learning model that your group selected and why.
* The data preparation and model training process. (3 points)
    * Describe the source of your data and why you chose it for your project. 
Yahoo-option chains
Alpaca - stock data
[Sentiment investor](https://sentimentinvestor.com/)
 reason- sentiment social media
 
 json 
 convert timestamps
 

    * Describe the collection, cleanup, and preparation process. 
    * Describe the training process.
    * 
we train models 

tech indicators: moving  MACD RSI CCI



fundamental indicator -sentiment analy
 
* The approach that your group took to achieve the project goals. (5 points)
    * Include any relevant code or demonstrations of the machine learning model. 



* The results and conclusions from the machine learning model or application. (5 points)
    * Include relevant images or examples to support your work. 


### Working on issues

>" Discuss any unanticipated insights or problems that arose and how you resolved them."

1. Finding data. 
 main problem we encounter was finding the data. The original source we planned to use - Alpaca - worked for some data. But we needed to find some alternative sourses of data. Some of the ones we tried, like [QuantConnect](https://www.quantconnect.com) - didnt work. After trial and error we end up using [following libriries]()


2. Unifying the data

Some sourses return data in json format, which has different frame construction. Our solution was to create new data frames, change indexes, concatinate or join some data frames together. It took a lot of time and creative solutions, but we were able to do it.


3. Difficulty in pricing options 

 Very hard to put  into code a process of forecasting option contract prices. Our solution was to changed the strategy. Instead we are forecasting stock prices. Because stock price directly correlates with option contracts price change we can use machine learning strategies we developeped to make a desision to buy or sell stock.
 
 4. Choosing iindicators and incorporating them into code.
  Technical Indicator is essentially a mathematical representation based on data sets to forecast price trends. Choosing the right set of indicators was another challange. We end up using:
 ........................
 
 5. How do we convert sentiment analyses?
Another challenge was to convert data for [sentiment analyses](https://sentimentinvestor.com/) into a single data frame and working through that data

6. Create and fill up "buy/sell" column 






### Next steps. (2 points)
  * Potential next steps for the project would be 
1.Adding more indicators or trying different set of indicators
2. Try the strategy on different stocks
3. Incorporate Deep Learning Network 
 
    * If we had more timewe would continue our research in following areas:
1. Build a bot or some other interface to automatically placed orders or execute buy/sell in real time
2. Link real accounts to the algorithm and actually start executing our strategy
3. Explore more complex trading strategies, like Iron Condor 
4. 
>"An iron condor is an options strategy consisting of two puts (one long and one short) and two calls (one long and one short), and four strike prices, all with the same expiration date. The iron condor earns the maximum profit when the underlying asset closes between the middle strike prices at expiration. In other words, the goal is to profit from low volatility in the underlying asset."























### How to install

##### Repository

* Save remote repo from GitHub to your computer (Desktop): 
in Terminal type:

```
cd desktop

git clone https://github.com/
```

Now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ .ipynb ] file to see the analysis report.


##### Alpaca API call

In order to succesfully run the file you have to generate your own Alpaca key and save it to .env file. Those files are hidden so Hold down the Command, Shift and Period keys (for Mac) to be sure you have it in the same folder as Jupyter Lab notebook

```
 cmd + shift + [.]
```
To generate Alpaca key you have to create your own account and request a new key. Save it in .env file, make sure to name the variables ALPACA_API_KEY and ALPACA_SECRET_KEY 
```

ALPACA_API_KEY = '<your key>'
ALPACA_SECRET_KEY = '<your key>'

```

Those steps are nessesary to maintain a security of private information. 




## Team
📩 [Natalia Burrey](https://github.com/nataliaburrey)
📩 [Jonah Leggett](https://github.com/JonahLeggett)
📩 [Miguel Ortega]()
📩[Samuel Yang]()





## License

MIT

## Links

* [Resourses]
* [Jupyter Lab]
* [Repository copy link]
* [Presentation Prezi Website]


:star:



