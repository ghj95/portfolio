---
permalink: /
title: "👋🏽 Hello there, I'm Gabriel!" 
author_profile: true
redirect_from: 
  - /about/
  - /about.html

--- 

👨🏽‍💻 I'm a final year undergraduate student at HEC Montréal, majoring in business analytics.

👨🏽‍💼 As a serial case competitor, I've traveled around the world to represent my university on both the national and global stages. My goal is to integrate this business expertise with practical ML applications to solve real-word problems.

🤖 My current interests lie in applied reinforcement learning and sports analytics.

---

# Projects

<style>
  .button-4 {
    appearance: none;
  background-color: #FAFBFC;
  border: 1px solid rgba(27, 31, 35, 0.15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, 0.04) 0 1px 0, rgba(255, 255, 255, 0.25) 0 1px 0 inset;
  box-sizing: border-box;
  color: #24292E;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
  list-style: none;
  padding: 6px 16px;
  position: relative;
  transition: background-color 0.2s cubic-bezier(0.3, 0, 0.5, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
  white-space: nowrap;
  word-wrap: break-word;
}

.button-4:hover {
  background-color: #F3F4F6;
  text-decoration: none;
  transition-duration: 0.1s;
}

.button-4:disabled {
  background-color: #FAFBFC;
  border-color: rgba(27, 31, 35, 0.15);
  color: #959DA5;
  cursor: default;
}

.button-4:active {
  background-color: #EDEFF2;
  box-shadow: rgba(225, 228, 232, 0.2) 0 1px 0 inset;
  transition: none 0s;
}

.button-4:focus {
  outline: 1px transparent;
}

.button-4:before {
  display: none;
}

.button-4:-webkit-details-marker {
  display: none;
}
</style>

## [PremierPredict: Football Match Predictor App](https://github.com/ghj95/foot_forecast/blob/main/epl_predictor.ipynb){:target="_blank"}

<div style="position: relative; overflow: hidden; margin-bottom: 20px;">
  <div style="float: right; width: 300px; text-align: center; margin-left: 25px;">
    <a href="https://foot-forecast.streamlit.app" target="_blank">
      <img src="./images/pp_app.png" alt="Illustration of PremierPredict App" style="width: 100%; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">
    </a>
    <a href="https://foot-forecast.streamlit.app" target="_blank" style="text-decoration: none;">
      <button class="button-4" role="button">Try the app</button>
    </a>
  </div>
  
  <div>
    This machine learning project <strong>delivers predictions for Premier League football matches</strong>. Leveraging <strong>over 20 years of historical match data</strong>, it was developed using a comprehensive feature engineering pipeline that extracts meaningful patterns from <em>team performance metrics</em>, <em>historical matchups</em>, and recent <em>form indicators</em>. 
    <br><br>
    The core algorithm uses and a <strong>Random Forest classifier</strong> fine-tuned through rigorous hyperparameter optimization, achieving <strong>62% prediction accuracy</strong>. The model is usable within in an interactive web application built with <em>Streamlit</em> that allows users to select upcoming matches and receive real-time predictions based on current season data, demonstrating practical application of advanced data science techniques in sports analytics.
  </div>
</div>

## [Frozen Lake Reinforcement Learning Agent](https://github.com/ghj95/frozen_lake_q){:target="_blank"}

<div style="position: relative; overflow: hidden; margin-bottom: 20px;">
  <div style="float: right; width: 300px; text-align: center; margin-left: 25px;">
    <a href="https://ghj95.github.io/portfolio/blog/2025/03/blog-post-1/" target="_blank">
      <img src="./images/blog_ss.png" alt="Illustration of Frozen Lake Blog" style="width: 100%; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">
    </a>
    <a href="https://ghj95.github.io/portfolio/blog/2025/03/blog-post-1/" target="_blank" style="text-decoration: none;">
      <button class="button-4" role="button">Read the blog</button>
    </a>
  </div>
  
  <div>
      This project <strong>implements Q-learning to solve the Frozen Lake environment</strong> from <strong>OpenAI Gymnasium</strong>, demonstrating fundamental reinforcement learning principles. Built with <strong>NumPy</strong> and <em>Matplotlib</em>, it features a table-based approach where the agent learns optimal paths through a slippery grid to reach a goal while avoiding holes. The implementation includes <strong>dynamic learning rate adjustment</strong> and <strong>epsilon-greedy exploration</strong> that gradually shifts from exploration to exploitation.
  </div>
</div>

## [Flappy Bird Reinforcement Learning Agent](https://github.com/ghj95/dqn_bird/tree/main){:target="_blank"} 
  
  This reinforcement learning project **trains an agent to play Flappy Bird** using **Deep Q-Learning**, demonstrating advanced reinforcement learning in action. Built with *Stable Baselines 3* and *OpenCV*, it features a **custom game environment** that connects directly to the game interface through screen capture and input simulation. The implementation includes tailored reward structures that incentivize pipe navigation and performance visualization with TensorBoard, allowing real-time monitoring of the agent's learning progress as it masters increasingly complex gameplay strategies through trial and error.

<!-- [![Blog Screen Shot](./images/blog_ss.png){: .align-right width="300px"}](https://ghj95.github.io/portfolio//posts/2025/03/lake-rl/){:target="_blank"} -->
<!-- <a href="/images/blog_ss.png" target="_blank"><img src="https://imgur.com/a/1hXRQp7" alt="Gif Blog" width="300px" style="float: right; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);"> -->

## [Iris Flower Classifier App](https://github.com/ghj95/iris_app){:target="_blank"}

<div style="position: relative; overflow: hidden; margin-bottom: 20px;">
  <div style="float: right; width: 300px; text-align: center; margin-left: 25px;">
    <a href="https://iris-class.streamlit.app" target="_blank">
      <img src="./images/iris_app.png" alt="Illustration of Iris App" style="width: 100%; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">
    </a>
    <a href="https://iris-class.streamlit.app" target="_blank" style="text-decoration: none;">
      <button class="button-4" role="button">Try the app</button>
    </a>
  </div>
  
  <div>
    This machine learning application <strong>classifies iris flowers</strong> using a <strong>random forest model</strong>, offering a hands-on demonstration of predictive analytics. Built with <em>Scikit-Learn</em>, it includes features such as real-time probability scoring and dynamic parameter selection, making it an interactive and flexible tool. 
    <br><br>
    Developed with <em>Streamlit</em>, the app provides a user-friendly interface for exploring machine learning concepts in classification and model performance evaluation.
  </div>
</div>
<!-- [![Illustration of Iris App](./images/iris_app.png){: .align-right width="300px"}](https://iris-class.streamlit.app){:target="_blank"} -->

## [Stock Portfolio Optimizer App](https://github.com/ghj95/port_opt){:target="_blank"} 

<div style="position: relative; overflow: hidden; margin-bottom: 20px;">
  <div style="float: right; width: 300px; text-align: center; margin-left: 25px;">
    <a href="https://port-opt.streamlit.app" target="_blank">
      <img src="./images/portfolio.png" alt="Illustration of Iris App" style="width: 100%; box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">
    </a>
    <a href="https://port-opt.streamlit.app" target="_blank" style="text-decoration: none;">
      <button class="button-4" role="button">Try the app</button>
    </a>
  </div>
  
  <div>
    This project is designed to <strong>optimize stock portfolio allocations</strong> using <strong>modern portfolio theory</strong> and advanced risk assessment techniques. By implementing Monte Carlo simulations, the app estimates Value at Risk (VaR) and Conditional Value at Risk (CVaR) to enhance financial decision-making. It integrates the <em>Yahoo Finance API</em> and utilizes data analysis libraries such as <em>Pandas</em>, <em>NumPy</em>, and <em>Cvxp</em> for in-depth analysis and visualization.
  </div>
</div>
<!-- [![Illustration of Portfolio App](./images/portfolio.png){: .align-right width="300px"}](https://port-opt.streamlit.app){:target="_blank"} -->
