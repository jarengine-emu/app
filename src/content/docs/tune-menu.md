---
title: "Tune Menu"
description: "Advanced configuration options for themes, performance, and emulator behavior in JarEngine"
order: 5
category: "Menus"
---

# Tune Menu Documentation

The **Tune** menu is your command center for customizing JarEngine's appearance, performance, and behavior. This menu offers extensive theming options, performance tuning, and advanced configuration settings to optimize your emulation experience.

## 🎨 Menu Items

### Adaptive Resolution
**Purpose**: Control the display scaling and zoom levels for optimal viewing.

**Available Options**:
- **1x** - Native resolution (100%)
- **1.25x** - Slight enlargement (125%)
- **1.5x** - Medium enlargement (150%)
- **1.75x** - Large enlargement (175%)
- **2x** - Double size (200%)

**How to Use**:
1. Navigate to **Tune** → **Adaptive Resolution**
2. Select your preferred zoom level
3. Changes apply immediately to the current display

**Best For**:
- **1x**: High-resolution displays, performance-critical applications
- **1.25x-1.5x**: Standard desktop monitors, balanced performance
- **1.75x-2x**: High-DPI displays, accessibility needs

### Internet Access
**Purpose**: Control network connectivity for MIDlet applications.

**Default State**: Enabled (checked)

**How to Use**:
- **Checked**: MIDlets can access the internet
- **Unchecked**: MIDlets run in offline mode

**Use Cases**:
- **Enabled**: Web-enabled MIDlets, online games, network applications
- **Disabled**: Offline testing, security-sensitive environments, performance optimization

### Record Store Manager
**Purpose**: Enable/disable the persistent data storage management interface.

**Default State**: Disabled (unchecked)

**How to Use**:
1. Check this option to enable the Record Store Manager
2. Access it from the Tools menu when enabled
3. Manage MIDlet data persistence and storage

**Benefits**:
- Monitor MIDlet data usage
- Clear stored data when needed
- Debug data persistence issues

### Console
**Purpose**: Toggle the log console display for debugging and monitoring.

**Default State**: Disabled (unchecked)

**How to Use**:
1. Check this option to show the console
2. Access detailed logging information
3. Monitor MIDlet behavior and errors

**Features**:
- Real-time log output
- Error tracking and debugging
- Performance monitoring

### Theme
**Purpose**: Customize the application's visual appearance with professional themes.

#### Built-in Themes
- **Mac Light** - Clean, modern light theme
- **Mac Dark** - Elegant dark theme
- **Flat Light** - Minimalist flat design
- **Flat Dark** - Dark flat aesthetic
- **IntelliJ** - Professional IDE-inspired theme
- **Darcula** - JetBrains-style dark theme

#### Extended Theme Collection
Access 30+ additional professional themes:

**Popular Options**:
- **One Dark** - Atom editor-inspired dark theme
- **GitHub Light/Dark** - GitHub-style themes
- **Dracula** - Vibrant dark theme
- **Nord** - Arctic-inspired color scheme
- **Monokai Pro** - Professional monokai variant
- **Solarized Light/Dark** - Eye-friendly color palette
- **Material variants** - Google Material Design themes
- **Arc themes** - Modern flat design collection

**How to Use**:
1. Navigate to **Tune** → **Theme**
2. Select your preferred theme category
3. Choose from built-in or extended themes
4. Theme changes apply immediately

**Theme Categories**:
- **Classic**: Traditional desktop themes
- **Flat**: Modern minimalist designs
- **Professional**: IDE and development themes
- **Custom**: Specialized color schemes

### Replicate Instances
**Purpose**: Create multiple emulator instances for testing and development.

**How to Use**:
1. Click **Replicate Instances** from the Tune menu
2. A new JarEngine window will open
3. Each instance runs independently

**Use Cases**:
- Testing multiple MIDlets simultaneously
- Comparing different configurations
- Development and debugging workflows
- Performance testing across instances

### Self-Destruct
**Purpose**: Configure automatic cleanup and resource management.

#### Activate
**Purpose**: Enable the self-destruct functionality.

**Features**:
- Automatic resource cleanup
- Memory optimization
- Performance monitoring
- Configurable cleanup intervals

**How to Use**:
1. Select **Activate** from the Self-Destruct submenu
2. Configure cleanup parameters in the dialog
3. Set cleanup intervals and thresholds

#### Deactivate
**Purpose**: Disable the self-destruct functionality.

**How to Use**:
1. Select **Deactivate** from the Self-Destruct submenu
2. Self-destruct features will be disabled
3. Manual resource management required

## 🔧 Advanced Configuration

### Theme Persistence
- Selected themes are automatically saved
- Themes persist across application restarts
- Custom theme configurations are preserved

### Performance Optimization
- Adaptive resolution affects rendering performance
- Theme selection impacts UI responsiveness
- Self-destruct features optimize long-running sessions

### Resource Management
- Automatic cleanup prevents memory leaks
- Performance monitoring tracks resource usage
- Configurable thresholds for optimization

## 🚀 Best Practices

1. **Choose Appropriate Resolution**: Match zoom level to your display and performance needs
2. **Theme Selection**: Use light themes for bright environments, dark themes for low-light
3. **Performance Balance**: Balance visual appeal with performance requirements
4. **Resource Monitoring**: Enable self-destruct for long gaming sessions

## ❓ Troubleshooting

**Problem**: Theme not applying
- **Solution**: Restart the application
- **Solution**: Check if the theme file is corrupted

**Problem**: Performance issues with high zoom
- **Solution**: Reduce zoom level to 1x or 1.25x
- **Solution**: Enable self-destruct for automatic optimization

**Problem**: Console not showing
- **Solution**: Ensure Console option is checked in Tune menu
- **Solution**: Check if console is minimized or hidden

---

*The Tune menu provides comprehensive customization options to make JarEngine work exactly how you want it. From visual themes to performance optimization, this menu gives you full control over your emulation experience.*
