# SEI ONE: Kling.AI Prompt Execution Directive
**Specification Standard: SEI-ONE-PROMPT-KLING-v1.0**

This directive standardizes prompt schemas for generating spatial entity integrations within the Kling.AI generative framework under the SEI ONE specification.

---

## Technical Directives

| Variable | Specification Source | Direct Value Mapping |
| :--- | :--- | :--- |
| `CAMERA_RIG` | `spec/geometry.json` | 24mm wide-angle lens, 25° elevation tilt, 0.4m lens height |
| `SPATIAL_ANCHOR` | `manifests/domus-mare.json` | Cantilevered container overhang, raw concrete plinth, ocean horizon |
| `LIGHTING_TEMP` | `spec/lighting.yaml` | 3000K warm stairwell/interior LEDs vs. 7500K twilight sky fill |
| `MATERIAL_PAIRING` | `spec/materials.json` | High-gloss synthetic latex against matte cast concrete & corrugated steel |

---

## Standardized Production Prompt

```text
[SEI_ONE_EXECUTION] Cinematic high-fashion architectural integration. Extreme low-angle perspective (25-degree elevation, 24mm lens) looking upward from the base of illuminated concrete steps. Foreground feature: an imposing elite synthetic female model in high-gloss black latex suit, centered on the landing. The dark corrugated steel container structure from Domus Mare looms directly above as a ceiling canopy. Dual-mapped lighting: sharp 3000K warm specular reflections along the latex surfaces from embedded stair-step LEDs, balanced against cool 7500K twilight sky ambient fill. Photorealistic material friction, high specular contrast, 8k resolution.
overexposed interior, flat lighting, daylight, eye-level perspective, blurry reflections, low resolution, warped architectural geometry
