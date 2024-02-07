# Volumes every day

Developed by the Forex Robot Easy Team, Volumes every day is a trading program designed to analyze volume data and execute trades based on market trends. This program utilizes the MetaTrader 4 platform and is intended for use in the forex market.

## Features

- Calculates the average volume within a specified range period
- Analyzes current volume and compares it to the average volume
- Executes buy or sell trades based on market trends
- Displays trading signals on the chart using chart objects

## Installation

To use Volumes every day, follow these steps:

1. Download and install MetaTrader 4 from your preferred broker.
2. Open MetaTrader 4 and login to your trading account.
3. Open the MetaEditor tool by clicking on 'Tools' -> 'MetaQuotes Language Editor' or by pressing the F4 key.
4. In the MetaEditor tool, create a new Expert Advisor (EA) or Custom Indicator (CI) and name it 'Volumes every day'.
5. Copy and paste the provided code into the editor.
6. Save the file and compile it by clicking on 'Compile' or by pressing the F7 key.
7. Close the MetaEditor tool and go back to the MetaTrader 4 platform.
8. Attach the 'Volumes every day' EA or CI to a chart of your choice.
9. Adjust the input parameters according to your preferences.
10. Start the program execution by clicking on 'View' -> 'Strategy Tester' or by pressing the Ctrl+R key.

## How it works

The Volumes every day program works by calculating the average volume within a specified range period and comparing it to the current volume. It performs this calculation for each bar within the specified time range.

The program uses the input parameters to determine the range period, the number of range profiles, and the start and end times for profile construction. It then loops through each bar and checks if it falls within the specified time range.

For each bar within the time range, the program calculates the current volume and the volume within the range period. It keeps track of the total volume within all ranges and the current range count. Once the current range count reaches the specified number of range profiles, the program updates the total volume, resets the range volume and range count, and calculates the average volume.

The program then compares the current volume to the average volume and executes a buy or sell trade based on the market trend. It also displays a trading signal on the chart using a chart object.

## Product Description

Volumes every day is a powerful tool for traders looking to incorporate volume analysis into their trading strategies. By calculating the average volume within a specified range period, this program helps identify market trends and provides trading signals based on volume data.

Key features of Volumes every day include customizable range profiles, the ability to analyze volume data for specific time periods, and automatic execution of buy or sell trades based on market trends.

To use Volumes every day, simply attach the program to a chart in MetaTrader 4 and adjust the input parameters to suit your trading preferences. The program will then calculate the average volume and provide trading signals based on the current volume compared to the average volume.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-forex-software-volumes-every-day-key-differences-and-advantages-of-volume-every-day-indicator-compared-to-similar-product-volume-profile-v6-customize-profile-construction-with-range-per/).
