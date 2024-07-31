# Jax-Baseline

Jax-Baseline is a Reinforcement Learning implementation using JAX and Flax/Haiku libraries, mirroring the functionality of standard baselines.

## Features
- 2-3 times faster than previous Torch and Tensorflow implementations
- Optimized using JAX's Just-In-Time (JIT) compilation
- Flexible solution for Gym and Unity ML environments

## Installation

```
pip install -r requirement.txt
pip install .
```

## Implementation Status

- :heavy_check_mark: : Optional implemented
- :white_check_mark: : Defualt implemented at papers
- :x: : Not implemeted yet or can not implemented
- :zzz: : Implemented but didn't update a while (can not guarantee working well now)

### Supported Environments

| **Name**                | **Q-Net based**    | **Actor-Critic based** | **DPG based**      |
| ----------------------- | ------------------ | ---------------------- | ------------------ |
| Gymnasium               | :heavy_check_mark: | :heavy_check_mark:     | :heavy_check_mark: |
| MultiworkerGym with Ray | :heavy_check_mark: | :heavy_check_mark:     | :heavy_check_mark: |
| Unity-ML Environments   | :zzz:              | :zzz:                  | :zzz:              |



[^DQN]: [DQN](https://arxiv.org/abs/1312.5602v1)
[^DOUBLE]: [Double DQN paper](https://arxiv.org/abs/1509.06461)
[^DUELING]: [Dueling DQN paper](https://arxiv.org/abs/1511.06581)
[^PER]: [PER](https://arxiv.org/abs/1511.05952)
[^NSTEP]: [N-step TD](https://link.springer.com/article/10.1007/BF00115009)
[^RAINBOW]: [RAINBOW DQN](https://arxiv.org/abs/1710.02298)
[^NOISY]: [Noisy network](https://arxiv.org/abs/1706.10295)
[^MUNCHAUSEN]: [Munchausen rl](https://arxiv.org/abs/2007.14430)
[^APEX]: [Ape-X](https://arxiv.org/abs/1803.00933)
[^HL_GAUSS]: [HL-GAUSS](https://arxiv.org/abs/2403.03950)
[^C51]: [C51](https://arxiv.org/abs/1707.06887)
[^QRDQN]: [QRDQN](https://arxiv.org/abs/1710.10044)
[^IQN]: [IQN](https://arxiv.org/abs/1806.06923)
[^FQF]: [FQF](https://arxiv.org/abs/1911.02140)
[^SPR]: [SPR](https://arxiv.org/abs/2007.05929)
[^BBF]: [BBF](https://arxiv.org/abs/2305.19452)
[^A3C]: [A3C](https://arxiv.org/pdf/1602.01783)
[^PPO]: [PPO](https://arxiv.org/abs/1707.06347)
[^TPPO]: [Truly PPO](https://arxiv.org/abs/1903.07940)
[^IMPALA]: [IMPALA](https://arxiv.org/abs/1802.01561)
[^APPO]: [IMPALA + PPO, APPO](https://docs.ray.io/en/latest/rllib/rllib-algorithms.html#appo)
[^DDPG]: [DDPG](https://arxiv.org/abs/1509.02971)
[^TD3]: [TD3](https://arxiv.org/abs/1802.09477)
[^SAC]: [SAC](https://arxiv.org/abs/1812.05905)
[^TQC]: [TQC](https://arxiv.org/abs/2005.04269)
[^TD7]: [TD7](https://arxiv.org/abs/2306.02451)
[^LaP]: [LaP](https://arxiv.org/abs/2007.06049)
