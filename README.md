# alfred-airbank-currency-rates
[Alfred 3][1] workflow for showing actual currency exchange rates of Airbank [Czech Republic].

## Installation

1) Register at [AirBank Developers Portal][3] to get your own public access API key
2) Create your own public API key
   - Tap on the `+ Create new application` button and fill in the application name and a description. You could use any values here.
   - Then, tap on the `+ Create new application version` button and fill it according following image. Eventually, press the `Create` button.
   ![Developer portal - New Version](doc/images/developerNewVersion.png?raw=true "")
      
3) Install [alfred-airbank-currency-rates wokflow.][2]
   - Copy your API Key from the developer portal version details to clipboard.    
   ![Developer portal - New Version](doc/images/developerVersionDetail.png?raw=true "")
   
   - In Alfred, paste your API Key to the workflow configuration properties.
   ![Alfred - Workflow Configuration](doc/images/alfred-workflow-configuration.png?raw=true "")

4) All further updates are handled automatically.

## Usage

In Alfred, type `air` and actual exchange rates will be downloaded from AirBank and shown in Alfred. The most useful, EUR and USD, will be displayed on the top of exchange rates list, the remaining will be ordered by currency abbreviation. 

![Alfred - workflow main](doc/images/alfred-airbank-main.png?raw=true "")

------------------

Additionally, the cash amount could be added. Then, the exchange results will be updated.

![Alfred - workflow main with amount](doc/images/alfred-airbank-main-amount.png?raw=true "")

------------------

This workflow could be also invoked by pressing global shortcut <key>⌃⌘c</key>. When you have a number in a selection, this one will be used as the cash amount passed to the workflow. Very useful in combination with a web browser. 

![Alfred - workflow main with selected text in external program](doc/images/alfred-amazon-airbank-selected-amount.png?raw=true "")

------------------

[1]: https://www.alfredapp.com/
[2]: https://github.com/vookimedlo/alfred-airbank-currency-rates/releases/latest
[3]: https://developers.airbank.cz/
