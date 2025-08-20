# Tools Menu Documentation

The **Tools** menu is JarEngine's powerhouse, providing professional-grade development tools, performance monitoring, networking diagnostics, and recording capabilities. This menu transforms JarEngine from a simple emulator into a comprehensive development and testing platform.

## 🛠️ Menu Items

### Screenshot
**Purpose**: Capture and save screenshots of the current MIDlet display.

**Keyboard Shortcut**: `Ctrl+S`

**How to Use**:
1. Click **Screenshot** from the Tools menu
2. Or use the keyboard shortcut `Ctrl+S`
3. Screenshot is automatically saved with timestamp
4. Status bar shows save location and confirmation

**Features**:
- Automatic file naming with timestamps
- High-quality image capture
- Instant save to disk
- Status feedback and error handling

**File Format**: PNG format for optimal quality and compression

### FPS
**Purpose**: Monitor frame rate and performance metrics in real-time.

**How to Use**:
1. Click **FPS** from the Tools menu
2. FPS monitoring dialog opens
3. View real-time performance data
4. Monitor frame timing and rendering statistics

**Displayed Metrics**:
- Current FPS (Frames Per Second)
- Frame timing analysis
- Performance trends
- Rendering statistics

**Use Cases**:
- Performance optimization
- Game development testing
- Benchmarking applications
- Troubleshooting performance issues

### Performance
**Purpose**: Comprehensive performance tuning and optimization controls.

#### Hardware Acceleration
**Purpose**: Enable/disable hardware-accelerated rendering.

**Benefits**: Improved rendering performance, smoother graphics
**When to Use**: Modern systems with dedicated graphics

#### Anti-Aliasing
**Purpose**: Control image smoothing and edge quality.

**Benefits**: Cleaner, more professional appearance
**Performance Impact**: Moderate, depends on quality level

#### Double Buffering
**Purpose**: Enable smooth frame transitions and reduce flickering.

**Benefits**: Eliminates screen tearing, smoother animation
**Performance Impact**: Minimal, recommended for most use cases

#### Power Saving Mode
**Purpose**: Optimize performance for battery-powered devices.

**Benefits**: Extended battery life, reduced heat generation
**Performance Impact**: Slight reduction in maximum performance

#### Idle Skipping
**Purpose**: Skip frames when MIDlet is idle to save resources.

**Benefits**: Reduced CPU usage during inactive periods
**Use Cases**: Long-running applications, background processes

#### Frame Skipping
**Purpose**: Skip frames to maintain target FPS under load.

**Benefits**: Consistent performance, reduced stuttering
**When to Use**: Performance-critical applications, older hardware

#### Thread Priority Boost
**Purpose**: Increase priority of emulation threads.

**Benefits**: Better responsiveness, reduced input lag
**Use Cases**: Real-time applications, games

#### Input Throttling
**Purpose**: Control input processing frequency.

**Benefits**: Consistent input handling, reduced CPU usage
**Performance Impact**: Minimal, improves stability

#### Sprite Caching
**Purpose**: Cache frequently used graphics for faster rendering.

**Benefits**: Improved rendering performance, reduced memory allocation
**Memory Impact**: Moderate, trades memory for speed

#### Texture Filtering
**Purpose**: Control texture quality and filtering algorithms.

**Benefits**: Better image quality, smoother textures
**Performance Impact**: Depends on filtering quality

#### VSync
**Purpose**: Synchronize frame rendering with display refresh rate.

**Benefits**: Eliminates screen tearing, smoother animation
**Performance Impact**: May limit maximum FPS to refresh rate

#### Fluid Mode
**Purpose**: Enable advanced performance optimization algorithms.

**Benefits**: Adaptive performance tuning, intelligent resource management
**Use Cases**: Long gaming sessions, performance-critical applications

#### JVM Heap Size
**Purpose**: Configure Java Virtual Machine memory allocation.

**How to Use**:
1. Click **JVM Heap Size** from Performance submenu
2. Enter desired heap size in MB
3. Restart application for changes to take effect

**Recommended Settings**:
- **512MB**: Light applications, basic testing
- **1024MB**: Standard applications, moderate usage
- **2048MB**: Heavy applications, long gaming sessions
- **4096MB+**: Development environments, multiple instances

#### Reset Performance Settings
**Purpose**: Restore all performance settings to default values.

**How to Use**:
1. Click **Reset Performance Settings**
2. Confirm the reset operation
3. All settings return to optimized defaults

### Networking
**Purpose**: Advanced networking tools for development and testing.

#### Proxy Settings
**Purpose**: Configure HTTP/HTTPS proxy for network connections.

**Features**:
- HTTP and HTTPS proxy support
- Authentication configuration
- Bypass settings for local addresses

#### Network Monitor
**Purpose**: Real-time network activity monitoring.

**Displayed Information**:
- Active connections
- Data transfer rates
- Connection status
- Error tracking

#### Traffic Shaping
**Purpose**: Control network bandwidth and simulate network conditions.

**Features**:
- Bandwidth limiting
- Latency simulation
- Packet loss simulation
- Connection throttling

#### Connection Tester
**Purpose**: Test network connectivity and diagnose connection issues.

**Tests Available**:
- HTTP connectivity
- HTTPS connectivity
- DNS resolution
- Port availability

#### DNS Overrides
**Purpose**: Customize DNS resolution for testing and development.

**Use Cases**:
- Local development servers
- Testing environments
- Network debugging
- Custom domain resolution

#### Mock Server
**Purpose**: Create virtual network services for testing.

**Features**:
- HTTP response simulation
- Custom response codes
- Response body customization
- Request logging

#### TLS Settings
**Purpose**: Configure Transport Layer Security options.

**Options**:
- Trust all certificates (development mode)
- Custom certificate validation
- TLS version selection
- Cipher suite configuration

#### Packet Capture
**Purpose**: Capture and analyze network traffic.

**Features**:
- Real-time packet capture
- Protocol analysis
- Traffic filtering
- Export capabilities

#### Offline / Captive Portal
**Purpose**: Simulate offline conditions or captive portal scenarios.

**Modes**:
- **Offline**: Complete network isolation
- **Captive Portal**: Simulate captive portal detection

#### Network Metrics
**Purpose**: Comprehensive network performance analysis.

**Metrics Displayed**:
- Connection latency
- Throughput analysis
- Error rates
- Performance trends

#### UDP Tester
**Purpose**: Test UDP connectivity and performance.

**Features**:
- UDP packet transmission
- Echo testing
- Performance measurement
- Connection validation

#### Reset Network Settings
**Purpose**: Restore all network settings to default values.

**How to Use**:
1. Click **Reset Network Settings**
2. Confirm the reset operation
3. All network configurations return to defaults

### X-Render
**Purpose**: Advanced graphics rendering and filtering tools.

**How to Use**:
1. Click **X-Render** from the Tools menu
2. Configure rendering filters and effects
3. Apply custom graphics processing
4. Optimize visual quality and performance

**Features**:
- Custom filter chains
- Post-processing effects
- Performance optimization
- Quality vs. speed balancing

### Record
**Purpose**: Capture and record MIDlet sessions for analysis and sharing.

#### Start Capture
**Purpose**: Begin recording the current MIDlet session.

**How to Use**:
1. Click **Start Capture** from the Record submenu
2. Recording begins immediately
3. Status indicator shows recording state

**Features**:
- Real-time recording
- Automatic file management
- Quality settings
- Compression options

#### Stop Capture
**Purpose**: Stop the current recording session.

**How to Use**:
1. Click **Stop Capture** from the Record submenu
2. Recording stops and file is finalized
3. Recording file is saved automatically

**Output**: Recorded session file with timestamp

### Record Store Manager
**Purpose**: Manage MIDlet persistent data storage.

**Features**:
- View stored data
- Clear specific records
- Monitor storage usage
- Debug data persistence

**Access**: Must be enabled in Tune menu first

### Console
**Purpose**: Display detailed logging and debugging information.

**Features**:
- Real-time log output
- Error tracking
- Performance metrics
- Debug information

**Access**: Must be enabled in Tune menu first

## 🔧 Advanced Features

### Performance Profiling
- Real-time performance monitoring
- Automatic optimization suggestions
- Resource usage tracking
- Performance trend analysis

### Network Diagnostics
- Comprehensive connection testing
- Traffic analysis and monitoring
- Custom network simulation
- Advanced debugging tools

### Development Tools
- Screenshot capture and management
- Session recording capabilities
- Performance benchmarking
- Resource monitoring

## 🚀 Best Practices

1. **Performance Tuning**: Start with default settings and adjust based on your needs
2. **Network Testing**: Use offline mode for testing, enable networking for production
3. **Resource Monitoring**: Enable performance tools for long gaming sessions
4. **Development Workflow**: Use recording and screenshot tools for documentation

## ❓ Troubleshooting

**Problem**: Performance tools not responding
- **Solution**: Check if MIDlet is running
- **Solution**: Restart the application

**Problem**: Network tools not working
- **Solution**: Verify internet access is enabled
- **Solution**: Check proxy settings

**Problem**: Screenshot not saving
- **Solution**: Check disk space and permissions
- **Solution**: Verify save directory is accessible

---

*The Tools menu transforms JarEngine into a professional development platform. Whether you're optimizing performance, debugging network issues, or recording gameplay sessions, these tools provide everything you need for advanced MIDlet development and testing.*
