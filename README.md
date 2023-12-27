# Python GOAP


## About

This is a Python implementation of GOAP (Goal-Oriented Action Planning), a
generic architecture for autonomous AI.

GOAPy was written in 2014 and updated in 2019 to work with Python 3. It predates
other libraries of the same name and is not to be confused with `GOApy`.

GOAPy is simple in design and can be set up with only a few lines of code. It
supports weighted actions and has debug text for tracking planner outcomes.


## Example

See `example.py`.

By taking the current state of the AI (e.g.: Hungry? Tired?) and their desired state (e.g.: Not tired) a "plan" is generated to take the AI from their current state to their goal state by considering a list of actions. By attaching weights to these actions, GOAP is capable of producing highly dynamic results. In this case, the AI will discover that in order to sleep, they must first find and consume food, potentially leading to a complex course of action that involves going shopping, cooking, ordering pizza, taking a shower, etc.