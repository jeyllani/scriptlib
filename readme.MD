<center>
<!-- TradingView Chart BEGIN -->
<script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script>
<script type="text/javascript">
var tradingview_embed_options = {};
tradingview_embed_options.width = '640';
tradingview_embed_options.height = '400';
tradingview_embed_options.chart = 'rSKLxeF1';
new TradingView.chart(tradingview_embed_options);
</script>

</center>

--- 

<p><a href="https://www.tradingview.com/script/rSKLxeF1-MTF-C-Strategy-A/"><h3>MTF C Strategy A</h3></a> by <a href="https://www.tradingview.com/u/FriedChickenWing/">FriedChickenWing</a> on <a href="https://www.tradingview.com/">TradingView.com</a></p>
<!-- TradingView Chart END -->


* The Pearson coefficient is a type of correlation coefficient that represents the relationship between two variables that are measured on the same interval or ratio scale. It's a measure of the strength of the association between two continuous variables.

* This script allows you to choose one or more sources as a curve, if several sources are chosen, their average is taken into account in an EMA or SMA of your choice. It is possible to have the average of all the curves and to add one or more other curves for an influence on the calculated average.
Then, on the basis of this curve a correlation is calculated from 8 time ranges which give 4 curves, it is on this basis that the conditions of entries in the trade and / or exits are based with the possibility of adding an RSI condition.
For some entries, it is possible to try the symmetrically opposite condition, ie the one that is used in shorts.

* To make entry short work, you must activate an exit short option.

* However, exit conditions are more flexible than entry conditions because they allow the inverse entry condition used and / or to use statistical indices such as CCI / RSI / ROC / BB as exit condition independently or combined way.
It should be noted that if a condition among those chosen is executed substantially first, it will predominate over the others (same for long / short entries).

* In addition, it is possible to choose a stop loss as an exit condition, however, it is not possible to * combine the other exit conditions with the stoploss at the same time. Credits to adolgov for the base of the stoploss script part.

* You can combine several curves, just as it is possible to combine several types of trade entries / exits.
The strategy uses 100% of equity, it has not been configured in such a way that there is an order pyramid and the closings are done on a total equity basis.

* You can configure a daily session interval, a limit of the number of daily trades, a limit of drawdown.
You can add comments for each execution of an opening / closing order respectively to the direction (long or short).

* Each step of the configuration has a tip, a button that must be hovered over in order to have the information relating to the configuration.
