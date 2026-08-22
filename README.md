# Apache TVM (apache-tvm)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache TVM is an open-source compiler framework for deep learning that provides performance portability across CPUs, GPUs, FPGAs, and specialized accelerators. It automatically optimizes models from TensorFlow, PyTorch, ONNX, and other frameworks for edge and cloud deployment.

**URL:** [https://tvm.apache.org/](https://tvm.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Compiler, Deep Learning, Edge Computing, Model Optimization, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache TVM Python API
Comprehensive Python interface for model compilation, optimization, and deployment including tvm.relay, tvm.auto_scheduler, tvm.micro, and tvm.rpc modules.

**Human URL:** [https://tvm.apache.org/docs/reference/api/python/](https://tvm.apache.org/docs/reference/api/python/)

#### Tags:

 - Python, Deep Learning, Model Optimization, Compiler

#### Properties

- [Documentation](https://tvm.apache.org/docs/reference/api/python/)
- [Python Package (PyPI)](https://pypi.org/project/apache-tvm/)

### Apache TVM RPC API
Remote compilation, deployment, and profiling of optimized models on target devices for AutoTVM/AutoScheduler tuning jobs.

**Human URL:** [https://tvm.apache.org/docs/how_to/work_with_microtvm/](https://tvm.apache.org/docs/how_to/work_with_microtvm/)

#### Tags:

 - RPC, Remote, Profiling, Hardware

#### Properties

- [Documentation](https://tvm.apache.org/docs/how_to/work_with_microtvm/)

## Common Properties

- [GitHubRepository](https://github.com/apache/tvm)
- [Documentation](https://tvm.apache.org/docs/)
- [Portal](https://tvm.apache.org/)
- [GettingStarted](https://tvm.apache.org/docs/get_started/)
- [ReleaseNotes](https://github.com/apache/tvm/releases)
- [Support](https://discuss.tvm.apache.org/)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Multi-Framework Support | Import models from TensorFlow, PyTorch, ONNX, MXNet, Keras, and other frameworks. |
| Hardware-Specific Optimization | Automatic operator scheduling and kernel fusion for CPUs, GPUs, and accelerators. |
| Auto-Tuning | AutoTVM and AutoScheduler for automated compute kernel hyperparameter optimization. |
| MicroTVM | Deploy optimized models on microcontrollers and bare-metal devices. |
| BYOC Framework | Bring Your Own Codegen for integrating custom hardware accelerators. |
| Relay IR | High-level intermediate representation for end-to-end model optimization. |

## Use Cases

| Name | Description |
|------|-------------|
| Edge AI Deployment | Deploy optimized deep learning models on edge devices and microcontrollers. |
| Model Serving Optimization | Optimize inference performance for cloud GPU/CPU model serving. |
| Cross-Platform Deployment | Compile a single model for multiple hardware targets. |
| Custom Accelerator Integration | Integrate custom AI accelerators using TVM's BYOC framework. |

## Integrations

| Name | Description |
|------|-------------|
| ONNX | Import and optimize ONNX models from any ONNX-compatible ML framework. |
| PyTorch | TorchScript to TVM compilation for PyTorch model optimization. |
| TensorFlow | TensorFlow and TFLite model import and optimization. |
| NVIDIA CUDA | CUDA/cuDNN backend for NVIDIA GPU kernel generation and optimization. |
| ARM | ARM CPU (Cortex-A, Cortex-M) and ARM Mali GPU backend support. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
