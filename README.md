# Tsuro

---

Reinforcement learning environment based on Tsuro.

Implemented using OpenAI's gym wrapper for the environment itself and Pygame for the visuals.

---

There are 4 different versions:

### Tsuro(No Rotations Seen)
- The original implementation, has a fault with the observation space not giving agents details on the rotations of different cards.
### Tsuro(Rotations Seen)
- Observation space has a seperate matrix to track the rotations of the cards placed.
### Tsuro(With Rotations and Cards Merged)
- Similar to Tsuro(Rotations Seen) but rather than cards placed and rotations having seperate matricies, the values are combined and a single matrix formed.
### Tsuro(Reward System Change)
- Uses same observations as Tsuro(With Rotations and Cards Merged) but with an altered reward system just to see how it affects the ability for the agent to learn.

All 4 implementations utilise a very similar if not the same agent architecture, the architecture itself was not fully looked into, with only a few different variations trialled.

The saved versions of the agents are too big in size to upload to github but can be found here: 
https://www.dropbox.com/sh/df3cv0y21v8lgry/AAC-BwidXNepfrSShn-VE7bGa?dl=0

Replace the folders in the github download with the folders found at the link above to resume from where i left it.
