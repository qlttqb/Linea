Linea

A macOS menu bar application that transforms your Strava workout history into a dynamic live wallpaper for your desktop. By securely connecting to your Strava account, Linea reads your past activity data locally and animates your run or cycle routes directly across your screen.
Key Features

Live Route Animations: Visualizes your actual GPS routes drawn in real-time as an animated background.
Customizable Aesthetics: Choose from multiple layout modes (Scatter, Grid, Sequence) and over a dozen curated color themes, including Classic, Dark, and Light editions.
Menu Bar Control: Operates quietly from your Mac's menu bar, allowing you to instantly sync new runs, toggle the wallpaper, or access display settings.
Performance Optimized: Automatically pauses background animations when covered by other windows to minimize CPU usage and preserve battery life.
Privacy Focused: Your GPS telemetry is processed purely locally on your machine to render the animations. Location data is never transmitted to or stored on external servers.

System Requirements:
OS: macOS Tahoe 26.0 or later
Architecture: Natively optimized for Apple Silicon (M-series chips)
Accounts: Requires an active Strava account and a valid Linea license key (via Gumroad).

Installation:
Linea is currently distributed outside the Mac App Store. Because it is not signed with an Apple Developer certificate, macOS Gatekeeper will flag it on the first launch.
Download the latest Linea.dmg from the Releases page.
Double-click the .dmg file to mount it.
Drag the Linea app icon into the Applications folder.
First Launch (Important): Do not double-click the app to open it. Instead, Right-click (or Control-click) the Linea app in your Applications folder and select Open. Click Open Anyway in the security prompt.
Note: If macOS displays an error stating the app is "damaged and should be moved to the Trash," open your Terminal and run the following command to clear the quarantine flag:xattr -cr /Applications/Linea.app

How It Works
Activate: Enter your Gumroad license key upon first launch to unlock the app.
Connect: Authorize Linea using Strava OAuth. No manual FIT or GPX file exports are required.
Personalize: Curate your canvas by selecting your preferred layout style and color themes from the Settings window.
Auto-Sync: Linea utilizes official Strava API webhooks to automatically fetch and cache your latest activities in the background.
Technology Stack
UI & Rendering: SwiftUI, native macOS Canvas/CoreGraphics
Updates: Sparkle 2.0 (EdDSA cryptographically signed appcast updates)
Licensing: Gumroad API
Data Integration: Strava API (OAuth 2.0 & Webhooks)
Privacy & Security

Linea is built with a strict local-first architecture. Your authentication credentials, license keys, and processed activity maps are stored securely on your local disk. Linea does not host, analyze, or monetize your location data.
Strava: API usage is subject to the Strava API Policy.
Gumroad: License verification requests are processed subject to Gumroad's Privacy Policy.

Linea is an independent application and is not associated with, endorsed by, or affiliated with Strava, Inc.
