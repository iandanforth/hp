# hp
Homeostatic Primitives 

# States, Control, and Optimal Control

Biological creatures require the maintenance of internal and external states to maintain their life processes. If these states veer outside of critical ranges for any extended period of time the organism may die. For example an animal that is unable to breathe in or otherwise process sufficient oxygen will rapidly asphyxiate, whereas excess oxygen can also lead to death via damage to the pulmanory and nervous systems.

The behaviors of organisms which serve to regulate essential states can be considered part of a class of control mechanisms. The vast majority of them fall into the category of closed loop controls. Through complex biological mechanisms the organism is able to monitor essential states and initiate behavior to attempt to control those states, adjusting the behavior based on the continually monitored states.

It is unclear what proportion of control behehaviors in organisms fall into the category of 'optimal control.' Optimal control is "control for a dynamical system over a period of time such that an objective function is optimized." While it is clear that some behaviors or behavioral strategies may be superior to others in maintaining essential states, it is unclear if biological mechanisms also try to optimize an objective function when selecting behaviors. For example, it might be the case that minimizing energy expenditure in control behaviors might be a common objective function, however it is not clear that such objectives are universal or even consistently applied during the process of reestablishing essential states within critical ranges.

Given that a large and varied set of biological behavior is either directly instigated by or serves the purpose of regulating essential states, we can imagine that researchers may benefit from a concise package of tools for developing and testing control strategies in the context of learning agents.

Moreover the relation of those fundamental control strategies to a set of one or more artificial essential states, implemented as a reusable set of primitives can benefit both experiment and discussion.

This is the aim of this library.