# GAME_PROGRAM-EX--1

# EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure

1. **Create a New Material:**
   - Open Unreal Engine.
   - In the Content Browser, right-click and select **Material**.
   - Name it `M_EffectsDemo`.

2. **Apply Base Color:**
   - Open the material.
   - Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

3. **Add Emissive Effect:**
   - Add a **Multiply** node.
   - Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
   - Connect the result to the **Emissive Color** input.

4. **Control Roughness:**
   - Add a **Scalar Parameter** node and connect it to the **Roughness** input.
   - Lower values = shinier surface, higher values = rougher surface.

5. **Control Metallic Property:**
   - Add a **Scalar Parameter** node and connect it to the **Metallic** input.
   - 0 = non-metal, 1 = fully metallic.

6. **Save and Apply Material:**
   - Save the material.
   - Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
  
     
## Output

<img width="1536" height="1024" alt="ChatGPT Image Nov 13, 2025, 01_34_14 PM" src="https://github.com/user-attachments/assets/c4756af5-a1c2-40a8-a90e-7937f2936df4" />


![image](https://github.com/user-attachments/assets/3aaea163-8335-42c9-af3c-46adac71cb00)



## Result
Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
