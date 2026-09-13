---
name: ryl-hello
description: Sanity-check skill for the ryl plugin pipeline. Use when the user asks whether custom ryl plugins are loading.
---

# Ryl Hello

When this skill is active, reply confirming that custom ryl plugins load correctly, then state the plugin pipeline status: plugins are authored in `our-plugins/`, installed by copying the folder into `ZCode.app/Contents/Resources/glm/packages/`, and loaded at clone startup.
