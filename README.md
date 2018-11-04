# DRLND-Navigation

## 1. Environment information

This banana environment has 37 observation vectors and 4 discrete action space.

You can solve this environment with DQN-based agent.

## 2. Installation & Running the Training Code

1. Run this code to install all of dependencies.

   ```bash
   source activate VIRTUAL_ENV_NAME # Run this line if you work with virtual env
   pip install requirements.txt # Install the dependencies from requirements.txt
   ```

2. Download Udacity banana environment from below site.

- Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip

- Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip

- Windows: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip (for 32bit)

  ​                 https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip (for 64bit)

3. Change the path `Banana_Windows_x86_64\\Banana.exe` to your Banana environment path in `Navigation.ipynb` file.
4. Run all blocks in `4. It's Your Turn!` to train your model
5. Enjoy a well-trained model by running `4-4-2` code cell!

## 3. Review my Model

My banana agent was trained by DQN agent which has dense layers to approximate the Q function.

You can choose other model like Double DQN, Dueling DQN, and so on.

Below is my agent's reward curve during training.

[이미지 첨부]

- My agent got approx.  reward almost by the end.
- This environment was solved in 2500 steps

## 4. Furthur Work

- Implement Double DQN or Dueling DQN for this project
- Use DQN in other environments, such as atari Breakout or Pong
