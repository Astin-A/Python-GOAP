# Python GOAP


## About GOAP

Goal-Oriented Action Planning is a generic architecture for autonomous AI.

By taking the current state of the AI (e.g.: Hungry? Tired?) and their desired state (e.g.: Not hungry? Not tired?) a "plan" is generated to take the AI from their current state to their goal state by considering a list of actions. By attaching weights to these actions, GOAP is capable of producing highly dynamic results.

## Example

See `example.py`.

By taking the current state of the AI (e.g.: Hungry? Tired?) and their desired state (e.g.: Not tired) a "plan" is generated to take the AI from their current state to their goal state by considering a list of actions. By attaching weights to these actions, GOAP is capable of producing highly dynamic results. In this case, the AI will discover that in order to sleep, they must first find and consume food, potentially leading to a complex course of action that involves going shopping, cooking, ordering pizza, taking a shower, etc.