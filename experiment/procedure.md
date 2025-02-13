<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h2>1. Input Parameters</h2>
    <p>Provide the following inputs to run the simulation:</p>
    <ol>
        <li><strong>SNR (dB):</strong> Enter the desired signal-to-noise ratio in decibels.</li>
        <li><strong>Number of Multipaths:</strong> Input the number of multipath components in the channel to simulate Rayleigh fading.</li>
        <li><strong>Excess Delay (ms):</strong> Specify the delay experienced by each multipath in milliseconds.</li>
        <li><strong>Bit Rate (bps):</strong> Enter the bit rate of the message signal in bits per second.</li>
    </ol>
    <h2>2. Visualizing the Channel Effects</h2>
    <p>The simulator will process the input parameters and display how the original message signal is affected by Rayleigh fading and AWGN noise. The visualizations may include:</p>
    <h2>3. BER vs. SNR Comparison</h2>
    <p>The simulator will compute and plot the bit error rate (BER) for:</p>
    <ul>
        <li>The signal affected by <strong>Rayleigh fading + AWGN noise</strong>.</li>
        <li>The signal affected by <strong>AWGN noise only</strong>.</li>
    </ul>
    <p>These plots help compare the performance under different channel conditions.</p>
    <h2>4. Interpreting the Results</h2>
    <p>Review the output visualizations to understand the impact of Rayleigh fading and AWGN. Analyze the BER vs. SNR graph to observe signal quality under different conditions.</p>
    <h2>5. Adjusting Parameters</h2>
    <p>Modify the input values as needed to rerun the simulation with different settings. This allows you to observe how changes in SNR, multipaths, excess delay, and bit rate affect signal quality and BER.</p>
</body>
</html>
