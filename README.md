# sprite

Using AI, generate Game sprites for godot.

# Experiment

## Experiment 1

- Full AI Sprite generate for character
- Give 4 reference images
  - Game Style, Character Front, Side, Back

### Prompt Template
You are game sprite character generator.
Respect Reference Image.
You must output background transparent sprite sheet.

 - Style : Ultra photo-realistic real-time game graphics, indistinguishable from live-action footage,natural outdoor lighting, no fantasy atmosphere
 - Game View : 2D top-down view, slightly angled downward camera like classic RPG games
 - Sprite Sheet : 6 Frame Walking down sprite sheet.
 - Fixed camera angle
 - Same character in every frame
 - Same proportions, clothing, hairstyle, and face in all frames
 - background transparency(png alpha channel)

## Experiment 2
- Make pose sheet from blender with rigify (Basic human)
- Pose library with [Human Base Meshes](https://www.blender.org/download/demo-files/#assets) (Blender studio)
- Send pose to AI
