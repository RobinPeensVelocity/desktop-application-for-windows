# Account performance

Account performance panel is a tool for traders that provides detailed information on the selected accounts. This panel contains a massive array of trading statistics, various P/L charts, data about trade population and drawdowns. Statistics can be shown for operations against various accounts and time periods from 1 day to years chosen in the top section of the Performance panel. It is also possible to set a custom range for statistics displaying.

Account performance panel offers the feature of exporting all statistics and charts to HTML format as a report. To take advantage of this option use the 'Export to HTML' button located on the top right corner of the panel. The report is generated for the selected accounts over the chosen period considering values displayed in the corresponding tabs.

![](../../../.gitbook/assets/1%20%287%29.png)



![](../../../.gitbook/assets/2%20%289%29.png)



Select ‘Show toolbar’, to make Account lookup, Data filter and ‘Export’ button visible. In the Data filter, you can choose options ‘Daily’ or ‘Range’. 

### **Performance Data**

3 parameters:

* Start capital – shows balance value at the beginning of the selected period.
* Final capital – shows balance value at the end of the selected period.
* Net P/L – shows total Net P/L for the selected period.

All information in the ‘Performance Data’ tab is divided into three following sections:

1. Cumulative P/L
2. Trades population
3. Drawdowns

The table consists of 4 columns:

* Variables – in this column, user can find the names of the parameters.
* Total – in this column, user can find parameters for Short and Long trades.
*  Long – in this column, user can find parameters for Long trades.
* Short – in this column, user can find parameters for Short trades.

Let’s consider all the tabs in details.

The first section is **Cumulative P/L**. Here users can see all the information on their trading results and capital. In the ‘Total’ tab, the value of all settled and unsettled P/L account operations is displayed. Operation values can also be viewed separately divided by operation type \(‘Long’ and ‘Short’ tabs\).

Cumulative P\L :

*  Profit factor – indicator of profitability showing what average profit in relation to loss is. Calculated as:

Profit factor = \(avr\_TP \* %TP\)/\(avr\_SL \* %SL\), where:

avr\_TP – size of the average profitable trade \(in ccy\);

%TP – probability of the profitable trade receiving;

avr\_SL – size of the average losing trade \(in ccy\); avr\_SL is always taken modulo.

%SL – probability of the losing trade receiving.

* Fee = \(Fee/Start capital\)\*100%
*  Expected payoff – mathematical expectation of win. This parameter to be calculated statistically represents average profit/loss factor of one trade. Calculation formula:

Expected payoff = \(avr\_TP \* %TP\) – \(avr\_SL \* %SL\), where

avr\_TP – size of the average profitable trade \(in ccy\);

%TP – probability of the profitable trade receiving;

avr\_SL – size of the average losing trade \(in ccy\); avr\_SL is always taken modulo.

%SL – probability of the losing trade receiving.

* Recovery factor – is a ratio of the net profit to the maximum drawdown. Calculation formula:

Recovery factor = Net profit / Max DD, where

Max DD – module of the maximum drawdown \(in ccy\);

Net profit – trading result for the analyzed period.

* Sharpe Ratio – is a ratio of the expected payoff to the standard deviation. Calculation formula:



STD – standard deviation of the trading results;

STD = SQRT\(1/\(n-1\) \* SUM\(xi-avr\_x\)^2\)

* Win/Loss Ratio 
*  Equity linearity factor – shows the dispersion degree of the balance chart relative to its regression line. Calculation algorithm:

  1\) Calculate the linear regression on the cumulative array of points of the balance \(equity\).

  Ŷ = a + b\*x

![](../../../.gitbook/assets/3%20%284%29.png)

2\) Calculate the standard deviation \(SD\):

![](../../../.gitbook/assets/4%20%281%29.png)

3\) Plot +1SD and -1SD from obtained regression line.

       4\) Calculate the percentage of points that went beyond the boundaries of standard deviation:

 Equity linearity factor = \(Number of points that are below and above the SD lines/Total number  of points\) \* 100%

 The closer the factor to 100%, the more linear the balance chart.

Trades population:

·         Trades Loss – shows total loss by all losing trades for period.

·         Trades Win – shows total profit by all winning trades for period.

·         Average Loss – displays the average P/L value for one trade, and separately average loss for losing trades.

·         Average Win – displays the average P/L value for one trade, and separately average win for winning trades.

·         Max. consecutive Loss – shows the longest series of losses in a row among the total number of trades, and their value in the money.

·         Max. consecutive Win – shows the longest series of wins in a row among the total number of trades, and their value in the money.

·         Largest Loss – displays the largest profit loss of one trade for the selected period.

·         Largest Win – displays the largest profit win of one trade for the selected period.
