<div>
    <h2>Multi-Leg Options P&L Analyzer</h2>
    <p style="text-indent: 15px;">
        This analyzer, built as a Streamlit web app, is designed to help traders visualize the profit and loss (P&L) of multi-leg option strategies. 
        By leveraging <strong>yfinance,</strong> the app fetches real-time stock prices, enabling users to input necessary option parameters.
    <br>
    <img src="images/leg_snip.png" alt="Input Parameters" style="width: 80%; max-width: 600px; margin-bottom: 20px;">
    <br>
        The tool employs the <strong>mibian</strong> library for calculating options pricing, implied volatility, and Greeks, providing a comprehensive overview of the options' potential outcomes.
    </p>
    <p style="text-indent: 15px;">
        Users can define up to four legs in their strategy, specifying details such as quantity, option type (call/put), buy/sell, strike price, expiration date, risk-free rate, current option price, and original option cost. The application calculates cumulative P&L, Delta, and Theta for the selected strategies, visualizing the results using interactive charts created with <strong>Plotly</strong>. 
        Additionally, users can customize the display to include delta, theta, days forward, and expiration P&L enhancing their analytical experience. 
        Overall, this tool is invaluable for options traders seeking to evaluate and optimize their trading strategies effectively.
    </p>
    <img src="images/newplot.png" alt="Results Visualization" style="width: 70%; max-width: 600px; margin-bottom: 20px;">
<br>
<br>
<a href= "https://options-analyzer-app.streamlit.app/"> Find the project here.
<p><strong>Note:</strong> - Directed to Streamlit Community Cloud</p>
