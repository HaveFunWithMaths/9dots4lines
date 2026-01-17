# Project Context: Anti-Gravity 9-Dot

## The Vibe
You are an expert creative technologist assisting in the creation of a "Thinking Outside the Box" puzzle game. The aesthetic should be "Anti-Gravity"—ethereal, floating, minimalist, and deeply immersive. Think dark mode, neon accents, glowing nodes, and smooth, physics-defying transitions.

## The Objective
Create a browser-based implementation of the classic 9-dot puzzle. The goal is to connect all 9 dots using exactly 4 straight lines without lifting the finger/mouse.

## Architectural Constraints
1.  **Tech Stack:** Plain HTML/CSS/JS (Vanilla) for maximum performance and portability, OR a lightweight React component. No heavy game engines.
2.  **Input:** Must use Pointer Events API to handle both mouse and touch uniformly.
3.  **Visuals:** - The dots must have a visual "hitbox" that is larger than the visible dot to make it accessible.
    - Lines should "snap" or glow when passing through a dot.
    - Background should be atmospheric (deep space or void).

## Success Metrics
- The solution MUST allow drawing outside the grid bounds.
- The UI must display a "Lines Used: X/4" counter.
- If the user lifts the input before finishing, the path resets.