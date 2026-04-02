# Zoro Lamp demo

A shadow projection lamp template featuring Roronoa Zoro from One Piece. This project contains the vector graphics needed to construct an interlocking four-wall lamp structure. When properly assembled and illuminated, it casts a specific and detailed shadow based on the provided source image.

## Directory Structure

- **`source-image/`**
  - `onepiece.png`: The original reference image used to generate the lamp's shadow templates.
- **`svg/`**
  - Contains the vector files (`.svg`) for the four walls. These are ready for laser cutting or CNC machining.
  - `ShadowEngine_Back_Wall_Vector.svg`
  - `ShadowEngine_Front_Wall_Vector.svg`
  - `ShadowEngine_Left_Wall_Vector.svg`
  - `ShadowEngine_Right_Wall_Vector.svg`
- **`spec.txt`**
  - Contains the configuration and optical specifications required for the lamp setup.

## Project Specifications

To achieve the optimal intended shadow projection, ensure that your physical light source and environment match the specifications defined in `spec.txt`:

- **Shadow Width**: 136.9 cm
- **Shadow Length**: 123.9 cm
- **Light Source Height**: 15 cm 

## Assembly Instructions

1. **Cut the Panels**: Use a laser cutter, CNC machine, or vinyl cutter to cut the four SVG files in the `svg/` directory from an opaque material (such as plywood, MDF, acrylic, or heavy cardstock).
2. **Assemble the Walls**: Connect the Front, Back, Left, and Right walls to form the primary lamp housing.
3. **Position the Light Source**: Place a single-point bright LED or bulb inside the assembly. Adjust its vertical position so that its emitting point is exactly **15 cm** in height from the base.
4. **Project**: Place the lamp in a darkened room. The interplay of the cutouts and the light source will project a shadow roughly **136.9 cm by 123.9 cm** around the room.

## Note
For the sharpest shadows, it is highly recommended to use a single-point LED (like a COB LED or an LED with the dome removed) rather than a regular frosted lightbulb, which can cause blurry shadow edges.
