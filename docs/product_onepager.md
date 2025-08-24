# ISLBridge — Product One-Pager (Phase 0)

## 1. MVP Scope
- **Vocabulary size:** 50–100 ISL signs  
- **Covered categories:**
  - Greetings (hello, thank you, sorry, good morning, etc.)
  - WH-questions (who, what, where, when, why, how)
  - Yes/No gestures
  - Numbers 0–10
  - Urgent phrases (help, water, doctor, bathroom, hungry, etc.)

## 2. Targets / Success Metrics
- **Latency:** < 1 second per sign on a mid-range Android phone (SDK 26+).  
- **Accuracy:** > 90% top-1 accuracy on MVP vocabulary.  
- **Sentence mode:** Word Error Rate (WER) < 15%.  

## 3. Platforms / Devices
- **In scope:** Android (SDK 26+).  
- **Out of scope for MVP:** iOS (to be added in later phases).  

## 4. Privacy Principles
- Default: **On-device inference** (no sign/video sent to server).  
- Optional: **Opt-in cloud mode** for heavier models (for improved accuracy/extended vocab).  

## 5. Success Demo Script
**Scenario:** Live demonstration to show end-to-end pipeline.  

1. **Input:** User signs “Hello, how are you?”  
2. **Processing:** Model recognizes each sign in real time.  
3. **Output:**  
   - Text on screen: “Hello, how are you?”  
   - Speech generated in selected language (Hindi / Tamil / English).  

## 6. Out of Scope (Phase 0 / MVP)
- Support for multiple signers / different signing speeds.  
- Full ISL vocabulary (>2000 signs).  
- Non-Android platforms (iOS, Web).  

---
Add Phase 0 one-pager.
