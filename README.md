# GHOSTPHISH-v3.5-AUTO-TUNNEL-LOCALHOST-CAMERA-GUARANTEED
GhostPhish v3.5: mobile capture framework for authorized pen testing. Phishing link silently grabs: · 📸 Front camera (victim face) · 📍 Real-time GPS + Maps · 🖥️ DOM screenshots · 📱 Full device fingerprint After 15sec, seamless redirect to any URL you provided— zero trace.
Feature Description
📸 Invisible Camera Camera stream runs in a 1×1 pixel hidden element — victim sees nothing
📍 Dual GPS Native GPS via browser + IP geolocation fallback (always gets a location)
🖥️ DOM Screenshots html2canvas captures the actual rendered page as the victim sees it
📱 Device Fingerprint OS, browser, screen size, CPU cores, RAM, battery, network type, timezone
🔀 Silent Redirect window.location.replace() — no back-button trace, no visible overlay
🎯 One-Tap Activation Single button triggers camera → location → screenshots in sequence

TUNNEL FEATURES
Feature Description
☁️ Auto-Install Cloudflare Downloads cloudflared binary automatically if missing
🔒 Auto-Install Ngrok Downloads ngrok binary + prompts for auth token
🔑 SSH Tunnels Localhost.run and Serveo.net — no install needed
🏠 Localhost Mode Option 5 for same-device testing (camera works on localhost!)
✅ HTTPS Verification Confirms tunnel is serving HTTPS before you deploy

Feature Description
🔴 Live Capture Feed Real-time terminal output of every capture
📊 Running Counters Victims, camera shots, screenshots, GPS pings, errors
🗺️ Google Maps Links Every GPS ping generates a clickable Maps URL
📁 Per-Victim Storage Each victim gets organized folder: uploads/<victim_id>/
🏆 Hunt Summary Clean summary on exit with all capture statistics

OS Status Install Method Notes
Kali Linux ✅ Native apt install php curl Gold standard. Everything works.
Ubuntu / Debian ✅ Native apt install php curl Perfect.
Parrot OS ✅ Native Pre-installed Security distro.
Arch / BlackArch ✅ Native pacman -S php curl Rolling release.
Fedora / RHEL ✅ Native dnf install php-cli curl Works.
macOS ✅ Native brew install php curl Full support.
Termux (Android) ✅ Native pkg install php curl openssh Run directly from your phone!
Windows (WSL2) ✅ Native Install Ubuntu in WSL2 Full Linux environment.
Raspberry Pi ✅ Native apt install php curl ARM64/ARMv7 supported.
Cloud VPS ✅ Native Any Linux distro 24/7 operation.
Docker ✅ Container php:8.2-cli image Portable.
iOS (iSH) ❌ No N/A Apple blocks PHP CLI.
Windows (Native) ❌ No N/A Use WSL2 instead.

Minimum Requirements:

· PHP 7.4+ (8.x recommended)
· curl (for tunnel URL detection)
· bash (any version)
· 50MB free disk space
· Internet connection (for tunnel + CDN resources)

  
📱 SUPPORTED TARGETS (VICTIM DEVICES) <a name="supported-targets-victim-devices"></a>

What devices GhostPhish can capture from:

Platform Browser Camera GPS Screenshots Device Info
Android Chrome ✅ ✅ ✅ ✅
Android Firefox ✅ ✅ ✅ ✅
Android Samsung Browser ✅ ✅ ✅ ✅
Android Opera ✅ ✅ ✅ ✅
Android Brave ✅ ✅ ✅ ✅
Android WebView (in-app) ⚠️ *  ⚠️ *  ✅ ✅
iOS Safari ✅ ✅ ✅ ✅
iOS Chrome ✅ ✅ ✅ ✅
iOS Firefox ✅ ✅ ✅ ✅
iOS Brave ✅ ✅ ✅ ✅
iOS Edge ✅ ✅ ✅ ✅
iPadOS All browsers ✅ ✅ ✅ ✅
Desktop Chrome ✅ ✅ ✅ ✅
Desktop Firefox ✅ ✅ ✅ ✅
Desktop Edge ✅ ✅ ✅ ✅

Requirements for full capture:

· HTTPS connection (provided by all tunnel options)
· User taps "Allow" on camera + location permission prompts
· JavaScript enabled (enabled by default on all modern browsers)
· html2canvas loads from CDN (requires internet during capture)

What works WITHOUT user permission:

· ✅ Device fingerprint (always captured)
· ✅ DOM screenshots (no permission prompt)
· ✅ IP geolocation fallback (no permission prompt)
· ✅ Redirect (always works)
