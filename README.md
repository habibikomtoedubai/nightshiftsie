🌙 NIGHTSHIFT - 100 Features & Technical Overview
🌌 1. Game Concept & Lore (1-10)
Atmospheric Horror: A dark, tense, and claustrophobic survival-horror experience.

Threat in the Dark: The main antagonist, the mysterious Shadow Stalker.

Night Shift Theme: A struggle for survival during a dangerous night shift.

Exploration & Tension: High tension created by limited visibility and dynamic audio.

Visual Concept: A creature design made of complex, tendon-like dark fibers.

Dark Environment: An abandoned, eerie, and unsettling 3D facility/setting.

Psychological Pressure: Constant fear of ambush paired with resource management.

Listen & Hide: Locating the creature using sound cues.

Minimalist HUD: Clean interface allowing full immersion in the atmosphere.

Pure Survival: Focus on hiding and timing rather than direct combat.

🎮 2. Gameplay Mechanics (11-30)
First-Person View (FPS): Immersive camera perspective.

Movement System: Walking, sprinting, and crouching mechanics.

Stamina Management: Realistic fatigue system limiting continuous running.

Stealth Mechanics: Crouching to move quietly and avoid detection.

Interaction System: Interacting with doors, keys, and objects.

Flashlight / Light Source: Battery-powered light source for dark areas.

Battery Drain: Flashlight power decreases over time, requiring new batteries.

Sound Detection: Enemy reacts to footstep noise made by the player.

Hiding Spots: Hiding inside lockers, under desks, or in dark corners.

Head Bobbing: Realistic camera movement while walking and running.

Inventory System: Collecting items and keys required to progress.

Field of View (FOV): Adjustable FOV settings for player comfort.

Objective List: Step-by-step tasks to complete in the facility.

Locked Doors: Keycard and key locking mechanisms.

Danger Indicators: Screen distortion or audio cues when the creature is near.

Realistic Physics: Smooth jump and falling physics.

Dual Interaction: Ability to interact with objects while holding a flashlight.

Anxiety System: Increased heartbeat and screen blur when spotted.

Chasing Thrill: High-speed escape moments in narrow corridors.

Quick Restart: Fast respawn to the last checkpoint upon capture.

🤖 3. Shadow Stalker (Enemy & AI) (31-50)
Custom Armature Structure: Unique skeleton built from dense dark fibers.

Quadrupedal / Hunched Stance: Menacing and non-humanoid pose.

Extended Limbs: Extremely long arms, legs, and sharp claw bones.

Dynamic AI: Smart navigation using Godot's NavMesh system.

Patrol State: Wandering predefined routes across the map.

Search State: Investigating suspicious sounds created by the player.

Chase State: Accelerating towards the player upon visual contact.

Line of Sight: Detection cone based on creature vision.

Hearing Sense: Sound detection for running or dropped objects.

Glowing Eyes: Two bright white glowing eyes targeting in the dark.

Custom Attack Animations: Unique kill sequence upon catching the player.

Jumpscare Mechanics: Sudden attack triggers to surprise the player.

Animation Blending: Smooth transitions between walking, running, and idle states.

Tendon / Fiber Effects: Web-like shadow textures and materials.

Light Sensitivity: Flashlight causing momentary stuns or retreats.

Spatial Audio Cues: Growls and footsteps heard behind walls.

Quick Maneuvers: Fast turns in narrow spaces due to long limbs.

Unpredictable AI: Randomized decision-making to prevent pattern memorization.

Obstacle Avoidance: Navigating around tables and walls smoothly.

High Lethality: One-hit capture system for intense stakes.

🛠️ 4. Engine & Technical Setup (Godot 4 & Blender) (51-70)
Godot Engine 4: Built on modern game engine architecture.

GDScript Language: Clean, fast, and optimized codebase.

CharacterBody3D: Physics-based 3D character controller.

Blender 3.6 LTS: 3D modeling and rigging pipeline.

Manual Rigging: Handcrafted Armature and Bone structure for the creature.

GLTF / GLB Export: High-compatibility model pipeline into Godot.

CollisionShape3D: Precise collision bounds and physics shapes.

Skeleton3D & Attachments: Bone-based attachment points in Godot.

Volumetric Lighting: Realistic fog and light beams breaking the dark.

Dynamic Shadow Mapping: Real-time dynamic shadows.

WorldEnvironment Node: Custom fog, darkness, and tonemapping setups.

3D Spatial Audio: Environmental 3D audio via AudioStreamPlayer3D.

VoxelGI / SDFGI: Modern global illumination techniques in Godot 4.

Inverse Kinematics (IK): Limb adaptation for smooth floor placement.

Modular Scene Architecture: Clean separation of scripts and scenes.

Performance Optimization: Efficient low-poly models for performance.

Custom Shaders: Specialized visual shaders for shadow effects.

Signal-Driven Architecture: Event-driven GDScript design pattern.

Clean Scene Tree: Organized node hierarchy for easy maintenance.

Cross-Platform Readiness: Optimized for Windows PC performance.

🎨 5. Visuals, Audio & Atmosphere (71-85)
Cinematic Color Palette: Dark greys, deep blacks, and cool blue tones.

High Contrast: Deep shadows paired with sharp light sources.

Dark Textures: Metallic, rusty, and wet surface materials.

Dense Fog Effect: Atmospheric fog reducing maximum visibility.

Ambient Audio: Eerie background drones and wind soundscapes.

Surface-Based Footsteps: Distinct footstep sounds for wood, metal, and concrete.

Creature Audio Library: Custom growls, shrieks, and heavy footsteps.

Flickering Lights: Broken hallway lighting adding unpredictability.

Post-Processing: Subtle bloom, chromatic aberration, and film grain.

Particle Systems: Dust particles floating in light shafts.

Horror-Themed UI: Dark, minimalistic interface design.

Dynamic Music Intensity: Music escalates as the creature draws near.

Surface Reflections: Realistic light reflections on wet floors.

Focal Lighting: Strategic light placement to guide the player.

Silhouettes: Spine-chilling creature silhouettes in dark corridors.

🚀 6. Project Roadmap & Future Plans (86-100)
Open Source Development: Modular code available for community review.

Version Control: Organized GitHub repository with regular commits.

Advanced AI Upgrades: Enhanced searching logic for hidden players.

New Map Sections: Additional floors and outdoor areas.

Interactive Puzzles: Repairing power grids to open doors.

Environmental Lore: Notes, audio logs, and diaries scattered around.

New Entity Types: Additional shadow variants in future updates.

Audio Settings: Independent volume controls for FX and music.

Graphics Settings: Quality toggles and FPS limiters.

In-Game Achievements: Rewards for surviving under difficult conditions.

Gamepad Support: Full controller support planned.

Localization: Multi-language support (English, Turkish, Dutch).

Key Binding: Custom control mapping system.

Community Feedback: Game balance adjustments based on playtests.

Indie Passion Project: A unique horror project built with dedication.
