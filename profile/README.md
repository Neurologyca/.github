# Neurologyca

**Human context for apps, agents and enterprise software.** Real-time indicators of stress, engagement, cognitive load and more, computed by Neurologyca Engine from face and voice signals captured in the browser.

[Website](https://www.neurologyca.com) · [DevLab](https://devlab.neurologyca.com) · [Documentation](https://devlab.neurologyca.com/docs/) · [Quickstart](https://devlab.neurologyca.com/docs/start/quickstart/)

---

### SDKs

| Package | Version | What it does |
| --- | --- | --- |
| [`@neurologyca/capture`](https://www.npmjs.com/package/@neurologyca/capture) | [![npm](https://img.shields.io/npm/v/@neurologyca/capture?label=npm&color=0969da)](https://www.npmjs.com/package/@neurologyca/capture) | Browser SDK: webcam and microphone capture for Neurologyca Engine, live on-device or record-and-upload. |
| [<code>@neurologyca/capture&#8209;server</code>](https://www.npmjs.com/package/@neurologyca/capture-server) | [![npm](https://img.shields.io/npm/v/@neurologyca/capture-server?label=npm&color=0969da)](https://www.npmjs.com/package/@neurologyca/capture-server) | Server half of the SDK: short-lived tokens, Engine proxy, upload receiver and webhooks. Your API key never reaches the browser. |
| [`@neurologyca/kodec`](https://www.npmjs.com/package/@neurologyca/kodec) | [![npm](https://img.shields.io/npm/v/@neurologyca/kodec?label=npm&color=0969da)](https://www.npmjs.com/package/@neurologyca/kodec) | Browser-native affective signal codec: face landmarks, blendshapes, head pose and speech, computed on-device. |

Source mirrors: [`capture-js`](https://github.com/Neurologyca/capture-js) · [`kodec-js`](https://github.com/Neurologyca/kodec-js)

> Anyone can install the SDKs from npm. Using them requires an API key from a [DevLab](https://devlab.neurologyca.com) account. The SDKs are proprietary and governed by the [Neurologyca SDK License](https://devlab.neurologyca.com/legal/sdk-license/). The capture SDK is in [Preview](https://devlab.neurologyca.com/docs/resources/release-phases/).

### Build with your coding agent

Neurologyca publishes agent skills and plain-text documentation so coding agents follow the verified integration steps instead of guessing. Install the skills with `npx skills add https://devlab.neurologyca.com`, or see [Build with your coding agent](https://devlab.neurologyca.com/docs/start/ai-agents/) and [`llms.txt`](https://devlab.neurologyca.com/llms.txt).

### Privacy and responsible use

Facial geometry is biometric data. In on-device mode the video stays in the browser, but facial landmarks, expression coefficients and head pose are sent to Engine; in deferred mode, the recording is uploaded. Before you capture, read:

- [Privacy and data](https://devlab.neurologyca.com/docs/resources/privacy/): what leaves the device in each mode, and retention layer by layer.
- [Responsible use](https://devlab.neurologyca.com/docs/guides/responsible-use/): what the readings are never for.
- [Biometric and Emotion-Inference Addendum](https://devlab.neurologyca.com/legal/biometric-addendum/), [Acceptable Use Policy](https://devlab.neurologyca.com/legal/aup/) and all [legal documents](https://devlab.neurologyca.com/legal/).

### Contact

- Technical support: [support@neurologyca.com](mailto:support@neurologyca.com) · [how to get help](https://github.com/Neurologyca/.github/blob/main/SUPPORT.md)
- Security: [report a vulnerability](https://github.com/Neurologyca/.github/blob/main/SECURITY.md)
- Legal and privacy: [info@neurologyca.com](mailto:info@neurologyca.com)
- [LinkedIn](https://www.linkedin.com/company/neurologyca/)
