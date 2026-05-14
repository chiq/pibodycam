# pibodycam

Raspberry Pi body camera demo project for self-improvement across coding, AI-assisted development, embedded Linux, and project delivery.

## Skills and learning goals

1. LeetCode C (advanced)
2. LeetCode C++ (advanced)
3. LeetCode Python (advanced)
4. LeetCode Golang (basic)
5. Data structures and algorithms (C/C++/Python)
6. GitHub Copilot (advanced usage)
7. AI solutions for the full SDLC
8. Project management (PMP + Agile practice)
9. Embedded Linux and Yocto
10. End-to-end body camera demo on Raspberry Pi

## Demo project scope (Raspberry Pi body camera)

Build a working prototype that can:

- Capture video from a Raspberry Pi camera module
- Record timestamped clips on trigger (button or motion event)
- Store metadata (clip ID, start/end time, device info)
- Expose a simple local API for clip listing and download
- Run on a Yocto-based image for embedded deployment

## Suggested architecture

- **Device layer (C/C++)**: camera capture pipeline, low-level performance-sensitive logic
- **Service layer (Python/Golang)**: control service, metadata handling, local API
- **Algorithms layer**: event detection/motion heuristics and interview-style DSA practice modules
- **AI/SDLC layer**: GitHub Copilot workflows for requirements, coding, testing, review, and documentation
- **Delivery layer**: Agile sprint planning, backlog tracking, and milestone reviews

## Execution roadmap

### Phase 1: Foundations
- Set up Raspberry Pi hardware and camera
- Define backlog, acceptance criteria, and sprint cadence
- Start LeetCode/DSA routine (C/C++/Python advanced, Golang basic)

### Phase 2: Core functionality
- Implement camera capture and clip recording
- Add metadata indexing and clip lifecycle management
- Add unit-level checks where test tooling exists

### Phase 3: Embedded productization
- Create Yocto build with required runtime components
- Package and auto-start services on device boot
- Validate resource usage (CPU, memory, storage)

### Phase 4: AI + project delivery maturity
- Apply GitHub Copilot advanced patterns across coding/test/review
- Add AI-assisted SDLC checkpoints (design, test case generation, review prompts)
- Run Agile retrospectives and update roadmap from outcomes

## Definition of done

- Raspberry Pi records and stores playable camera clips
- Local API can list and retrieve clips with metadata
- Yocto image boots and starts the bodycam services automatically
- Project artifacts include sprint plan, risks, and measurable learning progress across all 10 goals
