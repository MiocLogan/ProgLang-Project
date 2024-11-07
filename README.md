# ProgLang-Project
Currency Converter

A currency converter application in three different languages (Python, JavaScript, C#) with each having a separate implementation.

ABOUT THE APPLICATION:
-The main goal of the application is to allow users to convert certain amounts from one currency to another based on real-time currency values when online, or using pre-set values when offline, for 5 different currencies (EUR, USD, GBP, BAM, CHF).Users can select currencies and enter amounts to get instant conversion results. Offering flexibilities in different situations.

FEATURES:
  -Single Currency Conversion:
    Allows user to input an amount in one currency and recive the converted amount based on the selected currency.
    
  -Offline mode:
    Allows the user to convert currencies from one to another using pre-set values for 5 different currencies.
    
  -Online mode:
    Allows the user to convert currencies from one to another using fetched live exchange rates using an online API, ensuring that the       conversions are accurate and up to date.

  -See conversion history:
    After every conversion, the application saves the conversion details to a JSON file, this file stores information such as the base currency, the target currency, the conversion rate, amount and the converted value.

  -Error handling:
    The application manages invalid inputs sidplaying appropriate error messages when necessary.
