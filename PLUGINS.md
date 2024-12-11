# S2400 Plugin Build Status

This document tracks the build and compatibility status of DISTRHO-Ports plugins for the S2400.

## Build Status Legend
- ✅ Built & Working
- 🟡 Builds but Untested
- 🔧 Needs Modification
- ❌ Build Failed
- 📝 Not Yet Attempted

## Compatibility Requirements
- Target: aarch64 (imx8mq)
- Host: sushi v1.1.0
- Plugin Format: LV2
- Install Paths: /usr/lib/lv2/ or /home/isla/user/plugins/lv2/

## Common Modifications Needed
1. Change lv2:requiredFeature to lv2:optionalFeature for inPlaceBroken
2. Static linking where possible to minimize dependency issues
3. CPU optimization for imx8mq architecture

## Plugin Status

### JUCE 5 Ports
- [ ] Plugin1 📝
- [ ] Plugin2 📝

### JUCE 6.0 Ports
- [ ] Plugin1 📝
- [ ] Plugin2 📝

### JUCE 6.1 Ports
- [ ] Plugin1 📝
- [ ] Plugin2 📝

### JUCE 7 Ports
- [ ] Plugin1 📝
- [ ] Plugin2 📝

## Working Examples Reference
- BollieDelayXT
- dm-SpaceEcho (with modifications)
- MaGigaverb

## Required Dependencies
(List will be updated as we discover dependencies during builds)