MASTER DEVELOPMENT PROMPT
ART LAB [AGzO Edition]
Professional Native Mobile Graphics & Thumbnail Editing Studio

You are Claude acting as a principal software architect, senior React Native developer, graphics-engine engineer, mobile UI/UX designer, performance engineer and QA engineer.

Your mission is to BUILD a real, fully functional professional mobile graphics editing application called:

ART LAB [AGzO Edition]

This project must be developed exclusively for Android and iOS.

This is NOT a website, NOT a desktop application and NOT a simple photo-filter application.

It must be a powerful Photoshop CC 2019-inspired mobile editing studio with professional editing capabilities, an extensive assets library and custom asset importing.

IMPORTANT: Create an original implementation and original UI. Do not copy Adobe's proprietary source code, branding or protected assets.

1. DEVELOPMENT ENVIRONMENT

Use the following technology stack:

React Native
Expo
TypeScript
Expo Router
React Native Skia for graphics rendering where suitable
React Native Gesture Handler
React Native Reanimated
SQLite for project metadata
Native filesystem storage for project and asset files
Expo EAS Build for Android and iOS builds

Use maintained, compatible dependencies.

Use strict TypeScript.

Do not build the final product as a web application or WebView wrapper.

Before development:

Inspect the existing repository.
Understand the installed dependencies.
Create a detailed implementation plan.
Establish a scalable project architecture.
Begin implementation immediately after planning.

Do not stop after providing a plan.

2. APP BRANDING

Application name:

ART LAB [AGzO Edition]

Create:

Premium original app icon.
Splash screen.
Original brand identity.
Premium dark interface.
Optional light theme.
Professional typography.
Smooth but lightweight animations.

The application must look like a premium professional graphics editor.

3. MOBILE-FIRST USER EXPERIENCE

The application must be designed specifically for smartphones.

Support:

Android smartphones.
iPhones.
Android tablets.
iPads.

Prioritize one-hand usability.

Interface requirements:

Full-screen editing canvas.
Bottom floating toolbar.
Expandable editing panels.
Thumb-friendly controls.
Large touch targets.
Bottom sheets.
Collapsible tool categories.
Customizable left-handed/right-handed layout.
Safe-area support.
Dynamic screen sizing.
Dark theme.

Do not squeeze a desktop Photoshop layout onto a mobile screen.

4. PROFESSIONAL EDITING ENGINE

Build a genuine layered editing engine.

Implement:

Canvas
Create new projects.
Custom dimensions.
Canvas resizing.
Canvas rotation.
Zoom.
Pan.
Rulers.
Grid.
Guides.
Snap-to-guides.
Transparent canvas.
Layers
Create layers.
Delete layers.
Duplicate layers.
Rename layers.
Hide/show layers.
Lock/unlock layers.
Reorder layers.
Group/ungroup.
Layer opacity.
Blend modes.
Layer masks.
Clipping masks.
Adjustment layers.
Editing tools
Move tool.
Brush tool.
Eraser.
Crop.
Transform.
Rotate.
Clone stamp.
Healing tool where feasible.
Lasso.
Selection tools.
Magic wand.
Gradient.
Paint bucket.
Eyedropper.
Blur.
Sharpen.
Smudge.
Shape tools.
Pen/path tools where feasible.

Every tool must actually work.

5. ADVANCED TEXT EDITOR

Implement:

Multiple text layers.
Custom font import.
Font size and weight.
Letter spacing.
Line spacing.
Alignment.
Text color.
Text gradients.
Stroke.
Drop shadow.
Outer glow.
Inner glow.
3D-style effects.
Text transformations.
Curved text where feasible.

Support reusable text styles and presets.

6. PROFESSIONAL EFFECTS ENGINE

Implement:

Drop shadow.
Inner shadow.
Outer glow.
Inner glow.
Stroke.
Bevel and emboss.
Gradient overlay.
Color overlay.
Pattern overlay.
Gaussian blur.
Motion blur.
Radial blur.
Sharpen.
Noise.
Vignette.
Color correction.
Brightness.
Contrast.
Saturation.
Exposure.
Temperature.
Tint.
Hue.
Color balance.
Curves.
Levels.
Shadows and highlights.

Provide adjustable parameters and live previews.

Use non-destructive processing where practical.

7. ADVANCED ASSETS LIBRARY

Create a dedicated Assets Library.

Organize it into:

BASIC ASSETS
Shapes.
Arrows.
Frames.
Borders.
Icons.
Stickers.
Decorative elements.
Basic backgrounds.
PNG ASSETS
Transparent PNG objects.
Gaming graphics.
3D elements.
Social media elements.
Decorative elements.
Cutout objects.
EFFECT ASSETS
Smoke.
Fire.
Lightning.
Neon glow.
Light leaks.
Lens flares.
Bokeh.
Particles.
Rain.
Snow.
Dust.
Explosion graphics.
Cinematic overlays.
BACKGROUNDS
HD backgrounds.
4K backgrounds.
Abstract backgrounds.
Gaming backgrounds.
Gradient backgrounds.
Cinematic backgrounds.
Textures.
Metallic backgrounds.
Grunge textures.
Patterns.
TYPOGRAPHY
Gaming fonts.
Bold fonts.
Thumbnail fonts.
3D text presets.
Neon text presets.
Gradient text presets.
Stroke presets.
BRUSHES
Soft brushes.
Hard brushes.
Texture brushes.
Glow brushes.
Custom brush presets.
Gradient presets.
TEMPLATES
Gaming thumbnails.
Tech thumbnails.
YouTube thumbnails.
Vlog thumbnails.
Educational thumbnails.
News thumbnails.
Entertainment thumbnails.
Business thumbnails.

Use properly licensed, public-domain or original starter assets.

The app must include a starter asset collection that works offline.

Do not create fake asset previews or empty categories.

8. CUSTOM ASSET IMPORT SYSTEM

This is a critical feature.

Users must be able to import their own assets from:

Device gallery.
Files manager.
Downloads.
Supported external storage locations.

Support:

PNG.
JPG.
JPEG.
WebP.
SVG with secure parsing.
Supported font formats.
Supported brush presets.
Supported gradients and patterns.
Documented custom asset pack format.

Allow users to:

Import multiple assets.
Create folders.
Create categories.
Rename assets.
Delete assets.
Duplicate assets.
Add favorites.
Search assets.
Preview assets.
Sort assets.
Export custom asset packs.
Import custom asset packs.

Custom assets must remain available after restarting the application.

Persist asset metadata and file references safely.

Do not rely on temporary file URIs.

9. ASSET EDITING

Every placed asset should become an editable canvas object or layer.

Support:

Move.
Resize.
Rotate.
Flip.
Opacity.
Blend modes.
Filters.
Shadows.
Glow.
Masking.
Duplication.
Layer ordering.

Support non-destructive asset editing wherever practical.

10. TOUCH GESTURES

Implement:

One-finger selection.
One-finger drawing.
One-finger object movement.
Two-finger pinch zoom.
Two-finger pan.
Canvas rotation where appropriate.
Double-tap zoom.
Long-press context menus.
Drag-and-drop asset placement.

Avoid gesture conflicts between drawing, canvas navigation and object selection.

Provide a clear way to switch between drawing and navigation modes.

11. IMPORT AND EXPORT

Image import:

Gallery.
Camera.
Files.

Image export:

PNG.
JPG.
WebP.
Transparent PNG.
Custom dimensions.
720p.
1080p.
2K.
4K.

Default YouTube thumbnail: 1280 × 720 pixels.

Preserve image quality and transparency.

Implement proper color and memory management.

12. PROJECT SYSTEM

Implement:

Save projects.
Open projects.
Rename projects.
Duplicate projects.
Delete projects.
Recent projects.
Autosave.
Undo/redo.
Editing history.
Crash recovery.
Local project storage.

Create a documented native project format such as .artlab.

Preserve editable layers, text, effects, masks, asset references and project dimensions.

Do not silently flatten projects when saving.

13. PERFORMANCE ENGINEERING

Performance is critical.

Optimize for:

Low-end Android phones.
Mid-range Android phones.
Flagship Android phones.
Older supported iPhones.
Latest iPhones.
Tablets.

Implement:

GPU acceleration where available.
Efficient Skia rendering.
Preview resolution during editing.
Full-resolution export.
Memory-aware caching.
Background processing.
Worker-based processing where supported.
Image tiling for large documents where practical.
Lazy loading.
Efficient resource cleanup.
Debounced autosave.
Cancellation of expensive operations.

Do not block the main UI thread with heavy image processing.

Avoid unnecessary copies of large image buffers.

Provide graceful fallbacks when advanced graphics features are unavailable.

14. SECURITY AND PRIVACY

Implement:

Secure file validation.
Safe SVG parsing.
File size limits.
Safe image decoding.
Secure API key handling.
No hardcoded secrets.
User consent for external AI processing.
Secure authentication if accounts are implemented.
Proper error handling.
Protection against malicious uploads.

Never upload personal images without user consent.

15. AI FEATURES

Design optional AI-powered capabilities:

Background removal.
Background generation.
Object selection.
Image enhancement.
Image upscaling.
Smart cutout.

Use supported external services or models.

Keep API keys on a secure backend.

Provide manual alternatives when AI services are unavailable.

Do not pretend an AI operation succeeded when it failed.

16. TESTING AND QUALITY ASSURANCE

Create automated tests.

Test:

Image importing.
Image exporting.
Layer management.
Blend modes.
Text rendering.
Masks.
Undo/redo.
Custom asset importing.
Asset persistence.
Project recovery.
Large images.
Touch gestures.
App lifecycle.
Low-memory handling.
Android compatibility.
iOS compatibility.

Fix discovered errors.

Never claim zero bugs without extensive real-device testing.

Maintain a list of known limitations.

17. DEVELOPMENT WORKFLOW

Work in phases.

PHASE 1: Project setup, architecture, branding, navigation and mobile UI.

PHASE 2: Canvas engine, image import, layers, basic tools and export.

PHASE 3: Text engine, effects, color adjustments and advanced tools.

PHASE 4: Assets Library and starter asset collection.

PHASE 5: Custom asset import, persistence, folders and asset packs.

PHASE 6: Advanced features, AI integrations and project management.

PHASE 7: Performance optimization, security and testing.

PHASE 8: Android and iOS production builds.

At the end of each phase:

Run the application.
Run relevant tests.
Inspect errors.
Fix errors.
Update documentation.
Preserve existing functionality.

Do not skip phases.

Do not replace actual implementation with placeholder buttons.

Do not claim a feature is complete until it works.

18. CLAUDE WORKING INSTRUCTIONS

You must work directly with the available project files and development tools.

If the project is empty, initialize it correctly.

If a project already exists, inspect it before changing anything.

Before installing dependencies, verify compatibility.

Make small, safe changes.

Run TypeScript checks and tests regularly.

If a build fails, investigate and fix the root cause.

Do not delete working code unnecessarily.

If a task is too large for one response, continue in manageable development stages and maintain a clear progress checklist.

Do not stop after writing sample code or displaying mockups.

Implement actual working functionality.

FINAL DELIVERY

Deliver ART LAB [AGzO Edition] as a functional native Android and iOS editing application.

Provide:

Complete source code.
Working editing engine.
Professional mobile UI.
Basic-to-advanced asset library.
Custom asset importing and management.
Native Android build.
iOS build instructions.
Testing report.
Architecture documentation.
Setup instructions.
Known limitations.

The ultimate goal is to create a powerful, stable, mobile-first Photoshop-inspired graphics editing studio that users can operate comfortably with one hand.

START DEVELOPMENT NOW.
