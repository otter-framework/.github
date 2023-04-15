# Otter Framework

Otter is a cloud native framework for peer-to-peer video communication within web applications.

[API Documentation](https://otter-framework.github.io/api-documentation/)

Otter was built with 3 objectives in mind:
1. to provision the infrastructure required for P2P video calling (i.e. Signaling, STUN/TURN servers)
2. to abstract away the complexity of interacting with such video calling infrastructure and the WebRTC API
3. to allow developers to easily integrate Otter into their applications

<img width="625" alt="Screenshot 2023-04-15 at 2 49 33 PM" src="https://user-images.githubusercontent.com/37469965/232254500-dade593e-87a6-4fe0-9c54-60488d85582d.png">

We segmented the architecture into groups of components that together fulfill these objectives. 

We call these groups stacks and we have 4 stacks.
- Signaling stack
- Stun/Turn stack
- Frontend stack
- API stack
