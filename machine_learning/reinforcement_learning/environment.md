# Environment

In [[reinforcement_learning]] an environment is something the [[agent]] interacts with. After each [[action]] taken by the agent, the environment returns a [[state]] / [[observation]] and a [[reward]].

Environments can be continuous of episodic. In episodic environments there is a terminal state, i.e. the number of actions within the environment is finite. Each episode in an episodic environment is independent of the other episodes.

In continuous environments, there is no terminal state, i.e. the agent has infinite actions in the environment.

The [[gym]] framework provides many environments for training RL agents.

## Environments

- https://github.com/maximecb/gym-minigrid
- https://github.com/maximecb/gym-miniworld
- https://github.com/duckietown/gym-duckietown
- https://github.com/openai/coinrun
- https://github.com/openai/procgen
- https://github.com/Unity-Technologies/obstacle-tower-env
- https://github.com/facebookresearch/nle/
- https://github.com/microsoft/TextWorld
- https://github.com/minqi/wordcraft
- https://andyljones.com/megastep/
- https://github.com/mwydmuch/ViZDoom
- https://github.com/deepmind/open_spiel
- https://github.com/zuoxingdong/mazelab (randomly generated mazes with solvers)
- https://github.com/enlite-ai/maze (more mazes)
- https://github.com/rosewang2008/gym-cooking (multi-agent collaborative cooking environment)
- https://github.com/deepmind/lab2d
- https://github.com/rajcscw/nlp-gym (nlp tasks with rl-type api)
- https://griddly.readthedocs.io/en/latest/ (lots of gridworld experiments, results @ https://wandb.ai/griddly)
- https://jsuarez5341.github.io/neural-mmo/build/html/rst/userguide.html (MMO environment)
