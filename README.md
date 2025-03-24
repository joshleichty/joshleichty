# 👋 Hi, I'm Josh 

**Low-level enthusiast | Full-stack tinkerer | Problem dissector**

```javascript
const currentInterests = {
  hackingOn: ["Embedded systems", "Real-time data pipelines", "Game engine architecture", "Web Development"],
  languages: ["Rust", "C", "TypeScript", "Python", "React"],
  customizing: ["Custom electronics", "Game modding"],
  rituals: ["Morning BJJ rolls", "Fighting games"]
};

function buildProfile() {
  return {
    philosophy: "Understand the layers beneath",
    approach: "First principles debugging",
    obsession: "Performance characteristics",
    guiltyPleasure: "Over-engineering weekend projects"
  };
}
```

## 🔧 Tech Arsenal

**Core Stack**
```
// Web ecosystems
const framework = Next.js({ suspense: true, serverActions: true });

// Tooling
$ cargo watch -x 'clippy --fix'
```

**Current Experiments**
- Implementing Pokemon emulator quirks in C
- Building CI pipelines for embedded Rust targets
- Reverse engineering fighting game netcode
- Making games in Three.js

## 🛠️ Active Projects

### [motion-ai](https://github.com/joshleichty/motion-ai) - AI Video Processor
*Next.js 14 | OpenAI Whisper | Stripe Payments*
- Built real-time video transcription pipeline with 93ms latency
- Designed custom rate limiter for UploadThing file processing
- Implemented Clerk auth with hardware security key enforcement

### [blocks](https://github.com/joshleichty/blocks) - Vulkan-Powered Sandbox
*C17 | SDL3 GPU API | GLSL Compute Shaders*
- Achieved 16ms chunk updates using spatial partitioning
- Developed hybrid PBR/deferred rendering pipeline
- Prototyped lock-free job system for terrain generation

### [social-media-data-dashboard](https://github.com/joshleichty/social-media-data-dashboard) - Analytics Engine
*Python 3.11 | Streamlit | CrowdTangle API*
- Reverse-engineered Twitter engagement prediction model
- Built CI pipeline for automated NLTK corpus updates
- Designed anomaly detection system for virality spikes

## 🔬 Technical Arsenal
**Core Competencies**
```rust
unsafe {
    // Memory management
    let mut arena: Arena<UnsafeCell<dyn Any>> = Arena::new();
    
    // Concurrency patterns
    crossbeam::scope(|s| {
        s.spawn(|_| poll_fd(futex, Ordering::AcqRel));
    }).unwrap();
}
```

**Toolchain Essentials**

[![Tech Stack](https://skillicons.dev/icons?i=rust,c,cpp,python,react,java,js,ts,wasm,neovim,git,linux,vim)](https://skillicons.dev)


## 📡 Open Channels
```vhdl
entity collaboration is
    port(
        embedded_rust   : in  std_logic;
        game_netcode    : in  std_logic;
        kernel_hacks    : in  std_logic;
        coffee          : out std_logic
    );
end collaboration;

architecture behavioral of collaboration is
begin
    coffee <= '1' when (embedded_rust or game_netcode or kernel_hacks) else '0';
end behavioral;
```
