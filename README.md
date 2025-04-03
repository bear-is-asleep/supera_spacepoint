## Supera Spacepoint Parameters Evaluation

[spacepoint_params.ipynb](spacepoint_params.ipynb) Contains the code for the evaluation of the spacepoint parameters. Production is covered in [supera_spacepoint_prod](https://github.com/bear-is-asleep/supera_spacepoint_prod) It also contains an event display to visualize the completeness metric. This will create plots that evaluate the completeness of tracks, and purity and efficiency of the spacepoint making. 

Once a set of parameters is selcted, you can make some evaluation logs to evaluate the performance of the parameters. Example plots for SBND can be found in [SBND_SP_2025_02_28](assets/SBND_SP_2025_02_28.pdf). Around 1k events is ideal. The logs are made using one of the `.cfg` files in the repo. The evaluation metrics are made using [evaluation.ipynb](evaluation.ipynb).

