---
description: "Integrate a portfolio navbar section into this Astro site"
agent: "agent"
argument-hint: "Use for the portfolio navbar section"
---
You are given a task to integrate an existing React component into this codebase for the portfolio navbar section.

This codebase is an Astro site with React support. It does not currently use the standard shadcn project structure, Tailwind CSS, or TypeScript everywhere by default. If the integration requires any of those, provide clear setup instructions first.

Determine the default path for components and styles.
- If the default component path is not `src/components/ui`, explain why creating `src/components/ui` matters for shared shadcn-style components and keep the structure consistent.
- If styles are not in a standard Tailwind setup, explain the minimum changes needed before using the component.

Copy-paste or adapt the component into the correct component directory, using a section-specific implementation for this portfolio site.

Use this navbar behavior for the portfolio section:
- Top-center navigation overlay outside the 3D canvas
- Items: Home, Projects, Experience, Skills
- Keep it visually separate from the lanyard/card scene
- Make it responsive for desktop and mobile
- Keep the component compatible with the current Astro + React setup

If the component uses external dependencies, install them and list them clearly.
For this task, required dependencies may include:
- motion
- lucide-react

Implementation guidelines:
1. Analyze the component structure and identify required dependencies.
2. Review props, state, hooks, and any required context providers.
3. If the codebase lacks Tailwind, shadcn, or TypeScript support, provide setup instructions before integration.
4. Use lucide-react icons where SVG icons are needed.
5. Make the navbar specific to the portfolio section instead of using generic demo labels like Pricing or Docs.

Questions to ask if anything is ambiguous:
- What data or props will be passed to this component?
- Are there any specific state management requirements?
- Are there any required assets or icons?
- What responsive behavior is expected?
- What is the best place to render this component in the app?

Steps to integrate:
0. Place the component in the correct component directory.
1. Install external dependencies.
2. Add or replace image assets only if the component truly needs them.
3. Use lucide-react icons for SVGs or logos where appropriate.
4. Mount the navbar in the portfolio page so it appears above the 3D scene.

Use the actual portfolio section names and layout from this site, not the demo labels from the original snippet.
