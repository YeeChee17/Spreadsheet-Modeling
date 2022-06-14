# Spreadsheet-Modeling
Build sound spreadsheet models to solve business problems, and then draw meaningful insight from those models.

## Simulations in Marketing
1. Forecasting Sales of New Product

    When new product enters the market, people want to get some idea about how rapidly it might gain market share. Bass Diffusion Model model might be useful. The number of adopters and new adopters follows the charts below (charts from wikipedia):
![image](https://user-images.githubusercontent.com/102925575/173689354-e9a6555d-69e6-4531-8124-63281364f528.png)

    Equation:
    n(t) = [p + q x (N(t)/N0)] * [N0 - N(t)]
    
    Where:\
    n(t) = new customers adopting at time t \
    N0	 = total market size of potential users \
    N(t) = cumulative adopters up to time t-1 \
    p	 = coefficient of innovation \
    q	 = coeffecient of imitation

Base Model:
![image](https://user-images.githubusercontent.com/102925575/173697707-19d06c9b-e632-49d7-9cd1-01096d5de4b1.png)

Simulation Model:
![image](https://user-images.githubusercontent.com/102925575/173701164-1ea6047a-88ee-44ec-8f18-f22b0f057539.png)

Read Further about Bass Diffusion Model: 
- [Wiki](https://en.wikipedia.org/wiki/Bass_diffusion_model)
- [entertainmentstrategyguy.com](https://entertainmentstrategyguy.com/2019/09/11/the-bass-diffusion-modelexplained-the-most-important-shape-of-the-streaming-wars/)

3. Estimating Value of Customer
