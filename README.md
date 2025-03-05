# SMART- Stock Market Application for Real-time Trading

Follow these steps to set up and run the trading bot:

## 1. Create a Virtual Environment
To create a virtual environment named `smart` with Python 3.10, run the following command:

```bash
conda create -n smart python=3.10
```
## 2. Activate the Virtual Environment
Activate the `smart` environment by running:

```bash
conda activate smart
```
## 3. Install Initial Dependencies
Install the required dependencies using `pip` by running the following command:

```bash
pip install lumibot timedelta alpaca-trade-api==3.1.1
```
These dependencies include Lumibot, timedelta, and Alpaca Trade API (version 3.1.1), which are necessary for the bot to function properly.

## 4. Install Transformers and Related Libraries
Install PyTorch, torchvision, torchaudio, and transformers with this command:

```bash
pip install torch torchvision torchaudio transformers
```
These libraries are needed for machine learning tasks and natural language processing in the bot.

## 5. Update Your Alpaca API Credentials
Ensure you update the `API_KEY` and `API_SECRET` in your `tradingbot.py` script with your Alpaca account credentials. You can get these keys from your Alpaca dashboard.

```python
API_KEY = 'your_api_key'
API_SECRET = 'your_api_secret'
```
This will authenticate the bot with your Alpaca account.
## 6. Run the Trading Bot
After everything is set up, you can run the bot by executing:

```bash
python tradingbot.py
```
This will start the trading bot, and it will begin executing trades according to the strategy in the tradingbot.py file.

