 ## Machine Learning Algorithm for Options Trading
 
 
<img width="848" alt="Screen Shot 2021-07-07 at 6 32 48 PM" src="https://user-images.githubusercontent.com/80833988/124848463-bcee2200-df51-11eb-886d-85228b6cbc85.png">


> "In 2018, the Chicago Board Options Exchange reported that over $1 quadrillion worth of options
were traded in the US.
"









📌 In this Project, we assumed the role of a quantitative analyst for using a FinTech investing platform. This platform aims to offer investor sophisticated Options Trading mechanism. Using Machine Learning to evaluate our trading algorithm written in Python we strive to remove uncertainty and a human factor to automate Options investment decision making.




## Table of content 📔
- [An executive summary]()
    - [Overview of the project and project goals]()





## Software Version Control 


- Repository [ML_Algo_Options_Trading](https://github.com/JonahLeggett/ML_Algo_Options_Trading.git) was created on GitHub.

- Our team made sure files were frequently committed to repository. 

- Commit messages with appropriate level of detail included with each commit. Moreover you can find well  commented code in our Jypyter Notebook with analyses and explained results for user lacking a technical understanding

- Repository organized, relevant information about the project files included. 




Data Collection and Preparation (10 points)
* Data collected from CSV files, APIs, or databases by using Python or a Python library. (5 points) 
* Data cleaned and prepared for the application or analysis by using Python or a Python library. (5 points) 

#### Libraries 

*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* With the combination of Pandas and Jupyter Notebook, you can efficiently import, prepare, and analyze data of any type or quantity.
* We created a Google Collab group to take advantage of the speed and convenience of collaborative cloud environment.
* Following libraries were used to analyze the data 

[
<img width="579" alt="Screen Shot 2021-07-12 at 5 18 15 PM" src="https://user-images.githubusercontent.com/80833988/125371228-26e13f80-e335-11eb-8c5a-007e3c28ffd1.png">
](url)




🆕 We used following new libraries not covered in Bootcamp course 

<img width="361" alt="Screen Shot 2021-07-13 at 6 53 33 PM" src="https://user-images.githubusercontent.com/80833988/125548152-09ff4209-0955-4c09-bb42-23c2e1f96a18.png">



〰️ [yfinance](https://finance.yahoo.com/quotes/Historical,Option,DATA,Implied,Volatility,EOD/view/v1) is a popular open source library developed by Ran Aroussi as a means to access the financial data available on Yahoo Finance.
Yahoo Finance offers a range of market data on stocks, bonds etc. It also offers market news, reports and analysis and additionally options and fundamentals data- setting it apart from some of it’s competitors

〰️ FinTA (Financial Technical Analysis) supports over 80 trading indicators.

〰️ [sentiment-investor](https://sentimentinvestor.com/) APIs for stock social media data
Get high quality, granular data, on what people are saying on various social platforms about stocks and cryptocurrencies






## Machine Learning (40 points)
* Jupyter notebook, Google Colab notebook, or Amazon SageMaker Studio notebook created to prepare training and testing datasets. (5 points) 
* One or more machine learning models created. (5 points)
*  
* Models fit to the training data. (5 points) 
* Trained models evaluated by using the testing data. Calculations, metrics, or visualizations that are needed to evaluate the performance included. (10 points) 
* Predictions shown by using a sample of new data. Predictions compared if more than one model was used. (3 points) 
* PNG images of your visualizations saved to distribute to the class and instructional team and to include in your presentation and the README.md file for your repo. (2 points) 
* One new machine learning library, machine learning model, or evaluation metric used that the class hasn't already covered. (10 points) 

Jupyter notebook and Google Colab. We used group work feature in Google Collab to be able to simultaneously work on code and make a changes in real time.
#### Linear and Polynomial Regression

We are using both linear and polynomial regression  machine learning model, depends on what kind of prediction we are trying to make.


<img width="463" alt="Screen Shot 2021-07-13 at 6 51 19 PM" src="https://user-images.githubusercontent.com/80833988/125547952-636a2a91-d547-49ad-8885-fc09328423bc.png">

>"Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data.
Polynomial regression is a form of regression analysis in which the relationship between the independent variable x and the dependent variable y and considered to be a special case of multiple linear regression
"



 
## Documentation 

* You can find Code in Jupyter Notebook is well commented with concise, relevant notes. 

* GitHub README.md file includes a concise project overview. We followed step by step [Technical requirements](https://courses.bootcampspot.com/courses/740/pages/16-dot-16-dot-5-technical-requirements?module_item_id=194212) for grading team convenience.

* GitHub README.md file includes detailed usage and installation instructions [How to install]()
* GitHub README.md file includes examples of the application AND the results and [Summary of the analysis]() 


### Presentation 

## An executive summary

> " For out second project we decided to take challenging, but most rewarding approach - to work on our passion project.
"
##### How this project relates to fintech and machine learning?

We decided to use the power of Python, machine learning and neural network to build a sophisticated algorithmic trading bot. 
Specifically, we would like to in depth explore stock options trading 

>“Option contracts are a financial derivative that represents the right, but not the obligation, to buy (call) or sell (put) a particular security before expiration date…..
Because of the huge diversity of historical options data and their relatively few applications, no open source dataset exists."


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

tech indicators

moving  SMA RSI CCI
MACD

fundamental indicator -sentiment analy
 
* The approach that your group took to achieve the project goals. (5 points)
    * Include any relevant code or demonstrations of the machine learning model. 
    * Describe the techniques that you used to evaluate the performance of the model. 
    * Discuss any unanticipated insights or problems that arose and how you resolved them.
Finding data : Alpaca -some data 

QuantConnect-didnt work
Finviz


json data frame construction

created empty data frame
there was no index for a json response

sa_df

2. Difficulty in pricing options 
 forecasting 
 -
 resolution - we changed the strategy
 instead
 we forecasting stock performance not options pricing
 it price closely 
 look into stock closing price to make a call
 
 
4. How do we convert sentiment analyses
Converting data into a single data frame - formats
working through data
res
new data sources thought alpaca  need to find other sources




Our goal has change
Automatically placed orders
we want to use paper accounts 
so we cant do it


5. sxource took a while
6. setting iindicators and incorporating them into code
7. buy column 

Data types- json and different


* The results and conclusions from the machine learning model or application. (5 points)
    * Include relevant images or examples to support your work. 
    * If the project goal wasn’t achieved, share the issues and what the group tried for resolving them. 
* Next steps. (2 points)
    * Take a moment to discuss the potential next steps for the project. 
    * Discuss any additional questions that you’d explore if you had more time. Specifically, if you had additional weeks to work on your project, what would you research next?





















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



