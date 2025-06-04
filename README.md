# Rocket Boost

I'm thrilled to present **Rocket Boost**, my Unity 3D rocket piloting adventure—an exhilarating physics-based flight game where players master precise thrust and rotation controls to navigate treacherous obstacle courses, combining realistic rocket mechanics with challenging platforming gameplay.

---

## Gameplay & Mechanics

- **Realistic Rocket Physics:** Master thrust-based movement with authentic momentum and inertia—every boost matters, every rotation counts.
- **Precision Flight Controls:** Navigate using thrust for vertical movement and rotation for steering, creating a challenging skill-based control scheme.
- **Dynamic Obstacle Navigation:** Weave through oscillating platforms, spinning hazards, and environmental challenges that test piloting expertise.
- **Progressive Level Design:** Each stage presents unique flight challenges, from tight corridors to complex multi-path navigation puzzles.

---

## Interactive Systems & Feedback

- **Smart Collision Detection:** Tag-based system differentiates between friendly surfaces, finish lines, and deadly obstacles for varied gameplay responses.
- **Audio-Visual Excellence:** Immersive engine sounds, collision effects, and dynamic particle systems for thrust, rotation, and impact feedback.
- **Success & Failure States:** Celebration sequences for level completion and crash recovery systems that encourage players to retry and improve.
- **Environmental Interaction:** Moving platforms and oscillating obstacles create dynamic challenges that require timing and spatial awareness.

---

## Architecture & Input Systems

- **New Input System Integration:** Modern Unity Input Actions provide responsive, customizable controls for thrust and rotation with multi-device support.
- **Physics-Driven Movement:** Rigidbody-based locomotion using AddRelativeForce for authentic rocket behavior and realistic momentum conservation.
- **State Management:** Sophisticated control state system prevents input during crash/success sequences while maintaining clean game flow.
- **Component Separation:** Clear division between movement mechanics, collision handling, and environmental systems for maintainable code architecture.

---

## Advanced Features & Polish

- **Particle System Integration:** Multi-layered visual effects including main engine thrust, directional thrusters, success celebrations, and crash impacts.
- **Scene Management:** Seamless level progression with automatic next-level loading and crash recovery through intelligent scene indexing.
- **Debug & Development Tools:** Built-in cheat codes for level skipping and collision toggling to aid in development and testing workflows.
- **Oscillating Platforms:** Smooth mathematical movement patterns using Lerp and PingPong functions for predictable yet challenging obstacles.

---

## Technical Implementation

- **Physics-Based Design:** FixedUpdate timing ensures consistent physics calculations across different frame rates and hardware configurations.
- **Audio Management:** Intelligent sound layering prevents audio conflicts while providing rich feedback for all player actions and environmental interactions.
- **Rotation Mechanics:** Sophisticated rotation system with freeze/unfreeze patterns to prevent physics conflicts while maintaining smooth steering.
- **Performance Optimization:** Efficient particle management, audio pooling, and streamlined update loops maintain smooth 60fps gameplay.

---

## Player Experience & Flow

- **Skill-Based Progression:** Each level teaches new piloting techniques while building on previously mastered skills for satisfying learning curves.
- **Immediate Feedback:** Instant visual and audio confirmation of all player inputs creates responsive, engaging flight experience.
- **Retry-Friendly Design:** Quick restart mechanics and forgiving checkpoints encourage experimentation and skill development.
- **Accessibility Features:** Simple escape-key quit functionality and clear visual indicators make the game approachable for all skill levels.

---

## Reflections

Building **Rocket Boost** has been an incredible exploration of physics-based gameplay and precision control systems. The project demonstrates how thoughtful input design, realistic physics simulation, and polished audiovisual feedback combine to create engaging, skill-based challenges.

The modular architecture allows for easy expansion with new obstacle types, level mechanics, and flight challenges while maintaining clean, readable code. The integration of Unity's new Input System showcases modern development practices while the physics-driven approach creates genuinely satisfying rocket piloting experiences that reward player skill and persistence.

## Play Link
https://sayannandi.itch.io/rocket-boost

[![Watch the video](https://img.youtube.com/vi/AIq7QW8iHjo/maxresdefault.jpg)](https://youtu.be/AIq7QW8iHjo)
### [Gameplay Video](https://youtu.be/AIq7QW8iHjo)

![Image](https://github.com/user-attachments/assets/870eb7e1-96dd-4ef5-ae73-abc5ae8ae7ee)

![Image](https://github.com/user-attachments/assets/5f2a28e7-9cc5-4197-a0e2-5c8e05a2bb83)

![Image](https://github.com/user-attachments/assets/0802e131-f2f5-4741-8490-fbfe4b49325d)
