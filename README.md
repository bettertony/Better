## Better

Intelligent Advisors Trading Platform

This is the orinal implementation of our paper, A Deep Reinforcement Learning Algorithm for Financial Portfolio Management, together with a toolkit of portfolio management research.

* The deep reinforcement learning Algorithm is the core part of the library.
The method is basically the policy gradient on immediate reward.
 One can configurate the topology, training method or input data in a separate json file. The training process will be recorded and user can visualize the training using tensorboard.
Result summary and parallel training are allowed for better hyper-parameters optimization.
* The financial-model-based portfolio management algorithms are also embedded in this library for comparision purpose, whose implementation is based on Li and Hoi's toolkit [OLPS](https://github.com/OLPS/OLPS).

## Dependencies
Install Dependencies via `pip install -r requirements.txt`

* tensorflow (>= 1.0.0)
* tflearn
* pandas
* zipline

## User Guide
Please check out [User Guide](user_guide.md)

## Acknownledgement
This project would not have been finished without using the codes from the following open source projects:
* [Online Portfolio Selection toolbox](https://github.com/OLPS/OLPS)

## Future Plan
* Bug fixing
* Interfacing to other markets such as stock, futures, options
* Adding broker API (under `marketdata`)
* More backtest strategies (under `tdagent`)

