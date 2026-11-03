# Slime World: a film-quality world on Roblox

A Roblox game where you play a squishy slime ball rolling, bouncing and swimming through a hand-built world:
flower meadows, giant trees, rock spires, caves, and an underwater reef full of fish. The aim was to bring **film
VFX environment quality to a platform that runs on phones**.

I'm a VFX artist. I built the world myself (sculpted, textured and dressed in ZBrush, Substance, Maya and Houdini)
and made the game's tech by **directing AI coding agents**. Most of that tech is the
[Roblox Studio tools](https://github.com/jlipstock/roblox-studio-tools) I built for it.

> The source is private. This page describes the game and how it was made.

<p align="center"><img src="images/meadow.jpg" width="900" alt="The slime in a flower meadow with rock spires and hoops behind"></p>

<table><tr><td width="50%"><img src="images/underwater.jpg" width="100%" alt="Underwater: animated caustics on the rocks and a school of fish"></td><td width="50%"><img src="images/giant_tree.jpg" width="100%" alt="The slime on a dirt path below a giant tree, with birds flocking"></td></tr><tr><td width="50%"><img src="images/cave.jpg" width="100%" alt="Inside a blue-lit cave"></td><td width="50%"><img src="images/terrain_path.jpg" width="100%" alt="A worn dirt path through grass along a cliff"></td></tr></table>
<p align="center"><i>In-game captures. Top: the meadow (the counter in the corner reads 129 fps). Then the underwater reef with
caustics and a fish school, a flock of birds under the giant tree, a cave, and a terrain path.</i></p>

## What's in it

- **The slime**: a squishy slime-ball character controller (rolling, jumping, swimming) that reshapes to
  different slime skins, with a skin picker.
- **Water**: custom displaced water surfaces you can swim through, with animated caustics on the rocks below.
- **Life**: fish schools that shoal and steer around the player, and bird flocks that take off, glide and land.
- **Dressing**: painted flower fields and foliage that sway as you move through them, culled by distance so phones
  keep up.
- **Atmosphere**: world and zone fog, colour zones for per-area grading, and wind streaks.
- **Performance tooling**: an in-game FPS overlay for phones and stutter diagnostics, used to hold 60 fps on real
  devices.

## The art

<p align="center"><img src="images/zbrush_rock.jpg" width="300" alt="A rock spire sculpted in ZBrush"></p>
<p align="center"><i>One of the rock spires, sculpted in ZBrush before texturing and baking down for Roblox.</i></p>

The environment came out of a full VFX pipeline: ZBrush sculpts, Substance textures, Maya layout and Houdini,
plus Marmoset and Nuke. Everything was then baked down to fit Roblox's
mesh, texture and part budgets.

## Tech

Luau · Roblox Studio · EditableMesh · ZBrush · Substance · Maya · Houdini · Marmoset · Nuke
