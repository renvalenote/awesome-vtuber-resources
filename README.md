# Awesome VTuber Resources

**English** · [日本語](README.ja.md)

A curated guide to tools, tutorials, discovery services, and creator resources for VTubing. Find a starting point for making a model, bringing it to life, going live, or finding the people behind the work.

## Start here

- **Making a model?** Begin with [model creation](#model-creation), then follow the [learning resources](#learning-resources).
- **Ready to stream?** Choose a compatible app from [tracking and streaming](#tracking-and-streaming).
- **Looking for a creator or an asset?** Browse [commissions, assets, and usage rights](#commissions-assets-and-usage-rights).
- **Exploring VTubers and their work?** See [discovery and public credits](#discovery-and-public-credits).
- **Building an integration?** Head to [developer resources](#developer-resources).

Language notes describe the linked website or documentation, not a guarantee of every application's interface language. Check the official source for current compatibility, pricing, and terms.

## Contents

- [Model creation](#model-creation)
- [Tracking and streaming](#tracking-and-streaming)
- [Learning resources](#learning-resources)
- [Commissions, assets, and usage rights](#commissions-assets-and-usage-rights)
- [Discovery and public credits](#discovery-and-public-credits)
- [Developer resources](#developer-resources)
- [Selection and contributions](#selection-and-contributions)

## Model creation

- [Live2D Cubism](https://www.live2d.com/en/) — Create and animate 2D models from illustrations. A starting point for artists and Live2D riggers. **Website: EN / JA.**
- [VRoid Studio](https://vroid.com/en/studio) — Create humanoid 3D characters and export VRM models for compatible applications. **Website: EN / JA.**
- [Inochi Creator](https://github.com/Inochi2D/inochi-creator) — Rig layered 2D artwork for the Inochi2D puppet format, for VTubing and other real-time applications. The source code uses the [BSD-2-Clause license](https://github.com/Inochi2D/inochi-creator/blob/v0_8/LICENSE); the repository notes separate restrictions for branding assets. **Repository: EN.**
- [Krita](https://krita.org/en/features/) — Paint layered illustrations for model art and stream graphics, with layer management and PSD import/export for moving artwork between tools. **Website: EN / JA.**
- [VRM Add-on for Blender](https://github.com/saturday06/VRM-Addon-for-Blender) — Import, edit, and export VRM avatars in Blender, including humanoid and MToon settings. Follow the installation instructions for your Blender version. **Repository: EN / JA.**

## Tracking and streaming

Match your model format and tracking hardware to the application's requirements before building your setup.

- [VTube Studio](https://denchisoft.com/) — Animate Live2D models with face tracking and control expressions, props, and scene interactions. Its [official documentation and API repository](https://github.com/DenchiSoft/VTubeStudio) also supports plugin development; the repository is not the application's source code. **Website: EN.**
- [VSeeFace](https://www.vseeface.icu/) — Drive VRM avatars with face and hand tracking, including tracking-data exchange through the VMC protocol. **Website: EN.**
- [Warudo](https://www.warudo.app/) — Build 3D VTuber scenes with avatars, environments, props, and configurable interactions. See the [official handbook](https://docs.warudo.app/) for setup and supported tracking systems. **Handbook: EN / JA.**
- [veadotube mini](https://veado.tube/) — Build a PNGTuber avatar from images that react to microphone input, with blinking and switchable expression states. See the [official usage guide](https://veado.tube/docs/usage/mini/) and [OBS capture guide](https://veado.tube/docs/usage/obs/). **Website and documentation: EN.**
- [nizima LIVE](https://nizimalive.com/en/) — Live2D Inc.'s tracking app for animating Live2D models with a webcam or the companion iPhone tracker, with parameter adjustments and collaboration features. This is separate from the nizima marketplace. **Website: EN / JA.**
- [OBS Studio](https://obsproject.com/) — Combine video, audio, and overlays into scenes for live streaming or recording. **Website: EN / JA and other languages.**
- [OneComme (わんコメ)](https://onecomme.com/) — Collect chat from multiple streaming platforms, read comments aloud, display comment overlays, and manage viewer participation queues. See the [official documentation](https://onecomme.com/docs/about/) and [terms](https://onecomme.com/terms/): free-version use generally requires attribution, with exceptions; some features and templates are paid. **Linked website and documentation: JA.**
- [VNyan](https://suvidriel.itch.io/vnyan) — Use VRM, VRM 1.0, and VSFAvatar models in a Windows VTubing app, with a node-graph interface for viewer interactions and OBS event integration. **Product page: EN.**

## Learning resources

- [Live2D Cubism Tutorials](https://docs.live2d.com/en/cubism-editor-tutorials/top/) — Follow the official model-making workflow, from preparing illustrations to expressions, body movement, and animation. **Documentation: EN / JA.**
- [VRM Documentation](https://vrm.dev/en/) — Learn the VRM avatar format, its ecosystem, and the distinctions between format versions and model usage permissions. **Documentation: EN / JA.**

## Commissions, assets, and usage rights

A listing is a place to start your own checks. Confirm commercial use, attribution, modification, exclusivity, and redistribution terms with the relevant creator or rights holder. Inclusion here does not endorse every seller or asset on a platform.

- [VGen](https://www.vgen.co/) — Find creators offering model art, rigging, stream graphics, and other commission services. Review each creator's portfolio, deliverables, and terms. **Website: EN.**
- [nizima](https://nizima.com/) — Browse Live2D models and illustrations through Live2D's marketplace. Check the conditions attached to each work. **Website: JA.**
- [VRoid Hub](https://hub.vroid.com/en) — Browse 3D characters and their usage conditions. A public model page does not necessarily permit downloads, streaming, or redistribution. **Website: EN / JA.**
- [Live2D Sample Models](https://www.live2d.com/en/learn/sample/) — Study official sample models and their construction. Read the applicable sample-data terms before using them in your own work. **Website: EN / JA.**
- [hololive Production Derivative Works Guidelines](https://hololivepro.com/en/terms/) — Consult the rights holder's rules when making relevant hololive fan works. These guidelines do not grant permission for unrelated creators' work. **Guidelines: EN / JA.**
- [BOOTH](https://booth.pm/en) — Browse creator shops for 3D models, textures, and stream assets. Check each item's format, supported applications, and creator-defined usage terms before buying or using it. **Website: EN / JA; listing languages vary.**

## Discovery and public credits

Use directories to find leads, then check the original profile, announcement, or portfolio. Distinguish character design, illustration, Live2D rigging, 3D modeling, and outfit-specific work; one credit does not imply all of these roles.

- [Holodex](https://holodex.net/) — Discover VTuber streams and videos. The [official frontend repository](https://github.com/HolodexNet/Holodex) provides project context and source code. **Repository: EN.**
- [hololive Official Talent Profiles](https://hololive.hololivepro.com/en/talents/) — Find official profiles and illustrator credits where listed. For example, [Ninomae Ina'nis's profile](https://hololive.hololivepro.com/en/talents/ninomae-inanis/) identifies the illustrator; it is not a complete production-credit list. **Website: EN / JA.**
- [VTuber Zukan](https://vtuberzukan.com/) — Browse a Japanese-first directory with sections for VTubers, creators, and organizations. **Website: primarily JA. Maintainer affiliation: this directory is also a project of this list's maintainer.**

## Developer resources

- [UniVRM](https://github.com/vrm-c/UniVRM) — Import and export VRM avatars in Unity using the VRM implementation maintained by the VRM Consortium's GitHub organization. **Documentation: EN / JA.**
- [three-vrm](https://github.com/pixiv/three-vrm) — Load and work with VRM avatars in Three.js-based web applications. **Repository: EN.**
- [VMC Protocol](https://protocol.vmc.info/english.html) — Implement motion and expression data exchange between compatible applications using the published OSC-based protocol. **Specification: EN / JA.**

## Selection and contributions

This list favors practical resources with clear ownership, an original source, and a distinct purpose. General-purpose tools belong here when they play a clear role in a VTubing workflow. Official product pages, documentation, and creator-owned pages are preferred over mirrors.

When proposing a resource:

1. Provide its canonical URL and a short explanation of the task it helps with.
2. Use the most relevant category and check for an existing entry. Add documentation links to the existing entry unless they provide a distinct learning resource.
3. Note the language of the page or documentation. Do not assume operating-system support, prices, or licensing from another tool in the same category.
4. For creator credits, cite a public statement from the VTuber, rights holder, or credited creator. Identify the role and model or outfit version when available. Leave unknown roles unspecified.
5. Disclose any relationship to the project, and keep the English and Japanese entries in sync.

Do not submit private-identity information, speculative links between past or alternate personas, leaked or unauthorized model files, or voice-cloning materials made without the speaker's permission. This list does not infer identities from voices, appearance, or social connections.

