# Hi, I'm Ilia

QA Engineer focused on **automation, backend testing, and network-level analysis**.

I don’t just test UI — I analyze systems deeply: APIs, WebSockets, gRPC, and even low-level protocols.  
I build tools that help uncover issues that are invisible to standard testing approaches.

---

## Featured Projects

### Playwrite + C# Automated tests
👉 https://github.com/kazeboba/PlaywrightC-

#### What it does:
This project provides UI testing for user scenarios through a browser.
It follows the Page Object Model (POM) approach to separate test logic from page interactions.

#### Tech Stack
- .NET
- Playwright for .NET
- NUnit
- C#

#### Aproach
- Uses Page Object Model
- Locators are stored in Pages and Components
- Tests describe user behavior
- Avoids code duplication

### automation-proxy  
👉 https://github.com/kazeboba/automation-proxy  

Custom proxy built on top of mitmproxy for advanced traffic interception and manipulation.

#### What it does:
- Intercepts and modifies HTTP & WebSocket traffic
- Injects custom messages into active sessions
- Simulates server push events
- Allows runtime manipulation of backend responses

#### Problems it solves:
- Testing real-time features without full backend control
- Reproducing edge-case scenarios (timeouts, invalid states, race conditions)
- Debugging client-server interaction at protocol level
- Verifying app behavior under нестандартных серверных ответов

#### Tech:
- Python
- mitmproxy
- WebSockets
- Custom proxy handlers

---

### gRPC-tests  
👉 https://github.com/kazeboba/gRPC-tests  

Project for testing gRPC services and validating backend logic using Protocol Buffers.

#### What it does:
- Sends and validates gRPC requests
- Works directly with Protobuf schemas
- Tests services without UI dependency
- Can be used for integration and regression testing

#### Problems it solves:
- Testing microservices without relying on frontend
- Validating contracts between services
- Catching backend issues early in development

#### Tech:
- Python
- gRPC
- Protocol Buffers

---

## What I Do

- Backend testing (REST / gRPC)
- Test automation (Python + Airtest, Appium; C# + Playwright, XCUITEST for iOs, Airtest for Android)
- Network traffic analysis (HTTP, WebSocket)
- Reverse engineering client-server communication
- Building custom QA/debugging tools
- Integration testing (frontend ↔ backend)

---

## Toolbox

- Python / pytest
- Playwright / C#
- Python(Java) / Appium
- mitmproxy  
- gRPC / Protobuf  
- CI/CD (GitHub Actions, Jenkins)  
- Git  

---

## Problems I Like Solving

- “Works on backend but not on client” issues  
- Real-time bugs (WebSockets, push events)  
- Hard-to-reproduce edge cases  
- Inconsistent API behavior  
- Flaky tests and unstable environments  

---

## Focus

I’m especially interested in:
- Complex systems (real-time, event-driven)
- Backend-heavy products
- Deep debugging and observability
- Building tools that improve test coverage and reliability

---

## Contact

- GitHub: https://github.com/kazeboba
- Telegram: @iliaru351
- E-mail: iliarumyancev@gmail.com
