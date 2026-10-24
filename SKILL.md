---
name: xxd-panel-196
description: "XXD Panel 196｜Top-down Geometric Figure Vignette: redraws the people in a photo as minimal geometric figures seen from directly above — heads, bodies, clothes and limbs compressed into circles, ovals, half-circles, capsules and a few organic colour blocks that keep each person's identity, pose and direction — in flat colour with no modelled shading, each with a faint soft shadow beneath. The small figures sit off-centre, scattered or cropped in wide empty space, coloured with the brightest hues of the photo (sky blue, lake teal, fresh green, warm yellow, coral, peach pink) on clean warm white, with a few small, light words. The style is built around human figures. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-196 or asks for top-down, bird's-eye geometric or Bauhaus-like figure illustration from a photo of people."
---

# XXD Panel 196

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

This source brief specifically requires human figures. If the source photograph has no person, resolve suitability before generation; do not invent a person or silently generalise the aesthetic to objects.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-196/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-196-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
