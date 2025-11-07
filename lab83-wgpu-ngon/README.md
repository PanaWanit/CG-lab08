## WGPU N-GON

Based on the hello-triangle demo. Implement your Lab 1 N-GON using wgpu.

### Features
- Interactive N-sided polygon renderer using WGPU
- Colorful gradient with HSV color interpolation
- Dynamic polygon generation based on number of sides
- Keyboard controls to increase/decrease sides

### Controls
- **Up Arrow / Plus / Equals**: Increase number of sides
- **Down Arrow / Minus**: Decrease number of sides (minimum 3)

### Running
```bash
cargo run
```

### Implementation Details
- Starts with a hexagon (6 sides)
- Each polygon is composed of triangular segments radiating from the center
- Colors are interpolated using HSV to RGB conversion for a rainbow effect
- White center vertex with colored perimeter vertices