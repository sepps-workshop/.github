<p align="center">
  <img src="./sepps-workshop-header.jpg" width="100%" alt="Sepp, the blue robot, assembling code blocks with a wrench in his workshop" />
</p>

# Sepp’s Workshop

Sepp is the robot who keeps things running at [sepp.med](https://www.seppmed.com). This is his workshop: colour themes for the tools developers stare at all day, all built on sepp.med Darkblue with Sunset yellow as the accent.

<p>
  <img src="https://img.shields.io/badge/Darkblue-0d3174" alt="Darkblue #0d3174" />
  <img src="https://img.shields.io/badge/Sunset-fbba00" alt="Sunset #fbba00" />
  <img src="https://img.shields.io/badge/Windblue-008ecf" alt="Windblue #008ecf" />
  <img src="https://img.shields.io/badge/Pumpelorange-ec6608" alt="Pumpelorange #ec6608" />
</p>

One theme per tool, no variants, no settings to wrestle with. Every text colour is checked against WCAG AA before it ships, because a theme you cannot read is just an expensive way to rest your eyes.

## The workshop

| Repository                                                                                             | What it is                                                                 | Status                                                                                                        |
| ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| [`sepps-workshop-design-system`](https://github.com/sepps-workshop/sepps-workshop-design-system)       | The colours, the rules for using them, and the build that enforces WCAG AA | on [npm](https://www.npmjs.com/package/@sepps-workshop/design-system)                                         |
| [`sepps-workshop-vs-code`](https://github.com/sepps-workshop/sepps-workshop-vs-code)                   | Theme for VS Code                                                          | on the [Marketplace](https://marketplace.visualstudio.com/items?itemName=sepps-workshop.sepps-workshop-theme) |
| [`sepps-workshop-windows-terminal`](https://github.com/sepps-workshop/sepps-workshop-windows-terminal) | Theme for Windows Terminal                                                 | released                                                                                                      |
| [`sepps-workshop-powershell`](https://github.com/sepps-workshop/sepps-workshop-powershell)             | Theme for PowerShell                                                       | released                                                                                                      |
| [`sepps-workshop-fish`](https://github.com/sepps-workshop/sepps-workshop-fish)                         | Theme for fish                                                             | released                                                                                                      |
| [`sepps-workshop-starship`](https://github.com/sepps-workshop/sepps-workshop-starship)                 | Theme for Starship                                                         | working                                                                                                       |

The design system is the foundation. The themes live in their own repositories and read every colour from it, so a fix there reaches every tool.

## Spotted a colour that looks off?

Open an issue in the repository of the tool where you saw it. If two things are hard to tell apart, the cause is almost always in the design system, and we will move it there.

## Want to join Sepp’s Workshop?

<img align="right" width="150" src="./sepp-recruiting.png" alt="Sepp, the blue robot, holding a sign that reads Be you – with us!" />

sepp.med builds and tests software for places where a bug is more than an inconvenience: medical devices, cars, aircraft. We have been doing it since 1980, as a family-run company in the Nuremberg metropolitan region. If you would rather get the contrast ratio right than argue about it, you might like it here.

Browse the [open positions](https://www.seppmed.com/career/open-positions/), or send a [speculative application](https://www.seppmed.com/career/speculative-application/) if none of them fits yet. Be you – with us.
