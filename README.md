# Forecasting Net Prophet

The company, [MercadoLibre](http://investor.mercadolibre.com/investor-relations), is the most popular e-commerce site in Latin America. This notebook will analyze the company's financial and user data in clever ways to see if it can make the company grow. This notebook will find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

This will be done via 5 steps:
    1. Checking out if any unusual patterns in the Google search data for the company can be connected to corporate financial events.
    2. Marketing wants to track and predict interest in the company and its platform for any time of day, so they can focus their marketing efforts.
    3. Finance wants to know if any relationship between the search data and the company stock price exists.
    4. Produce a time series model that analyzes and forecasts patterns in the hourly search data.
    5. Finance wants a forecast of the total sales for the next quarter, so they can plan budgets and guide expectations.


---

## Technologies

This notebook will be using Google Colab, so this frame will be essential to run first.

```python

    from IPython.display import clear_output
    try:
      !pip install pystan
      !pip install fbprophet
      !pip install hvplot
      !pip install holoviews
    except:
      print("Error installing.")
    finally:
      clear_output()
      print("Installed.")
  
```

---

## Installation Guide

Nothing needs to be installed as Colab will hold it all for you.

You will just need to upload the corresponding .csv files in the Resources folder as it asks for them.

---

## Usage

To access the forecasting net prophet notebook, please begin by accessing Google Colab.

[Google Colab](https://colab.research.google.com/)

Next, find the folder with the notebook(forecasting_net_prophet.ipynb) and select it to open the notebook in Colab. Then, begin running through each section of the application to get the appropriate data.

Once in the notebook it will take you through a step-by-step process as it Collects the Data, Prepares the Data, and Analyzes the Data.
You will be granted Visualizations along the way to help better see and understand the data.

We do believe everything is thoroughly explained in the notebook, but please let us know if you have any further questions.

---
## Contributors

### Matthew Stream
m.stream3663@gmail.com

[LinkedIn](https://www.linkedin.com/in/matthew-stream-mba-215634102/)

---

## License

MIT