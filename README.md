# rnn_vs_lstm
Sequence Modeling with RNN and LSTM for Text Classification

# Training Result
### RNN
![RNN](https://github.com/JBRonaldHandiwinata/rnn_vs_lstm/blob/master/blob/rnn.png?raw=true)


### LSTM
![LSTM](https://github.com/JBRonaldHandiwinata/rnn_vs_lstm/blob/master/blob/lstm.png?raw=true)


# Conclusion
1. General Loss Trends<br/>
<ul>
<li>LSTM Performance:</li>
    <ul>
        <li>The loss curve for LSTM consistently shows a decreasing trend across all dimensions (128, 256, 512).</li>
        <li>Lower loss values indicate better performance and training efficiency.</li>
    </ul>
<li>RNN Performance:</li>
    <ul>
        <li>The loss for RNN tends to stabilize with less improvement over epochs.</li>
        <li>Loss values remain relatively higher compared to LSTM, suggesting that RNN struggles to minimize the loss effectively.</li>
    </ul>
</ul>

2. Train vs. Validation Loss
<ul>
<li>LSTM: </li>
    <ul>
        <li>The training loss decreases and validation loss remains fairly stable, indicating good generalization to unseen data.</li>
        <li>This shows that LSTM can better learn patterns without significant overfitting.</li>
    </ul>
<li>RNN: </li>
    <ul>
        <li>RNN shows a lack of significant improvement in validation loss, which suggests it might have higher variance or is failing to capture long-range dependencies.</li>
        <li>The gap between training and validation loss is less favorable, hinting at potential overfitting or underfitting issues.</li>
    </ul>
</ul>



