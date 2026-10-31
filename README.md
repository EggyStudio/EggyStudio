# EggyStudio

<div align="center">

## [3D Engine](https://github.com/EggyStudio/3DEngine)

A C# engine on SDL3, Vulkan, ImGui and Slang. Raylib's design over a Bevy-style ECS and scheduler,
scripted with its own Unity-style behaviors. Implementing Radiance Cascades. [e3d.cs]

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4)
![Graphics](https://img.shields.io/badge/Graphics-Vulkan-AC162C)
![Windowing](https://img.shields.io/badge/Windowing-SDL3-0B7BB2)
![Shaders](https://img.shields.io/badge/Shaders-Slang-2E7D32)
![Status](https://img.shields.io/badge/Status-Early-yellow)

</div>

<div align="center">

## [Bevy C#](https://github.com/EggyStudio/BevyCSharp)

Bevy C# [Behavior] on a struct are component & systems, generated at compile or runtime and wired straight into Bevy's ECS. Implementing Radiance Cascades. [bcs]

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4) ![Graphics](https://img.shields.io/badge/Graphics-wgpu%20%28Vulkan%2C%20DX12%2C%20Metal%29-AC162C) ![Windowing](https://img.shields.io/badge/Windowing-winit-0B7BB2) ![Shaders](https://img.shields.io/badge/Shaders-Slang-2E7D32) ![Status](https://img.shields.io/badge/Status-Early-yellow)



</div>

| Repository | What it is |
|---|---|
| [Voxel-Sandbox](https://github.com/EggyStudio/Voxel-Sandbox) | A voxel game written in C# on 3DEngine. Implementing Radiance Cascades. [e3d.cs] |

## The modules both engines use

Libraries the engines take as git submodules, so one solution serves both.

| Repository | What it holds |
|---|---|
| [Modeling](https://github.com/EggyStudio/Modeling) | An edit mesh shaped by operations through a selection, with recipes and commands |
| [Vegetation](https://github.com/EggyStudio/Vegetation) | Trees and grass grown from a species and a seed, with their texture sets and placement |
| [Levels](https://github.com/EggyStudio/Levels) | Levels in the Valve 220 map format, brushes to meshes and collision, with TrenchBroom's files |
| [Landscape](https://github.com/EggyStudio/Landscape) | A heightfield shaped by stamps and erosion, with vegetation placed over it |
| [RadianceCascades](https://github.com/EggyStudio/RadianceCascades) | The radiance cascades' CPU side and Slang shaders, each engine binding its own GPU side |
| [Tools](https://github.com/EggyStudio/Tools) | The scripts and document sources the repositories share, the devlog generator and the run reader among them |

## Linux

| Repository | What it is |
|---|---|
| [02Gnome](https://github.com/EggyStudio/02Gnome) | Configure and customize your GNOME environment in one command |

## .NET bindings and tools

| Repository | What it is |
|---|---|
| [UniversalSceneDescription](https://github.com/EggyStudio/UniversalSceneDescription) | OpenUSD USD.NET (Universal Scene Description) by Pixar and translated by Unity |
| [MaterialX.Net](https://github.com/EggyStudio/MaterialX.Net) | A single-package .NET binding for the MaterialX rich material and look-development content in computer graphics |
| [UltralightNet.Bundle](https://github.com/EggyStudio/UltralightNet.Bundle) | A single-package .NET binding for the Ultralight HTML rendering engine |
| [BlueprintShell](https://github.com/EggyStudio/BlueprintShell) | BlueprintShell is an embeddable editor shell built on BlazorBlueprintUI |
| [MarkdownToPDF](https://github.com/EggyStudio/MarkdownToPDF) | Convert one or more Markdown files into a styled, navigable PDF using WinAppSDK WinUI3 Fluent UI |
| [Encyclopedia](https://github.com/EggyStudio/Encyclopedia) | An open, Wikipedia-style encyclopedia where articles live in ordinary GitHub repositories and the web app pulls them in automatically |
| [ZeroTier.Quantum.Net](https://github.com/EggyStudio/ZeroTier.Quantum.Net) | A .NET binding of ZeroTier's networking |

## Unity Essentials

[UnityEssentials](https://github.com/EggyStudio/UnityEssentials) is the hub, a modular, production-ready ecosystem of game development building blocks with automated dependency management. Its 143 packages, one repository each, by family.

<details><summary><b>Core</b>, 4 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Core.HDRP.ImGui](https://github.com/EggyStudio/Unity.Core.HDRP.ImGui) | Minimal ImGui integration for HDRP that renders through a Custom Pass in Edit Mode and Play Mode, providing an immediate mode GUI library based on Dear ImGui an |
| [Unity.Core.HDRP.Resources](https://github.com/EggyStudio/Unity.Core.HDRP.Resources) | A ready-to-use set of HDRP assets - HDRP Asset, HDRP Global Settings, default LookDev profile, a default settings Volume Profile, and a global Volume Profile - |
| [Unity.Core.HDRP.Settings](https://github.com/EggyStudio/Unity.Core.HDRP.Settings) | Inspector-first HDRP settings component that surfaces runtime-loaded options using Unity Essentials Enum Drawer, and lets you load/save user choices to JSON |
| [Unity.Core.Templates.Sponza](https://github.com/EggyStudio/Unity.Core.Templates.Sponza) | One-click Sponza environment prefab spawner |

</details>

<details><summary><b>Dependencies</b>, 4 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Dependencies.Addressables](https://github.com/EggyStudio/Unity.Dependencies.Addressables) | Addressables |
| [Unity.Dependencies.GitApi](https://github.com/EggyStudio/Unity.Dependencies.GitApi) | Git CLI commands for the selected folder: fetch, pull, stage, commit and push using a stored HTTPS personal access token |
| [Unity.Dependencies.GitHub](https://github.com/EggyStudio/Unity.Dependencies.GitHub) | Clone multiple GitHub repositories into your Unity project with a stored HTTPS personal access token |
| [Unity.Dependencies.NuGet](https://github.com/EggyStudio/Unity.Dependencies.NuGet) | In-Editor NuGet package management powered by NuGetForUnity |

</details>

<details><summary><b>Diagnostics</b>, 5 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Diagnostics.Console](https://github.com/EggyStudio/Unity.Diagnostics.Console) | Console |
| [Unity.Diagnostics.Gizmo](https://github.com/EggyStudio/Unity.Diagnostics.Gizmo) | In-game transform gizmo for Rotation/Translation/Scale |
| [Unity.Diagnostics.Modules](https://github.com/EggyStudio/Unity.Diagnostics.Modules) | Lightweight, in-game frame time overlay with a bar graph and live stats (FPS, frame ms, render ms, memory, GC spikes) |
| [Unity.Diagnostics.Monitoring](https://github.com/EggyStudio/Unity.Diagnostics.Monitoring) | Annotate fields, properties, events, and methods to see live values in-game |
| [Unity.Diagnostics.ToggleShortcut](https://github.com/EggyStudio/Unity.Diagnostics.ToggleShortcut) | ToggleShortcut |

</details>

<details><summary><b>Editor</b>, 34 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Editor.Attributes.Button](https://github.com/EggyStudio/Unity.Editor.Attributes.Button) | Expose methods as clickable buttons in the Inspector, with optional labels, grouping, weight-based layout, custom height, parameters UI, and coroutine support ( |
| [Unity.Editor.Attributes.DateTime](https://github.com/EggyStudio/Unity.Editor.Attributes.DateTime) | Inspector-only attributes to edit dates and times with friendly controls |
| [Unity.Editor.Attributes.Directory](https://github.com/EggyStudio/Unity.Editor.Attributes.Directory) | Add a folder picker to string fields |
| [Unity.Editor.Attributes.Foldout](https://github.com/EggyStudio/Unity.Editor.Attributes.Foldout) | Group serialized fields under collapsible foldouts in the Inspector |
| [Unity.Editor.Attributes.Info](https://github.com/EggyStudio/Unity.Editor.Attributes.Info) | Show contextual HelpBox messages in the Inspector |
| [Unity.Editor.Attributes.LabelOverride](https://github.com/EggyStudio/Unity.Editor.Attributes.LabelOverride) | Override the display label of a serialized field in the Inspector using [LabelOverride("Your Label")] |
| [Unity.Editor.Attributes.MinMaxSlider](https://github.com/EggyStudio/Unity.Editor.Attributes.MinMaxSlider) | Draw a single slider that edits a min/max pair |
| [Unity.Editor.Attributes.OnValueChanged](https://github.com/EggyStudio/Unity.Editor.Attributes.OnValueChanged) | Invoke a method when specific serialized fields change in the Inspector |
| [Unity.Editor.Attributes.ReadOnly](https://github.com/EggyStudio/Unity.Editor.Attributes.ReadOnly) | Display any serialized field as a non-editable value in the Inspector |
| [Unity.Editor.Attributes.ShowIf](https://github.com/EggyStudio/Unity.Editor.Attributes.ShowIf) | Conditionally show or disable fields and methods in the Inspector based on another field's value |
| [Unity.Editor.Attributes.ToggleButton](https://github.com/EggyStudio/Unity.Editor.Attributes.ToggleButton) | Render boolean fields as clickable toggle buttons with optional icons |
| [Unity.Editor.Components.StickyNote](https://github.com/EggyStudio/Unity.Editor.Components.StickyNote) | Add color-coded notes to your GameObjects right in the Inspector |
| [Unity.Editor.Drawer.Console](https://github.com/EggyStudio/Unity.Editor.Drawer.Console) | Drawer, Console |
| [Unity.Editor.Drawer.DomainReload](https://github.com/EggyStudio/Unity.Editor.Drawer.DomainReload) | Drawer, DomainReload |
| [Unity.Editor.Drawer.Enum](https://github.com/EggyStudio/Unity.Editor.Drawer.Enum) | A better enum popup for the Inspector with search, keyboard navigation, and virtualization |
| [Unity.Editor.Drawer.EnumFlags](https://github.com/EggyStudio/Unity.Editor.Drawer.EnumFlags) | A foldout with checkboxes, "All" and "None" controls for bitwise flag enums |
| [Unity.Editor.Drawer.MarkdownViewer](https://github.com/EggyStudio/Unity.Editor.Drawer.MarkdownViewer) | Drawer, MarkdownViewer |
| [Unity.Editor.Drawer.PackageManifest](https://github.com/EggyStudio/Unity.Editor.Drawer.PackageManifest) | Edit package.json files inside Unity with a focused editor window: name/display name, version, Unity version, dependencies, keywords, samples, author, links, an |
| [Unity.Editor.Drawer.ReorderableList](https://github.com/EggyStudio/Unity.Editor.Drawer.ReorderableList) | Drawer, ReorderableList |
| [Unity.Editor.Drawer.SceneReference](https://github.com/EggyStudio/Unity.Editor.Drawer.SceneReference) | Strongly-typed scene picker + runtime helper |
| [Unity.Editor.Drawer.ScriptableObject](https://github.com/EggyStudio/Unity.Editor.Drawer.ScriptableObject) | Inline-edit ScriptableObject references directly in the Inspector |
| [Unity.Editor.Drawer.SerializedDictionary](https://github.com/EggyStudio/Unity.Editor.Drawer.SerializedDictionary) | A strongly-typed, serializable dictionary with a smooth inspector experience |
| [Unity.Editor.Drawer.SimpleTreeView](https://github.com/EggyStudio/Unity.Editor.Drawer.SimpleTreeView) | A lightweight, IMGUI-based TreeView wrapper for editor tools: drag-and-drop reparenting/reorder, unique naming, rename, selection helpers, per-item and global c |
| [Unity.Editor.Drawer.WindowBuilder](https://github.com/EggyStudio/Unity.Editor.Drawer.WindowBuilder) | A tiny fluent API for building polished EditorWindow UIs fast |
| [Unity.Editor.Fetcher.MouseInput](https://github.com/EggyStudio/Unity.Editor.Fetcher.MouseInput) | Editor-only helper that exposes the OS-level mouse cursor position from native APIs on Windows, macOS, and Linux |
| [Unity.Editor.Hooks.Hierarchy](https://github.com/EggyStudio/Unity.Editor.Hooks.Hierarchy) | Editor-only selection hook for the Hierarchy |
| [Unity.Editor.Hooks.Inspector](https://github.com/EggyStudio/Unity.Editor.Hooks.Inspector) | Global, editor-only hook system to extend MonoBehaviour inspectors |
| [Unity.Editor.Hooks.PlayerLoop](https://github.com/EggyStudio/Unity.Editor.Hooks.PlayerLoop) | Tiny runtime helper to inject and remove managed delegates into top-level Unity PlayerLoop phases like Update, FixedUpdate, EarlyUpdate, etc., via PlayerLoop.Ad |
| [Unity.Editor.Hooks.Statusbar](https://github.com/EggyStudio/Unity.Editor.Hooks.Statusbar) | Hooks, Statusbar |
| [Unity.Editor.Hooks.TextAsset](https://github.com/EggyStudio/Unity.Editor.Hooks.TextAsset) | Hooks, TextAsset |
| [Unity.Editor.Hooks.Toolbar](https://github.com/EggyStudio/Unity.Editor.Hooks.Toolbar) | Hooks, Toolbar |
| [Unity.Editor.Hooks.UIBuilder](https://github.com/EggyStudio/Unity.Editor.Hooks.UIBuilder) | Editor-only hooks into the Unity UI Builder |
| [Unity.Editor.Tools.EditorIcons](https://github.com/EggyStudio/Unity.Editor.Tools.EditorIcons) | Search, preview, copy, and export Unity's built-in editor icon textures |
| [Unity.Editor.Tools.MaskMapGenerator](https://github.com/EggyStudio/Unity.Editor.Tools.MaskMapGenerator) | Pack Metallic, AO, Detail Mask, and Smoothness into a single RGBA texture |

</details>

<details><summary><b>Environment</b>, 13 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Environment.Atmosphere](https://github.com/EggyStudio/Unity.Environment.Atmosphere) | Atmosphere |
| [Unity.Environment.CelestialBodies](https://github.com/EggyStudio/Unity.Environment.CelestialBodies) | Lightweight utilities for sun/moon astronomy (RA/Dec, distance, sidereal time, refraction) and a lighting controller that drives Unity sun/moon lights in lux wi |
| [Unity.Environment.Clouds](https://github.com/EggyStudio/Unity.Environment.Clouds) | Clouds |
| [Unity.Environment.Ecosystem](https://github.com/EggyStudio/Unity.Environment.Ecosystem) | Ecosystem |
| [Unity.Environment.Fauna](https://github.com/EggyStudio/Unity.Environment.Fauna) | Fauna |
| [Unity.Environment.Flora](https://github.com/EggyStudio/Unity.Environment.Flora) | Flora |
| [Unity.Environment.Ocean](https://github.com/EggyStudio/Unity.Environment.Ocean) | Drop-in ocean and pool water prefabs powered by a Shader Graph material and a tuned volume profile |
| [Unity.Environment.Precipitation](https://github.com/EggyStudio/Unity.Environment.Precipitation) | Precipitation |
| [Unity.Environment.Terrain](https://github.com/EggyStudio/Unity.Environment.Terrain) | Terrain |
| [Unity.Environment.TimeOfDay](https://github.com/EggyStudio/Unity.Environment.TimeOfDay) | HDRP time-of-day controller that orients sun/moon lights from date, time, and location; drives HDRP light units (Lux), sky material rotation matrices, and night |
| [Unity.Environment.Vegetation](https://github.com/EggyStudio/Unity.Environment.Vegetation) | Vegetation |
| [Unity.Environment.Weather](https://github.com/EggyStudio/Unity.Environment.Weather) | Drop-in HDRP weather prefab with preconfigured Volumes for Cloud Layer, Volumetric Clouds, and Volumetric Fog |
| [Unity.Environment.Wind](https://github.com/EggyStudio/Unity.Environment.Wind) | Wind |

</details>

<details><summary><b>Graphics</b>, 10 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Graphics.AdvancedAtmosphere](https://github.com/EggyStudio/Unity.Graphics.AdvancedAtmosphere) | AdvancedAtmosphere |
| [Unity.Graphics.AdvancedSky](https://github.com/EggyStudio/Unity.Graphics.AdvancedSky) | AdvancedSky |
| [Unity.Graphics.AdvancedSpotLight](https://github.com/EggyStudio/Unity.Graphics.AdvancedSpotLight) | HDRP composite spot light that splits a main light into tinted RGB channel lights to simulate chromatic aberration |
| [Unity.Graphics.AdvancedTerrain](https://github.com/EggyStudio/Unity.Graphics.AdvancedTerrain) | AdvancedTerrain |
| [Unity.Graphics.AdvancedVolumetrics](https://github.com/EggyStudio/Unity.Graphics.AdvancedVolumetrics) | AdvancedVolumetrics |
| [Unity.Graphics.AdvancedWater](https://github.com/EggyStudio/Unity.Graphics.AdvancedWater) | AdvancedWater |
| [Unity.Graphics.ApvLightingBaker](https://github.com/EggyStudio/Unity.Graphics.ApvLightingBaker) | Editor helper to add/apply and bake HDRP Adaptive Probe Volume (APV) lighting scenarios by name (sync or async), plus a one-click mesh converter to receive GI f |
| [Unity.Graphics.BlackoutReflectionProbe](https://github.com/EggyStudio/Unity.Graphics.BlackoutReflectionProbe) | Creates a child Reflection Probe that always returns a black cubemap inside its bounds, effectively killing environment reflections in that volume |
| [Unity.Graphics.LightCookies](https://github.com/EggyStudio/Unity.Graphics.LightCookies) | Example IES photometric light profile for HDRP lights |
| [Unity.Graphics.Tonemaps](https://github.com/EggyStudio/Unity.Graphics.Tonemaps) | A small pack of AgX-inspired tonemapping LUTs (EXR) for HDRP |

</details>

<details><summary><b>Humanoid</b>, 5 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Humanoid.ActiveRagdoll](https://github.com/EggyStudio/Unity.Humanoid.ActiveRagdoll) | Physics-driven "active ragdoll" that follows an animation using a simple PD controller and ConfigurableJoints |
| [Unity.Humanoid.AdvancedAvatar](https://github.com/EggyStudio/Unity.Humanoid.AdvancedAvatar) | AdvancedAvatar |
| [Unity.Humanoid.AnimationRigging](https://github.com/EggyStudio/Unity.Humanoid.AnimationRigging) | A lightweight head/aim "look target" helper |
| [Unity.Humanoid.PoseController](https://github.com/EggyStudio/Unity.Humanoid.PoseController) | Runtime helper to author and apply humanoid poses by writing Unity's human muscle values |
| [Unity.Humanoid.RagdollBuilder](https://github.com/EggyStudio/Unity.Humanoid.RagdollBuilder) | One-click Humanoid ragdoll generation with in-scene gizmos to edit colliders, joints, and centers of mass |

</details>

<details><summary><b>Movement</b>, 2 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Movement.AdvancedCharacterController](https://github.com/EggyStudio/Unity.Movement.AdvancedCharacterController) | AdvancedCharacterController |
| [Unity.Movement.SpectatorController](https://github.com/EggyStudio/Unity.Movement.SpectatorController) | Free-fly spectator camera controller with mouse look, scroll-wheel dolly, WASD/QE movement, boost, and optional acceleration |

</details>

<details><summary><b>Multiplayer</b>, 13 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Multiplayer.Backend.InterestManagement](https://github.com/EggyStudio/Unity.Multiplayer.Backend.InterestManagement) | Backend, InterestManagement |
| [Unity.Multiplayer.Backend.WorldPartition](https://github.com/EggyStudio/Unity.Multiplayer.Backend.WorldPartition) | Backend, WorldPartition |
| [Unity.Multiplayer.Communication.Chat](https://github.com/EggyStudio/Unity.Multiplayer.Communication.Chat) | Communication, Chat |
| [Unity.Multiplayer.Communication.Voice](https://github.com/EggyStudio/Unity.Multiplayer.Communication.Voice) | Communication, Voice |
| [Unity.Multiplayer.Lobbies](https://github.com/EggyStudio/Unity.Multiplayer.Lobbies) | Lobbies |
| [Unity.Multiplayer.Matchmaking](https://github.com/EggyStudio/Unity.Multiplayer.Matchmaking) | Matchmaking |
| [Unity.Multiplayer.P2P](https://github.com/EggyStudio/Unity.Multiplayer.P2P) | P2P |
| [Unity.Multiplayer.P2P.Replication](https://github.com/EggyStudio/Unity.Multiplayer.P2P.Replication) | P2P, Replication |
| [Unity.Multiplayer.P2P.Sessions](https://github.com/EggyStudio/Unity.Multiplayer.P2P.Sessions) | P2P, Sessions |
| [Unity.Multiplayer.Sessions](https://github.com/EggyStudio/Unity.Multiplayer.Sessions) | Sessions |
| [Unity.Multiplayer.Social.Friends](https://github.com/EggyStudio/Unity.Multiplayer.Social.Friends) | Social, Friends |
| [Unity.Multiplayer.Social.Groups](https://github.com/EggyStudio/Unity.Multiplayer.Social.Groups) | Social, Groups |
| [Unity.Multiplayer.Social.Invites](https://github.com/EggyStudio/Unity.Multiplayer.Social.Invites) | Social, Invites |

</details>

<details><summary><b>Networking</b>, 11 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Networking.Backend.Encryption](https://github.com/EggyStudio/Unity.Networking.Backend.Encryption) | Backend, Encryption |
| [Unity.Networking.Backend.NatTraversal](https://github.com/EggyStudio/Unity.Networking.Backend.NatTraversal) | Backend, NatTraversal |
| [Unity.Networking.Backend.PeerDiscovery](https://github.com/EggyStudio/Unity.Networking.Backend.PeerDiscovery) | Backend, PeerDiscovery |
| [Unity.Networking.Backend.Relay](https://github.com/EggyStudio/Unity.Networking.Backend.Relay) | Backend, Relay |
| [Unity.Networking.Backend.Serialization](https://github.com/EggyStudio/Unity.Networking.Backend.Serialization) | Backend, Serialization |
| [Unity.Networking.Backend.Transport](https://github.com/EggyStudio/Unity.Networking.Backend.Transport) | Backend, Transport |
| [Unity.Networking.Database](https://github.com/EggyStudio/Unity.Networking.Database) | Database |
| [Unity.Networking.Identity](https://github.com/EggyStudio/Unity.Networking.Identity) | Identity |
| [Unity.Networking.Inventory](https://github.com/EggyStudio/Unity.Networking.Inventory) | Inventory |
| [Unity.Networking.Persistence](https://github.com/EggyStudio/Unity.Networking.Persistence) | Persistence |
| [Unity.Networking.Profiles](https://github.com/EggyStudio/Unity.Networking.Profiles) | Profiles |

</details>

<details><summary><b>Rendering</b>, 8 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Rendering.AdvancedCamera](https://github.com/EggyStudio/Unity.Rendering.AdvancedCamera) | AdvancedCamera |
| [Unity.Rendering.Camera.AutoExposure](https://github.com/EggyStudio/Unity.Rendering.Camera.AutoExposure) | Automatic camera exposure adjustment driven by scene luminance, with target luminance band, asymmetric reaction speeds, and shutter/ISO bias |
| [Unity.Rendering.Camera.FocusPoint](https://github.com/EggyStudio/Unity.Rendering.Camera.FocusPoint) | Forward ray- or sphere-cast to derive camera focus distance, with separate near/far speeds, layer filtering, debug gizmo, and optional Cinemachine integration |
| [Unity.Rendering.Camera.Luminance](https://github.com/EggyStudio/Unity.Rendering.Camera.Luminance) | GPU-based average luminance measurement from a camera's render target, using a compute shader with async GPU readback and a normalized 0, 1 output |
| [Unity.Rendering.Camera.PhysicalProperties](https://github.com/EggyStudio/Unity.Rendering.Camera.PhysicalProperties) | Preset-driven mapping from normalized multipliers to physical camera settings (aperture, focal length, ISO, shutter), applied to Cinemachine Lens or the built-i |
| [Unity.Rendering.Camera.RenderTexture](https://github.com/EggyStudio/Unity.Rendering.Camera.RenderTexture) | Camera output is directed to a managed RenderTexture with configurable size, HDR, mipmaps, filter mode, and aspect-ratio aware UI presentation |
| [Unity.Rendering.CameraRefreshRate](https://github.com/EggyStudio/Unity.Rendering.CameraRefreshRate) | Per-camera rendering frequency can be limited to a target FPS, using either normal camera rendering or SRP render requests, synchronized by a global refresh rat |
| [Unity.Rendering.GlobalRefreshRate](https://github.com/EggyStudio/Unity.Rendering.GlobalRefreshRate) | A global cadence for rendering and time-sliced work, driven by a high-precision frame limiter that hooks into the PlayerLoop, and signals subscribers on each ti |

</details>

<details><summary><b>Sound</b>, 6 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Sound.Acoustics](https://github.com/EggyStudio/Unity.Sound.Acoustics) | Acoustics |
| [Unity.Sound.AudioMixer](https://github.com/EggyStudio/Unity.Sound.AudioMixer) | Drop-in AudioMixer asset with common groups and exposed volume parameters: master, music, effects, voice, and environment |
| [Unity.Sound.Playback](https://github.com/EggyStudio/Unity.Sound.Playback) | Playback |
| [Unity.Sound.SpatialAudio](https://github.com/EggyStudio/Unity.Sound.SpatialAudio) | SpatialAudio |
| [Unity.Sound.Synthesis](https://github.com/EggyStudio/Unity.Sound.Synthesis) | Synthesis |
| [Unity.Sound.Voice](https://github.com/EggyStudio/Unity.Sound.Voice) | Voice |

</details>

<details><summary><b>Systems</b>, 17 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Systems.AssetResolver](https://github.com/EggyStudio/Unity.Systems.AssetResolver) | Typed, deterministic asset lookup for runtime addressable first loader, with optional caching |
| [Unity.Systems.CameraProvider](https://github.com/EggyStudio/Unity.Systems.CameraProvider) | Zero-setup, global access to the "active" camera in Play and Edit Mode, plus its world height (Y) and distance from origin |
| [Unity.Systems.DependencyInjection](https://github.com/EggyStudio/Unity.Systems.DependencyInjection) | Lightweight, attribute-based runtime dependency injection for MonoBehaviours |
| [Unity.Systems.EventBus](https://github.com/EggyStudio/Unity.Systems.EventBus) | Strongly-typed, lightweight event bus for decoupled messaging between MonoBehaviours |
| [Unity.Systems.FieldBinder](https://github.com/EggyStudio/Unity.Systems.FieldBinder) | One-shot field/property value sync between two objects via reflection |
| [Unity.Systems.PredefinedAssembly](https://github.com/EggyStudio/Unity.Systems.PredefinedAssembly) | Helpers for mapping Unity's common assemblies and discovering loaded types that implement a given interface or base type across the game assemblies |
| [Unity.Systems.RuntimeDiscovery](https://github.com/EggyStudio/Unity.Systems.RuntimeDiscovery) | Tiny runtime utility that centralizes scene discovery and reflection helpers used by other runtime systems |
| [Unity.Systems.SceneLoader](https://github.com/EggyStudio/Unity.Systems.SceneLoader) | Scene-group based additive loading with optional Addressables support, aggregated progress reporting, smooth UI-friendly progress, and lifecycle events for load |
| [Unity.Systems.Serializer](https://github.com/EggyStudio/Unity.Systems.Serializer) | Shared JSON serialization + atomic file IO + a small envelope format used by SettingsProfile and SettingsDefinition |
| [Unity.Systems.SettingsDefinition](https://github.com/EggyStudio/Unity.Systems.SettingsDefinition) | Metadata side of settings keyed by paths like Controls/Mouse/Sensitivity that provides labels, tooltips, defaults, and UI control definitions and does not store |
| [Unity.Systems.SettingsProfile](https://github.com/EggyStudio/Unity.Systems.SettingsProfile) | Lightweight, versioned settings profiles backed by JSON files |
| [Unity.Systems.Singleton](https://github.com/EggyStudio/Unity.Systems.Singleton) | Generic MonoBehaviour singletons for Unity, including a runtime auto-creating singleton, a persistent (DontDestroyOnLoad) variant, and a regulator that keeps on |
| [Unity.Systems.SkinnedMeshTransfer](https://github.com/EggyStudio/Unity.Systems.SkinnedMeshTransfer) | Rebind one or more SkinnedMeshRenderers to a new armature by bone name, re-parent them under a new root, and optionally reset local transforms |
| [Unity.Systems.Task](https://github.com/EggyStudio/Unity.Systems.Task) | Zero-allocation async/await tailored for Unity |
| [Unity.Systems.Tick](https://github.com/EggyStudio/Unity.Systems.Tick) | Frame-synchronized tick scheduler |
| [Unity.Systems.Timing](https://github.com/EggyStudio/Unity.Systems.Timing) | High-performance coroutine scheduler using IEnumerator with segment control (Update, FixedUpdate, LateUpdate, LazyUpdate) |
| [Unity.Systems.UtilityExtensions](https://github.com/EggyStudio/Unity.Systems.UtilityExtensions) | Handy, zero-dependency extension methods for common Unity tasks: camera dynamic resolution, safe destroy helpers, component access, string formatting, vector co |

</details>

<details><summary><b>Types</b>, 2 packages</summary>

| Package | What it does |
|---|---|
| [Unity.Types.ManagedArray](https://github.com/EggyStudio/Unity.Types.ManagedArray) | A pooled, growable array for structs |
| [Unity.Types.ObjectPool](https://github.com/EggyStudio/Unity.Types.ObjectPool) | Thread-safe generic pool with per-type singletons |

</details>

<details><summary><b>UI</b>, 9 packages</summary>

| Package | What it does |
|---|---|
| [Unity.UI.Fonts](https://github.com/EggyStudio/Unity.UI.Fonts) | Curated UI font families, an emoji sprite sheet, TextMeshPro style sheet, and a full set of TMP shaders (Built-in/URP/HDRP/Mobile) to make text look consistent |
| [Unity.UI.Toolkit.Animation](https://github.com/EggyStudio/Unity.UI.Toolkit.Animation) | Drop-in USS utility classes for UI Toolkit transitions |
| [Unity.UI.Toolkit.ElementLinker](https://github.com/EggyStudio/Unity.UI.Toolkit.ElementLinker) | Bind MonoBehaviours to UI Toolkit VisualElements without boilerplate |
| [Unity.UI.Toolkit.Extensions](https://github.com/EggyStudio/Unity.UI.Toolkit.Extensions) | Handy extension methods for UIDocument and VisualElement to streamline common UI Toolkit tasks: add style sheets once, set size in pixels or percent, tweak text |
| [Unity.UI.Toolkit.MarqueeLabel](https://github.com/EggyStudio/Unity.UI.Toolkit.MarqueeLabel) | A custom UI Toolkit <MarqueeLabel> that automatically scrolls overflowing text horizontally |
| [Unity.UI.Toolkit.MenuGenerator](https://github.com/EggyStudio/Unity.UI.Toolkit.MenuGenerator) | Visual editor for building data-driven UI Toolkit menus |
| [Unity.UI.Toolkit.ScriptComponents](https://github.com/EggyStudio/Unity.UI.Toolkit.ScriptComponents) | Drop-in MonoBehaviours for common UI Toolkit tasks - event routing, OnValueChanged handlers, label/background setters, and display toggling - powered by the UI |
| [Unity.UI.Toolkit.SplashScreen](https://github.com/EggyStudio/Unity.UI.Toolkit.SplashScreen) | Three-act, UI Toolkit-driven splash sequence with timed material/light/lens-flare animation, synced audio, and easy branding via textures and text |
| [Unity.UI.Toolkit.Tooltip](https://github.com/EggyStudio/Unity.UI.Toolkit.Tooltip) | Zero-setup hover tooltips for UI Toolkit |

</details>

## Earlier work

<details><summary><b>Engine packages</b>, the earlier modular engine in 36 packages, which 3DEngine replaced</summary>

| Package | Area |
|---|---|
| [Engine.App](https://github.com/EggyStudio/Engine.App) | App |
| [Engine.App.Sdl](https://github.com/EggyStudio/Engine.App.Sdl) | App, Sdl |
| [Engine.App.Sdl.ImGui](https://github.com/EggyStudio/Engine.App.Sdl.ImGui) | App, Sdl, ImGui |
| [Engine.Assets](https://github.com/EggyStudio/Engine.Assets) | Assets |
| [Engine.Common](https://github.com/EggyStudio/Engine.Common) | Common |
| [Engine.Components](https://github.com/EggyStudio/Engine.Components) | Components |
| [Engine.Editor](https://github.com/EggyStudio/Engine.Editor) | Editor |
| [Engine.Entities](https://github.com/EggyStudio/Engine.Entities) | Entities |
| [Engine.Entities.Behaviors](https://github.com/EggyStudio/Engine.Entities.Behaviors) | Entities, Behaviors |
| [Engine.Graphics](https://github.com/EggyStudio/Engine.Graphics) | Graphics |
| [Engine.Graphics.Shaders](https://github.com/EggyStudio/Engine.Graphics.Shaders) | Graphics, Shaders |
| [Engine.Lighting](https://github.com/EggyStudio/Engine.Lighting) | Lighting |
| [Engine.Materials](https://github.com/EggyStudio/Engine.Materials) | Materials |
| [Engine.Materials.X](https://github.com/EggyStudio/Engine.Materials.X) | Materials, X |
| [Engine.Models](https://github.com/EggyStudio/Engine.Models) | Models |
| [Engine.Models.Assimp](https://github.com/EggyStudio/Engine.Models.Assimp) | Models, Assimp |
| [Engine.Models.Gltf](https://github.com/EggyStudio/Engine.Models.Gltf) | Models, Gltf |
| [Engine.Multiplayer](https://github.com/EggyStudio/Engine.Multiplayer) | Multiplayer |
| [Engine.Networking](https://github.com/EggyStudio/Engine.Networking) | Networking |
| [Engine.Physics](https://github.com/EggyStudio/Engine.Physics) | Physics |
| [Engine.Physics.Bepu](https://github.com/EggyStudio/Engine.Physics.Bepu) | Physics, Bepu |
| [Engine.Pipelines](https://github.com/EggyStudio/Engine.Pipelines) | Pipelines |
| [Engine.Pipelines.ImGui](https://github.com/EggyStudio/Engine.Pipelines.ImGui) | Pipelines, ImGui |
| [Engine.Renderer](https://github.com/EggyStudio/Engine.Renderer) | Renderer |
| [Engine.Renderer.Extracts](https://github.com/EggyStudio/Engine.Renderer.Extracts) | Renderer, Extracts |
| [Engine.Renderer.Graph](https://github.com/EggyStudio/Engine.Renderer.Graph) | Renderer, Graph |
| [Engine.Renderer.Phases](https://github.com/EggyStudio/Engine.Renderer.Phases) | Renderer, Phases |
| [Engine.Scenes](https://github.com/EggyStudio/Engine.Scenes) | Scenes |
| [Engine.Scenes.Usd](https://github.com/EggyStudio/Engine.Scenes.Usd) | Scenes, Usd |
| [Engine.Sound](https://github.com/EggyStudio/Engine.Sound) | Sound |
| [Engine.Sound.Sdl](https://github.com/EggyStudio/Engine.Sound.Sdl) | Sound, Sdl |
| [Engine.Sound.SteamAudio](https://github.com/EggyStudio/Engine.Sound.SteamAudio) | Sound, SteamAudio |
| [Engine.Textures](https://github.com/EggyStudio/Engine.Textures) | Textures |
| [Engine.Textures.Stb](https://github.com/EggyStudio/Engine.Textures.Stb) | Textures, Stb |
| [Engine.WebView](https://github.com/EggyStudio/Engine.WebView) | WebView |
| [Engine.WebView.Vulkan](https://github.com/EggyStudio/Engine.WebView.Vulkan) | WebView, Vulkan |

</details>

<details><summary><b>Older repositories</b>, 5</summary>

| Repository | What it is |
|---|---|
| [SDL3DEngine](https://github.com/EggyStudio/SDL3DEngine) | Minimal HowTo for building and using SDL3 on a variety of platforms, including mobile and web |
| [Voxeland](https://github.com/EggyStudio/Voxeland) | GAME | A Minecraft/Cubeworld-like WebGL-Game on HTML5 created with Unity 2020.3 URP |
| [SAE_Project](https://github.com/EggyStudio/SAE_Project) | Fighting, Arcade, Beat ‘Em Up, Action, Multiplayer, Competitive |
| [UnityNoise](https://github.com/EggyStudio/UnityNoise) | UnityNoise |
| [Wiki](https://github.com/EggyStudio/Wiki) | Wiki |

</details>
