```hlsl
// @solrmax

struct Profile {
    float3 focus;      // shaders, gpu_compute, animation
    float3 position;   // graphics_programming
    float experience;  // constantly_learning
};

Profile main() {
    Profile me;
    me.focus = normalize(float3(1, 1, 1));
    me.position = float3(rendering, optimization, experimentation);
    me.experience = lerp(learning, mastery, time);
    return me;
}
```

## Focus

Graphics programming, real-time rendering, and shader development.

Working with compute shaders, GPU-accelerated algorithms, and procedural animation systems.

## Stack

```hlsl
// Primary
C# + Unity
GLSL/HLSL/ShaderLab
Compute Shaders

// Secondary  
Unreal Engine 5 + Blueprints
C++ (embedded, engine experiments)
JavaScript (web tools, backend)
```

[//]: # (## Projects)

[//]: # ()
[//]: # (**[Ray-Tracing-Extended]&#40;https://github.com/solrmax/Ray-Tracing-Extended&#41;**  )

[//]: # (Real-time GPU path tracing experiments. Extended Sebastian Lague's raytracer with custom features.  )

[//]: # (`compute` `raytracing` `BVH` `Unity`)

[//]: # ()
[//]: # (**[Qshmup]&#40;https://github.com/solrmax/Qshmup&#41;**  )

[//]: # (Bullet hell shmup with custom rendering pipeline. GPU-driven particle systems and procedural VFX.  )

[//]: # (`shaders` `GPU instancing` `particles` `Unity`)

[//]: # ()
[//]: # (**[NetworkedInvaders]&#40;https://github.com/solrmax/NetworkedInvaders&#41;**  )

[//]: # (Multiplayer space invaders. Client prediction, server reconciliation, interpolation.  )

[//]: # (`networking` `multiplayer` `Node.js` `Unity`)

[//]: # ()
[//]: # (**[smart-rex-c100]&#40;https://github.com/solrmax/smart-rex-c100&#41;**  )

[//]: # (ESP32 web server for PID temperature controller. Embedded systems side project.  )

[//]: # (`ESP32` `C++` `embedded` `web server`)

## Currently Learning

```hlsl
float3 learning = float3(
    sdf_raymarching,
    compute_optimization,
    unreal_engine_5-7
);
```

Advanced SDF techniques, compute shader optimization patterns, custom render pipelines.

## Links

[solrmax.github.io](https://solrmax.github.io)

[layar.itch.io](https://layar.itch.io/)

```hlsl
// EOF
```
