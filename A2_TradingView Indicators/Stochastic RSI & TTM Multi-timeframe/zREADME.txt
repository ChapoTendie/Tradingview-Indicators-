README


1-20-23 update repo to include "Stochastic RSI & TTM Multi-timeframe v3.2 - Chapo Tendie"

The intention of this indicator is for it to be used on a multichart window as a standalone indicator on the 1 min timeframe, and used to signal profitable opportunties 

A multitimeframe indicator was developed to chart momentum, volatility, and a stochastic oscillator on a single chart through colored squares across various time frames. Standard time frame ranges were employed for momentum and squeeze indicators, and a meticulous selection process was applied to determine optimal time frames for stochastic analysis. The indicator monitors multiple time frames simultaneously, updating every minute.

Instances of red or green signals on the stochastic oscillator across any time frame are interpreted as potential trade opportunities. Traders can set alerts on TradingView to receive notifications on PCs and phones, prompting further investigation on a primary chart.

The strategy recognizes that smaller time frames may exhibit more oscillatory movements, making them suitable for reversal trades when stochastic values reach extremes. Larger time frames, with tendencies to trend, are considered for trend trades when stochastic values signal directional movements.


IMPORTANT NOTE:
-> The timeframe for this indicator must be set at 1 minute;
-> If the chart timeframe is higher than 1 minute, the results shown in the table for timeframes lower than the chart will not be correct;
-> Tradingview's own documentation explains this as follows: "It is not recommended to request data of a timeframe lower that the current chart timeframe, for example 1 minute data from a 5 minutes chart. The main problem with such a case is that some part of a 1 minute data will be inevitably lost, as it’s impossible to display it on a 5 minutes chart and not to break the time axis. In such cases the behavior of security can be rather unexpected"; and
-> It is therefore recommended that this indicator is placed in a standalone 1min chart window, and the window resized to only show the table to avoid any issues.

Credits:
-> John Carter creating the TTM Squeeze and TTM Squeeze Pro
-> Lazybear's original interpretation of the TTM Squeeze: Squeeze Momentum Indicator
-> Makit0's evolution of Lazybear's script to factor in the TTM Squeeze Pro upgrades - Squeeze PRO Arrows
-> Beardy_Fred evolution of the histogram in Multi-Timeframe TTM Squeeze Pro
-> NeoButane's interpretation of the Stochastic RSI




### Uploading Scripts to TradingView:

1. **Create a TradingView Account:**
   - If you don't have a TradingView account, sign up for one at [TradingView](https://www.tradingview.com/).

2. **Access the Pine Editor:**
   - Log in to your TradingView account.
   - In the top menu, click on "Pine Editor" to open the Pine Script editor.

3. **Create or Import Pine Script:**
   - You can either create a new Pine Script or import an existing one.
   - To create a new script, click on "New Script." To import, paste the script code into the editor.

4. **Save the Script:**
   - Once your script is ready, click on the "Add to Chart" button.
   - If you created a new script, you'll be prompted to provide a name and description. Enter the details and click "Save."

5. **View on the Chart:**
   - The script will be added to the chart, and you can see its visual representation.

6. **Access Script Management:**
   - To manage your scripts, go to the "Indicators" tab on the top toolbar and select "Scripts."
   - Here, you can see a list of your scripts, make edits, or delete them.

7. **Publishing Scripts (Optional):**
   - If you want to share your script with the TradingView community, you can publish it.
   - In the Pine Editor, click on "Publish Script" and follow the prompts. You'll need to provide a title, description, and category.

8. **Use Scripts on Different Charts:**
   - Once a script is saved, you can apply it to different charts.
   - Open the chart you want to apply the script to, click on "Indicators," and find your script under "Scripts."

9. **Customize Settings:**
   - Some scripts may have customizable settings. To adjust them, click on the gear icon next to the script in the "Indicators" menu.

10. **Remove Scripts:**
   - To remove a script from the chart, click on "Indicators," find the script, and select "Remove."

11. **Troubleshooting:**
    - If you encounter errors or issues, double-check the script for syntax errors.
    - Ensure that you have the necessary permissions to access Pine Editor features.

12. **Community and Support:**
    - Explore the TradingView community to learn from others and get support.
    - TradingView has a [help center](https://www.tradingview.com/support/) for additional assistance.

By following these steps, you should be able to successfully upload, manage, and use Pine Scripts on TradingView.
