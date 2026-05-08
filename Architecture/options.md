# Component Classes

The first architecture we considered was Component-Based Architecture, as we believed it would be the easiest and most reliable choice for implementation. This approach allows us to add components to different weapons and characters with flexibility and efficiency. It also supports a smoother workflow throughout the project and improves communication within the team, as one person can work on a specific component while another focuses on a different one simultaneously.
<img width="702" height="446" alt="72ff6b24751db3807c5d32607a301d2984273a27" src="https://github.com/user-attachments/assets/cb29c956-d474-4c8d-9d2c-ee9448d36f5d" />

## Event-driven 
we could also consider event-driven architecture this approach works by having different systems communicate through events, For example, when a player fires a weapon, an event could be triggered that tells the audio system to play a sound, the animation system to play recoil animations, and the damage system to calculate hits. This makes the project more modular and easier to expand as new features are added. this would be implemented if the scope of our project was on a larger scale and was heavily relaiant on actions of the player for this reason we believe this does not fit the brief our client has provided us.

### Layered
Layered architecture is quite similar to component where the team could work on different tasks simultaneously however this would be more a kin to a 2d project as it heavily relies on the interface for its structure kind of working in the same regard to a paint software the game would be made with layers upon layers 
this is one could work but because its limitations in a 3d space I would not recommend this choice.1
