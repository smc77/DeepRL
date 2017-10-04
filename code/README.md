# Example code for deep reinforcement learning

These scripts provide examples of using OpenAI gym with reinforcement learning agents.

```
brew install tmux htop cmake golang libjpeg-turbo      # On Linux use sudo apt-get install -y tmux htop cmake golang libjpeg-dev

pip install "gym[atari]"
pip install universe
pip install six
pip install tensorflow
```

You can run the pong example from the command line:

```
python pong_from_pixels.py --render True
```