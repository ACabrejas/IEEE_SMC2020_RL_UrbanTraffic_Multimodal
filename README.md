# Multimodal Optimisation for Reinforcement Learning in Urban Traffic Control
Optimisation of Traffic Signal Control Systems is an important real-world challenge that has direct impact on the economy and quality of life of urban areas.Recently, Reinforcement Learning is proving to be a successful tool that can effectively manage urban intersections with a fraction of the effort required to curate traditional Urban Traffic Controllers. 

This paper adds on the authors' previous work, performing a robust comparison between 30 different Reinforcement Learning reward functions for controlling intersections serving vehicles and pedestrians. We use a calibrated model in terms of demand, sensors, green times and other operational constraints of a real intersection in Greater Manchester, UK. 
Sensory inputs are restricted to what can be achieved with current vision-based sensors, such as those from Vivacity Labs.
The rewards can be broadly classified in 5 groups depending on the magnitudes used: queues, waiting time, delay, average speed and throughput in the junction. The performance of different agents, in terms of waiting time, is compared across different demand levels ranging from normal operation to saturation of traditional adaptive controllers.

We find that those rewards maximising the speed of the network obtain the lowest waiting time for vehicles and pedestrians simultaneously, closely followed by queue minimisation, demonstrating better performance than other methods proposed in the literature.

![] (figures/9grid_ordered_boxplot_all-page-001.jpg)

![] (figures/table_results.PNG)
