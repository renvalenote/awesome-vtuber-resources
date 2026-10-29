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
- [Krita](https://krita.org/en/features/) — Prepare separated, layered artwork for 2D model production and export PSD files. Check the [PSD format limits](https://docs.krita.org/en/general_concepts/file_formats/file_psd.html) and test imports in your rigging tool; Krita is not among Live2D's [confirmed-compatible drawing applications](https://docs.live2d.com/en/cubism-editor-manual/precautions-for-psd-data/). **Website: EN / JA; linked compatibility documentation: EN.**
- [VRM Add-on for Blender](https://github.com/saturday06/VRM-Addon-for-Blender) — Import, edit, and export VRM avatars in Blender, including humanoid and MToon settings. Follow the installation instructions for your Blender version. **Repository: EN / JA.**

- [Ucupaint](https://extensions.blender.org/add-ons/ucupaint/) — Paint and organize avatar texture layers and masks in Blender, then bake channel images for export. The Blender Extensions build requires Blender 4.2 or newer and uses GPL-3.0-or-later; choose a compatible release for older Blender versions. **Extension page and documentation: EN.**

## Tracking and streaming

Match your model format and tracking hardware to the application's requirements before building your setup.

- [VTube Studio](https://denchisoft.com/) — Animate Live2D models with face tracking and control expressions, props, and scene interactions. Its [official documentation and API repository](https://github.com/DenchiSoft/VTubeStudio) also supports plugin development; the repository is not the application's source code. **Website: EN.**
- [VSeeFace](https://www.vseeface.icu/) — Drive VRM 0 avatars with face tracking on 64-bit Windows and exchange tracking data through VMC. VRM 1.0 is not supported; optional hand tracking requires a Leap Motion device. **Website: EN.**
- [Warudo](https://www.warudo.app/) — Build 3D VTuber scenes with avatars, environments, props, and configurable interactions. See the [official handbook](https://docs.warudo.app/docs) for setup and supported tracking systems. **Handbook: EN / JA.**
- [veadotube mini](https://veado.tube/) — Build a PNGTuber avatar from images that react to microphone input, with blinking and switchable expression states. See the [official usage guide](https://veado.tube/docs/usage/mini/) and [OBS capture guide](https://veado.tube/docs/usage/obs/). **Website and documentation: EN.**
- [nizima LIVE](https://nizimalive.com/en/) — Live2D Inc.'s tracking app for animating Live2D models with a webcam or the companion iPhone tracker, with parameter adjustments and collaboration features. This is separate from the nizima marketplace. **Website: EN / JA.**
- [OBS Studio](https://obsproject.com/) — Combine an avatar app's video with game capture, audio, and overlays for live streaming or recording. Follow your avatar app's capture instructions, such as the [VTube Studio guide](https://github.com/DenchiSoft/VTubeStudio/wiki/Recording-Streaming-with-OBS). **Website: EN / JA and other languages; linked guide: EN.**
- [OneComme (わんコメ)](https://onecomme.com/) — Collect chat from multiple streaming platforms, read comments aloud, display comment overlays, and manage viewer participation queues. See the [official documentation](https://onecomme.com/docs/about/) and [terms](https://onecomme.com/terms/): free-version use generally requires attribution, with exceptions; some features and templates are paid. **Linked website and documentation: JA.**
- [VNyan](https://suvidriel.itch.io/vnyan) — Use VRM, VRM 1.0, and VSFAvatar models in a Windows VTubing app, with a node-graph interface for viewer interactions and OBS event integration. **Product page: EN.**
- [VDO.Ninja](https://vdo.ninja/) — Bring remote collaborators' video and audio into OBS. For VTuber avatar feeds, the project's optional Windows [Game Capture companion](https://github.com/steveseguin/game-capture/blob/main/docs/windows-guide.md) can send Spout2 output from apps such as VTube Studio or VSeeFace through VDO.Ninja. True alpha-channel playback requires the VDO.Ninja OBS plugin's experimental native receiver, not a normal browser source. **Website and documentation: EN.**
- [Streamer.bot](https://streamer.bot/) — Turn chat and platform events into avatar and scene actions. Its [VTube Studio integration](https://docs.streamer.bot/guide/integrations/vtube-studio) supports model, expression, and hotkey actions alongside OBS controls. The app targets Windows; [macOS and Linux setup](https://docs.streamer.bot/get-started/installation) is experimental. **Website and documentation: EN.**

- [OBS Spout2 Plugin](https://github.com/Off-World-Live/obs-spout2-plugin) — Capture transparent avatar video from VTube Studio or VSeeFace in OBS without capturing the app's settings UI. This 64-bit Windows plugin requires a release compatible with your OBS version. Follow the [VTube Studio capture guide](https://github.com/DenchiSoft/VTubeStudio/wiki/Recording-Streaming-with-OBS) or [VSeeFace guide](https://www.vseeface.icu/spout) for app-specific settings. **Repository and guides: EN.**

- [Inochi Session](https://github.com/Inochi2D/inochi-session) — Animate and stream Inochi2D puppets made in Inochi Creator. The [official download page](https://inochi2d.com/download/) offers free Windows, macOS, and Linux builds; the repository warns that it is still under heavy development and not production-ready. **Repository and download page: EN.**
- [VBridger](https://store.steampowered.com/app/1898830/VBridger/?l=english) — Paid Windows app for tuning face-tracking inputs for VTube Studio or compatible VRM setups. Advanced expressions require appropriate model rigging; creating custom outputs requires the Editor DLC. VMC output carries facial data, not head/eye rotation or body motion. See the [official setup guide](https://github.com/PiPuProductions/VBridger-Documentation/wiki/1.-Getting-Started). **Linked product page and guide: EN.**

- [SlimeVR](https://slimevr.dev/) — IMU-based full-body tracking for 3D VTubing, with open-source server software. Its [compatibility guide](https://docs.slimevr.dev/misc/compatibility.html#vtubing-and-motion-capture) lists VNyan and Warudo support via VMC. Requires separately obtained compatible trackers, either prebuilt or DIY. **Website and guide: EN.**
- [VRM Posing Desktop](https://store.steampowered.com/app/1895630/VRM_Posing_Desktop/) — ACHIOKI's paid posing tool for preparing avatar thumbnails, transparent images, and short MP4 clips. Supports VRM 1.0, VRM Animation (.vrma), and FBX/GLB props. This is a posing and content-production tool, not a model-rigging editor. **Linked product page: EN.**

- [VMagicMirror](https://malaybaku.github.io/VMagicMirror/en/) — Move a VRM avatar with keyboard, mouse, or controller input for work and game streams on 64-bit Windows, without requiring VR hardware. Microphone lip sync and optional webcam head tracking are also available. The [free Standard edition](https://malaybaku.github.io/VMagicMirror/en/download/) has restrictions on some hand-tracking, VMC, and Buddy features; a paid Full edition is available. **Website and documentation: EN / JA.**

- [iFacialMocap](https://www.ifacialmocap.com/) — Send facial tracking from a Face ID-equipped iPhone to compatible avatar apps. The [VSeeFace setup](https://www.vseeface.icu/) requires an avatar prepared with ARKit blendshapes and a shared network for phone and PC. The [iOS editions](https://www.ifacialmocap.com/download/) include a paid ad-free app and a free ad-supported app. **Website: EN / JA; linked VSeeFace guide: EN.**

- [StreamElements Alerts & Overlays](https://streamelements.com/features/overlays) — Create customizable stream alerts and overlays, such as Twitch follower and subscriber notifications. Add them to OBS as a Browser Source using the [official setup guide](https://docs.streamelements.com/selive/guides/overlays-and-alerts); keep the overlay URL private. Core alerts and overlays are free. **Website and guide: EN.**

- [PNGTuber Plus](https://kaiakairos.itch.io/pngtuber-plus) — Build layered PNG avatars with independently moving sprites, attachment, drag, bounce, and speaking/blinking visibility controls for OBS capture. Windows, macOS, and Linux builds are available; the [source project](https://github.com/kaiakairos/PNGTuber-Plus) uses the Unlicense. The author [notes performance problems](https://itch.io/t/4479727/whats-with-this-cpu-usage) on some hardware, so test your streaming setup before use. **Product page and repository: EN.**
- [VRM Live Viewer](https://fantom1x.booth.pm/items/1783082) — Fantom's free Windows 10/11 (x64) viewer for staging VRM avatar dance videos with VMD/BVH motions and customizable backgrounds. VRM 1.0 is not supported. The [official FAQ](https://note.com/fantom1x/n/nb7c0299faa74) permits commercial use of the app, but model, motion, music, and preset-asset permissions must be checked separately. **Product page: JA / partial EN; FAQ: mainly JA.**
- [SAMMI VTube Studio Extension](https://github.com/HueVirtualCreature/SAMMIVtubeStudioExtension) — HueVirtualCreature's MIT-licensed community extension for triggering VTube Studio expressions, model/item actions, and hotkeys from SAMMI automations. Requires VTube Studio 1.21.5 or newer, a running SAMMI Bridge, and authorization inside VTube Studio. [SAMMI Core](https://sammi.solutions/docs/download) officially supports Windows 10 or later; check the extension release's requirements and test buttons before going live. **Repository and documentation: EN.**

- [nizima ACTION!!](https://site.nizima-action.com/en/) — Live2D's browser editor for short avatar videos, with model import, captions, and voice-driven lip sync. Check the desktop [system requirements](https://docs.nizima-action.com/en/manual/system-requirements/); smartphones are unsupported. The beta software is free, including commercial use, under its [terms](https://site.nizima-action.com/ja/terms-of-use/). Provided assets have [separate conditions](https://site.nizima-action.com/ja/material-data-terms-of-use/), including an inquiry requirement for corporate commercial use. **Website and documentation: EN / JA; Japanese terms are authoritative.**

## Learning resources

- [Live2D Cubism Tutorials](https://docs.live2d.com/en/cubism-editor-tutorials/top/) — Follow the official model-making workflow, from preparing illustrations to expressions, body movement, and animation. **Documentation: EN / JA.**
- [VRM Documentation](https://vrm.dev/en/) — Learn the VRM avatar format, its ecosystem, and the distinctions between format versions and model usage permissions. **Documentation: EN / JA; some English-path pages remain Japanese.**
- [OBS Studio Quick Start Guide](https://obsproject.com/kb/quick-start-guide) — Follow the official first-stream workflow: automatic configuration, scene sources, audio setup, and a test recording before going live. **Guide: EN.**

- [VRoid Studio Official Tutorials & Help](https://vroid.pixiv.help/hc/en-us/categories/900000339606) — Pixiv's beginner walkthrough and illustrated guides for the stable version of VRoid Studio: create characters, customize hair, import outfit textures, and export VRM models. Check the destination app's VRM-version support before exporting. **Guides: EN / JA.**

- [OBS Compressor and Ducking Guide](https://obsproject.com/kb/compressor-filter) — Learn to reduce loud microphone peaks and lower game or background-music volume while speaking, using OBS's built-in compressor. The official guide explains the controls and provides starting settings for sidechain ducking; tune them for your own audio. **Guide: EN.**

- [OBS Multiple Audio Track Recording Guide](https://obsproject.com/kb/multiple-audio-track-recording-guide) — Record microphone, game, and background-music sources on separate tracks so their levels can be adjusted when editing stream highlights. Keep a combined mix on track 1 for ordinary video-player playback, and enable the required recording tracks in OBS output settings. **Guide: EN.**
- [Twitch AutoMod Guide](https://help.twitch.tv/s/article/how-to-use-automod?language=en_US) — Set up held-message review and blocked/permitted terms for Twitch chat. Private blocked terms are hidden from moderators, which can help protect personal information. AutoMod holds messages for review; it does not automatically timeout or ban users. Language coverage varies by moderation category. **Linked guide: EN.**

## Commissions, assets, and usage rights

A listing is a place to start your own checks. Confirm commercial use, attribution, modification, exclusivity, and redistribution terms with the relevant creator or rights holder. Inclusion here does not endorse every seller or asset on a platform.

- [VGen](https://www.vgen.co/) — Find creators offering model art, rigging, stream graphics, and other commission services. Review each creator's portfolio, deliverables, and terms. **Website: EN.**
- [nizima](https://nizima.com/) — Browse Live2D models and illustrations through Live2D's marketplace. Check the conditions attached to each work. **Website: JA.**
- [VRoid Hub](https://hub.vroid.com/en) — Browse 3D characters and their usage conditions. A public model page does not necessarily permit downloads, streaming, or redistribution. **Website: EN / JA.**
- [Live2D Sample Models](https://www.live2d.com/en/learn/sample/) — Study official sample models and their construction. Read the applicable sample-data terms before using them in your own work. **Website: EN / JA.**
- [hololive Production Derivative Works Guidelines](https://hololivepro.com/en/terms/) — Consult the rights holder's rules when making relevant hololive fan works. These guidelines do not grant permission for unrelated creators' work. **Guidelines: EN / JA.**
- [BOOTH](https://booth.pm/en) — Browse creator shops for 3D models, textures, and stream assets. Check each item's format, supported applications, and creator-defined usage terms before buying or using it. **Website: EN / JA; listing languages vary.**

- [VN3 License](https://www.vn3.org/) — Free, customizable terms-of-use templates and a [generator](https://www.vn3.org/generator) for distributing avatar and other 3D-model assets. Designed for Japanese law and Japan-based right-holders; permissions depend on each asset's selected terms. **Website: JA; generated terms: Japanese authoritative text, English reference translation, and Korean/Chinese simplified translations.**

- [OKUMONO](https://sozaino.site/) — Find backgrounds, frames, and other graphics for streams and thumbnails. Its [terms](https://sozaino.site/kiyaku) allow free use in monetized streams and modification without credit, but prohibit asset redistribution, selling or publicly distributing stream-screen templates, asset-dominant merchandise sales, and AI training use. **Website: JA; terms also available in EN, Chinese, and Korean.**

- [OpenTracks (formerly DOVA-SYNDROME)](https://opentracks.com/) — Find background music for chat and game streams. The [license](https://opentracks.com/help/articles/license/) permits free commercial background use without attribution, subject to its restrictions and additional creator conditions. Redistributing audio files, streams primarily replaying the provided music, and user Content ID registration are not permitted. **Website and linked terms: JA.**

- [Sound Effect Lab (効果音ラボ)](https://soundeffect-lab.info/) — Find short sound effects for stream segments and edited videos. The [terms](https://soundeffect-lab.info/agreement/) allow free commercial use and modification without credit, subject to restrictions. Redistribution, including sound collections and asset templates containing the sounds, adult-content use, AI training, and registering music containing these sounds with YouTube Content ID are prohibited. **Website and terms: JA.**

## Discovery and public credits

Use directories to find leads, then check the original profile, announcement, or portfolio. Distinguish character design, illustration, Live2D rigging, 3D modeling, and outfit-specific work; one credit does not imply all of these roles.

- [Holodex](https://holodex.net/) — Discover VTuber streams and videos. The [official frontend repository](https://github.com/HolodexNet/Holodex) provides project context and source code. **Repository: EN.**
- [hololive Official Talent Profiles](https://hololive.hololivepro.com/en/talents/) — Find official profiles and illustrator credits where listed. For example, [Ninomae Ina'nis's profile](https://hololive.hololivepro.com/en/talents/ninomae-inanis/) identifies the illustrator; it is not a complete production-credit list. **Website: EN / JA.**
- [VTuber Zukan](https://vtuberzukan.com/) — Browse a directory with sections for VTubers, creators, and organizations. **Website: JA / EN / ZH; content coverage varies. Maintainer affiliation: this directory is also a project of this list's maintainer.**

## Developer resources

- [UniVRM](https://github.com/vrm-c/UniVRM) — Import and export VRM avatars in Unity using the VRM implementation maintained by the VRM Consortium's GitHub organization. **Documentation: EN / JA.**
- [three-vrm](https://github.com/pixiv/three-vrm) — Load and work with VRM avatars in Three.js-based web applications. **Repository: EN.**
- [VMC Protocol](https://protocol.vmc.info/english.html) — Implement motion and expression data exchange between compatible applications using the published OSC-based protocol. **Specification: EN / JA.**

- [OpenSeeFace](https://github.com/emilianavt/OpenSeeFace) — Build webcam-based avatar tracking integrations using facial landmarks sent over UDP and the included Unity receiver components. This is a tracking library rather than a standalone avatar app. Code and models use BSD-2-Clause; redistributed binary builds also require the included third-party license notices. **Repository and documentation: EN.**

- [pyvts](https://github.com/Genteki/pyvts) — Genteki's MIT-licensed Python library for building VTube Studio plugins, including custom tracking parameters. Follow the [tutorial](https://genteki.github.io/pyvts/toctree2_tutorial.html) for connecting and obtaining authorization in VTube Studio; this is a development library, not a standalone tracking app. **Repository and documentation: EN.**

- [godot-vrm](https://github.com/V-Sekai/godot-vrm) — V-Sekai's Godot addon for importing VRM 0.0/1.0 avatars, exporting VRM 1.0, and MToon rendering in custom avatar applications. The [Asset Library build](https://godotengine.org/asset-library/asset/2031) targets Godot 4.1 or newer. Code uses MIT; sample models have separate licenses. Check the documented feature limitations; VRM Animation (.vrma) is not implemented. **Repository: EN / JA, with some untranslated sections.**
- [uOSC](https://github.com/hecomi/uOSC) — hecomi's MIT-licensed OSC client/server library for Unity. Build avatar-motion integrations using the [official VMC Protocol samples](https://protocol.vmc.info/Sample), which use uOSC to exchange VRM bone and expression data. This is a transport library, not a standalone tracking app or a complete VMC implementation; match the sample's Unity/UniVRM dependencies. **Repository: EN; linked samples: EN / JA.**

## Selection and contributions

This list favors practical resources with clear ownership, an original source, and a distinct purpose. General-purpose tools belong here when they play a clear role in a VTubing workflow. Official product pages, documentation, and creator-owned pages are preferred over mirrors.

When proposing a resource:

1. Provide its canonical URL and a short explanation of the task it helps with.
2. Use the most relevant category and check for an existing entry. Add documentation links to the existing entry unless they provide a distinct learning resource.
3. Note the language of the page or documentation. Do not assume operating-system support, prices, or licensing from another tool in the same category.
4. For creator credits, cite a public statement from the VTuber, rights holder, or credited creator. Identify the role and model or outfit version when available. Leave unknown roles unspecified.
5. Disclose any relationship to the project, and keep the English and Japanese entries in sync.

Do not submit private-identity information, speculative links between past or alternate personas, leaked or unauthorized model files, or voice-cloning materials made without the speaker's permission. This list does not infer identities from voices, appearance, or social connections.

