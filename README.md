# TSP-Ant-Colony
Solving TSP problem using Ant colony optimizer.


## Usage
Just define your function and call Optimizer with your configuration, and then train it.
```python
colony = Colony(ant_num = 20, 
                matrix = test ,
                base_formun = 10, 
                T_SA = 1, 
                SA_rate = 0.9, 
                beta = 10, 
                p_local = 0.4, 
                alpha = 0.2,
                q_0 = 0.7
               )
cost_history ,path_history = colony.training(50)
```
# Learning plot
![image](https://user-images.githubusercontent.com/54745174/148154282-68d8a175-111f-4e23-94ba-dc5001946d0d.png)



## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
