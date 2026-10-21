
# LifeFile

**Your proof, always at hand.**

LifeFile is an offline-first native iOS application that helps users keep receipts, warranties, and important purchase documents organized and easy to retrieve.

### Key Features
- Scan receipts and documents using the device camera.
- Extract text on-device using Apple Vision OCR.
- Store documents and structured records locally.
- Search receipts, purchases, and warranty details.
- Track warranty and return deadlines with reminders.
- Generate PDF evidence packs through the *Find My Proof* workflow.
- Review and correct extracted information before saving.

### Technology Stack
- **Language:** Swift
- **UI:** UIKit and Storyboards
- **Architecture:** MVVM, Clean Architecture, SOLID
- **Persistence:** Core Data and local file storage
- **OCR:** Apple Vision / VisionKit
- **Networking:** URLSession contracts for future backend integration
- **Testing:** XCTest

### Development Approach
LifeFile is being developed in iterations. The initial version prioritizes local storage, privacy, and offline functionality. Optional authentication, cloud backup, and device synchronization are planned for a future iteration.

*Project status: In development.*
