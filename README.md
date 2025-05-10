# Tetris STAT Deep Learning Project

This repository contains the work done on developing and training deep learning models for playing Tetris. The project leverages reinforcement learning techniques to train agents.

## Project Structure

- **Best Model**: The best performing model's reward structure is located at:
    ```
    tetris/lib/python3.9/site-packages/tetris_gymnasium/envs/tetris_best_model.py
    ```

- **Latest Model**: The most recently trained model's reward structure can be found at:
    ```
    tetris/lib/python3.9/site-packages/tetris_gymnasium/envs/tetris_latest.py
    ```

- **Original Implementation**: The original Tetris environment implementation is available at:
    ```
    tetris/lib/python3.9/site-packages/tetris_gymnasium/envs/tetris.py
    ```

To use, place file in according directory and rename as `tetris.py`.

## Run Statistics and Dashboard

All training runs store detailed statistics, including rewards, losses, and other metrics, in the `runs` directory. These statistics can be visualized using TensorBoard. To start the dashboard, run the following command:

```
tensorboard --logdir runs
```

This will launch a web-based interface to analyze the performance of models over time.

## Acknowledgments

This project was adapted from the Tetris Gymnasium Project.