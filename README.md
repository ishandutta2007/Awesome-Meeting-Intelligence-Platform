# Awesome-Meeting-Intelligence-Platform

## Top Meeting Intelligence Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Meeting Transcription, Conversation Intelligence, AI Meeting Notes & Sales Intelligence*

**Last updated: September 2026**



This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Meeting Intelligence Platforms**. These tools record, transcribe, diarize, summarize, search, analyze, and extract actionable intelligence from meetings, interviews, sales calls, customer conversations, and team discussions.



**Examples** include Otter.ai, Fireflies.ai, Gong, Avoma, Fathom, Grain, Read AI, Sembly AI, Supernormal, tl;dv, Chorus.ai, Jamie AI, and MeetGeek.



Modern meeting-intelligence platforms typically combine **audio/video capture, speech-to-text, speaker identification, meeting summaries, action-item extraction, searchable meeting libraries, conversational analytics, CRM synchronization, sales coaching, sentiment/topic analysis, follow-up automation, AI chat over meetings, and increasingly real-time AI assistance**.



**Open-source emphasis**: This section is heavily expanded with active projects for **local/self-hosted meeting transcription, speaker diarization, AI summaries, searchable meeting memory, voice activity detection, audio capture, speech-to-text, LLM processing, RAG, meeting bots, and developer frameworks** — ideal for organizations that want meeting intelligence without sending sensitive conversations to a third-party SaaS.



> **Important distinction:** Open-source meeting transcription is considerably more mature than open-source **enterprise conversation intelligence**. Projects such as Meetily, Meet2Notes, OpenWhispr, Wisp, and zabt.ai can provide strong foundations for self-hosted meeting notes and transcription, while sales-specific capabilities such as CRM intelligence, pipeline analytics, coaching, deal-risk detection, and revenue intelligence generally require additional development.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.



## Table of Contents



* [SaaS/Hosted Platforms](#saashosted-platforms)

* [Open-Source GitHub Projects](#open-source-github-projects)

* [Local Meeting Assistants](#local-meeting-assistants)

* [Speech-to-Text & Transcription](#speech-to-text--transcription)

* [Speaker Diarization](#speaker-diarization)

* [Audio/Video Capture](#audiovideo-capture)

* [AI Summarization & Meeting Memory](#ai-summarization--meeting-memory)

* [RAG & Semantic Search](#rag--semantic-search)

* [Workflow & Automation](#workflow--automation)

* [Recommended Open-Source Architecture](#recommended-open-source-architecture)

* [Commercial → Open-Source Mapping](#commercial--open-source-mapping)

* [Open-Source Capability Matrix](#open-source-capability-matrix)

* [How to Contribute](#how-to-contribute)

* [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



* **[Otter.ai](https://otter.ai/)**

  AI meeting assistant providing real-time transcription, speaker identification, meeting summaries, searchable conversations, and collaboration features.



* **[Fireflies.ai](https://fireflies.ai/)**

  AI meeting assistant for recording, transcription, summarization, conversation search, action items, integrations, and meeting analytics.



* **[Gong](https://www.gong.io/)**

  Revenue intelligence and conversation-intelligence platform analyzing sales calls, meetings, emails, and customer interactions to support sales teams and revenue organizations.



* **[Avoma](https://www.avoma.com/)**

  AI meeting assistant combining transcription, meeting notes, conversation intelligence, coaching, revenue intelligence, and CRM workflows.



* **[Fathom](https://fathom.video/)**

  AI meeting assistant providing recording, transcription, summaries, action items, and searchable meeting information.



* **[Grain](https://grain.com/)**

  Meeting recording and conversation-intelligence platform supporting transcription, searchable conversations, clips, highlights, and collaborative meeting insights.



* **[Read AI](https://www.read.ai/)**

  Meeting and conversation intelligence platform analyzing meetings, engagement, sentiment, participation, summaries, and follow-up information.



* **[Sembly AI](https://www.sembly.ai/)**

  AI meeting assistant providing transcription, summaries, action items, meeting analytics, and integrations.



* **[Supernormal](https://supernormal.com/)**

  AI meeting-notes platform that automatically generates structured meeting notes, summaries, action items, and documentation.



* **[tl;dv](https://tldv.io/)**

  AI meeting recorder and assistant providing transcription, summaries, searchable meetings, clips, and meeting insights.



* **[Chorus](https://www.zoominfo.com/products/chorus)**

  Conversation-intelligence platform from ZoomInfo focused on sales calls, customer conversations, deal intelligence, coaching, and revenue workflows.



* **[Jamie](https://www.meetjamie.ai/)**

  AI meeting assistant providing meeting transcription, notes, summaries, and action-item extraction.



* **[MeetGeek](https://meetgeek.ai/)**

  AI meeting assistant supporting automatic recording, transcription, summaries, action items, meeting analytics, and workflow integrations.



* **[Notta](https://www.notta.ai/)**

  AI transcription and meeting-notes platform supporting multilingual transcription, summaries, recordings, and collaboration.



* **[Fireflies Conversation Intelligence](https://fireflies.ai/)**

  Conversation analytics layer for extracting topics, action items, insights, and customer intelligence from meeting transcripts.



* **[Microsoft Teams Premium / Copilot](https://www.microsoft.com/microsoft-365/microsoft-teams/teams-premium)**

  Enterprise collaboration and AI ecosystem incorporating meeting transcription, intelligent recap, summaries, action items, and meeting assistance.



* **[Google Meet + Gemini](https://workspace.google.com/products/meet/)**

  Integrated meeting intelligence providing transcription, meeting summaries, notes, action items, and AI assistance within Google Workspace.



* **[Zoom AI Companion](https://www.zoom.com/en/ai-assistant/)**

  Meeting AI ecosystem providing summaries, meeting questions, action items, and conversation assistance.



* **[Microsoft Copilot](https://www.microsoft.com/microsoft-copilot)**

  AI assistant integrated into Microsoft productivity and meeting workflows, including meeting recap and conversation assistance.



* **[Granola](https://www.granola.ai/)**

  AI meeting-notes application focused on transforming conversations into structured notes and searchable meeting knowledge.



* **[Krisp AI Meeting Assistant](https://krisp.ai/)**

  AI meeting assistant combining noise cancellation, transcription, meeting notes, and conversation intelligence.



* **[Colibri.ai](https://colibri.ai/)**

  Real-time meeting transcription and conversation intelligence platform for meetings, calls, and searchable transcripts.



* **[MeetRecord](https://www.meetrecord.com/)**

  AI sales meeting platform providing call recording, transcription, summaries, coaching, and sales intelligence.



* **[Salesloft](https://www.salesloft.com/)**

  Revenue platform incorporating conversation intelligence, sales engagement, coaching, and customer-interaction analytics.



* **[Outreach](https://www.outreach.io/)**

  Sales execution platform incorporating conversation intelligence and AI-assisted revenue workflows.



## Open-Source GitHub Projects



> The projects below are grouped according to their role in constructing an open-source Meeting Intelligence Platform.

>

> **The strongest direct open-source alternatives are currently Meetily, Meet2Notes, OpenWhispr, zabt.ai, Wisp, and related local-first meeting assistants.** Other projects such as Whisper, WhisperX, pyannote.audio, Silero VAD, Ollama, llama.cpp, and vector databases are critical building blocks rather than complete meeting applications.



### Local Meeting Assistants



* **[Meetily](https://github.com/Zackriya-Solutions/meetily)**

  Privacy-first, open-source AI meeting assistant supporting local recording, real-time transcription, AI summaries, and local/offline processing. Built around Whisper/Parakeet and local AI workflows.



* **[Meet2Notes](https://github.com/estebanstifli/Meet2Notes)**

  Open-source, self-hosted meeting assistant for Windows, macOS, and Linux with local transcription, speaker diarization, AI meeting notes, searchable meeting history, RAG, and local MCP support.



* **[OpenWhispr](https://github.com/OpenWhispr/openwhispr)**

  Open-source privacy-first voice and meeting application supporting local speech-to-text, meeting transcription, notes, AI actions, and multiple local/cloud model options.



* **[zabt.ai](https://github.com/afeef/zabt-ai)**

  Self-hosted AI meeting intelligence platform providing transcription, speaker diarization, and LLM-generated meeting summaries. Uses faster-whisper, pyannote, FastAPI, PostgreSQL, Redis, and object storage.



* **[Wisp](https://github.com/ppXD/Wisp)**

  Local, real-time meeting transcription application with speaker diarization, word-level timestamps, local AI processing, searchable meeting memory, and Markdown export.



* **[Kuali](https://github.com/igarrux/kuali)**

  Open-source local meeting transcription system supporting Discord and Google Meet with participant-aware speaker attribution, searchable meeting history, summaries, decisions, questions, and tasks.



* **[Millet](https://github.com/pretyflaco/millet)**

  Fully local meeting transcription and summarization pipeline using WhisperX and pyannote for diarized transcripts, with Markdown and PDF output.



* **[Scriba](https://github.com/AlexanderAbramovPav/scriba)**

  Local meeting transcription tool/agent skill using WhisperX and pyannote for speaker-labeled transcripts, designed to work with AI coding agents and second-brain workflows.



### Additional Strong Local Meeting Options



* **[Hyprnote](https://github.com/HyprNote/Hyprnote)**

  Open-source, privacy-focused AI note-taking application designed for meetings and personal knowledge capture.



* **[Screenpipe](https://github.com/mediar-ai/screenpipe)**

  Open-source, local-first capture system for screen, audio, OCR, and searchable personal context. Useful as a foundation for meeting-memory and AI-assistant systems.



* **[Buzz](https://github.com/chidiwilliams/buzz)**

  Open-source desktop application using Whisper for transcription and translation of audio recordings.



* **[MacWhisper](https://github.com/matthewhonnibal/macwhisper)**

  Community/open-source ecosystem around local Whisper transcription workflows. Verify the current repository/license before treating it as a full open-source product.



### Speech-to-Text & Transcription



* **[OpenAI Whisper](https://github.com/openai/whisper)**

  Open-source automatic speech-recognition model supporting multilingual transcription and translation.



* **[Whisper.cpp](https://github.com/ggml-org/whisper.cpp)**

  C/C++ implementation of Whisper designed for efficient local inference across desktop and embedded environments.



* **[faster-whisper](https://github.com/SYSTRAN/faster-whisper)**

  High-performance Whisper implementation using CTranslate2, suitable for local and server-side meeting transcription.



* **[WhisperX](https://github.com/m-bain/whisperX)**

  Transcription pipeline providing word-level timestamps and speaker-diarization integration.



* **[WhisperLive](https://github.com/collabora/WhisperLive)**

  Open-source real-time Whisper transcription server for low-latency speech recognition.



* **[WhisperLiveKit](https://github.com/QuentinFuxa/WhisperLiveKit)**

  Open-source real-time speech-transcription stack supporting streaming transcription and speaker-related workflows.



* **[Vosk](https://github.com/alphacep/vosk-api)**

  Offline speech-recognition toolkit supporting multiple languages and relatively lightweight deployment.



* **[Kaldi](https://github.com/kaldi-asr/kaldi)**

  Established open-source speech-recognition toolkit useful for advanced ASR research and custom pipelines.



* **[SpeechBrain](https://github.com/speechbrain/speechbrain)**

  Open-source speech and audio AI toolkit supporting speech recognition, speaker recognition, enhancement, and related tasks.



* **[NVIDIA NeMo](https://github.com/NVIDIA/NeMo)**

  Open-source conversational AI and speech-AI framework supporting ASR, speaker recognition, diarization, and language models.



* **[FunASR](https://github.com/modelscope/FunASR)**

  Open-source speech-recognition toolkit supporting ASR, voice activity detection, punctuation, and related speech processing.



* **[sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)**

  Offline speech-processing toolkit supporting speech recognition, speaker identification, VAD, and multiple deployment environments.



### Speaker Diarization



* **[pyannote.audio](https://github.com/pyannote/pyannote-audio)**

  Open-source speaker-diarization toolkit for identifying speaker turns and assigning speech segments to speakers.



* **[NVIDIA NeMo](https://github.com/NVIDIA/NeMo)**

  Provides speaker-recognition and diarization capabilities that can be incorporated into meeting pipelines.



* **[SpeechBrain](https://github.com/speechbrain/speechbrain)**

  Provides speaker recognition, verification, separation, and speech-processing components.



* **[sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)**

  Supports local speaker-related processing and diarization-oriented workflows.



* **[WhisperX](https://github.com/m-bain/whisperX)**

  Integrates transcription, alignment, and speaker diarization into one pipeline.



### Audio/Video Capture



* **[FFmpeg](https://github.com/FFmpeg/FFmpeg)**

  Core open-source multimedia framework for recording, decoding, converting, mixing, and processing meeting audio/video.



* **[PipeWire](https://gitlab.freedesktop.org/pipewire/pipewire)**

  Modern Linux multimedia framework useful for capturing microphone and system audio.



* **[PulseAudio](https://github.com/pulseaudio/pulseaudio)**

  Linux sound-server infrastructure useful for audio capture and routing.



* **[GStreamer](https://github.com/GStreamer/gstreamer)**

  Open-source multimedia framework for real-time audio/video capture and processing.



* **[OBS Studio](https://github.com/obsproject/obs-studio)**

  Open-source recording and streaming application useful for meeting capture workflows and custom integrations.



* **[WebRTC](https://github.com/webrtc/webrtc)**

  Open-source real-time communication technology useful for browser-based meeting capture, audio/video transport, and custom meeting applications.



### AI Summarization & Meeting Memory



* **[Ollama](https://github.com/ollama/ollama)**

  Local LLM runtime useful for private meeting summarization, action-item extraction, classification, and meeting Q&A.



* **[llama.cpp](https://github.com/ggml-org/llama.cpp)**

  Efficient local LLM inference framework suitable for running meeting-summary models on local hardware.



* **[vLLM](https://github.com/vllm-project/vllm)**

  High-performance LLM inference engine suitable for self-hosted meeting-intelligence servers.



* **[Hugging Face Transformers](https://github.com/huggingface/transformers)**

  Open-source machine-learning framework providing access to a large ecosystem of language and multimodal models.



* **[LlamaIndex](https://github.com/run-llama/llama_index)**

  Framework for connecting LLMs to meeting transcripts, documents, vector databases, and knowledge bases.



* **[LangChain](https://github.com/langchain-ai/langchain)**

  Framework for building LLM applications such as meeting assistants, summarization pipelines, agents, and conversational search.



* **[Haystack](https://github.com/deepset-ai/haystack)**

  Open-source framework for retrieval-augmented generation, semantic search, document processing, and LLM applications.



* **[DSPy](https://github.com/stanfordnlp/dspy)**

  Framework for programming and optimizing LLM pipelines, potentially useful for structured meeting-intelligence extraction.



### RAG & Semantic Search



* **[Qdrant](https://github.com/qdrant/qdrant)**

  Open-source vector database useful for semantic search over meeting transcripts.



* **[Milvus](https://github.com/milvus-io/milvus)**

  Scalable vector database for meeting-memory and enterprise semantic-search applications.



* **[Weaviate](https://github.com/weaviate/weaviate)**

  Open-source vector database suitable for transcript search, meeting knowledge bases, and RAG.



* **[Chroma](https://github.com/chroma-core/chroma)**

  Developer-friendly open-source embedding/vector database useful for local meeting-memory applications.



* **[pgvector](https://github.com/pgvector/pgvector)**

  PostgreSQL extension for vector similarity search, useful when meeting metadata and embeddings should remain in one database.



* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**

  Search and analytics engine suitable for full-text and semantic meeting search.



* **[SQLite](https://github.com/sqlite/sqlite)**

  Lightweight database suitable for local meeting libraries and transcript storage.



### Workflow & Automation



* **[n8n](https://github.com/n8n-io/n8n)**

  Workflow automation platform useful for automatically sending meeting summaries to CRM, email, Slack, Notion, project-management systems, and other applications.



* **[Node-RED](https://github.com/node-red/node-red)**

  Flow-based automation framework useful for integrating transcription pipelines, events, APIs, and meeting workflows.



* **[Temporal](https://github.com/temporalio/temporal)**

  Durable workflow engine suitable for long-running meeting-processing pipelines.



* **[Apache Airflow](https://github.com/apache/airflow)**

  Workflow orchestration platform useful for batch transcription, indexing, analytics, and reporting.



* **[Windmill](https://github.com/windmill-labs/windmill)**

  Developer-oriented workflow automation platform useful for meeting-processing jobs and internal AI workflows.



### Analytics & Dashboards



* **[Grafana](https://github.com/grafana/grafana)**

  Dashboards for meeting-processing infrastructure, usage, latency, transcription jobs, and AI-system observability.



* **[Metabase](https://github.com/metabase/metabase)**

  Self-hosted BI platform suitable for meeting analytics, participation trends, meeting volumes, and team metrics.



* **[Apache Superset](https://github.com/apache/superset)**

  Open-source BI platform for analyzing meeting and conversation datasets.



* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**

  High-performance analytics database suitable for large meeting and conversation datasets.



### Messaging & Infrastructure



* **[Apache Kafka](https://github.com/apache/kafka)**

  Event-streaming platform for large-scale audio-processing and meeting-intelligence pipelines.



* **[Redis](https://github.com/redis/redis)**

  Low-latency storage for queues, jobs, sessions, caching, and real-time meeting state.



* **[PostgreSQL](https://github.com/postgres/postgres)**

  Strong relational database for meetings, participants, transcripts, actions, integrations, permissions, and audit records.



* **[MinIO](https://github.com/minio/minio)**

  S3-compatible object storage for recordings, audio/video files, transcript artifacts, and model outputs.



* **[Docker](https://github.com/docker)**

  Containerization foundation for self-hosted meeting-intelligence deployments.



## Additional Strong Open-Source Options



* **[Meetily](https://github.com/Zackriya-Solutions/meetily)** for private local meeting recording, transcription, and AI summaries.

* **[Meet2Notes](https://github.com/estebanstifli/Meet2Notes)** for local transcription, speaker diarization, meeting notes, and RAG.

* **[OpenWhispr](https://github.com/OpenWhispr/openwhispr)** for local speech-to-text, meeting transcription, notes, and AI actions.

* **[zabt.ai](https://github.com/afeef/zabt-ai)** for self-hosted transcription, speaker diarization, and LLM summaries.

* **[Wisp](https://github.com/ppXD/Wisp)** for local real-time transcription, diarization, structured Markdown, and semantic meeting search.

* **[Kuali](https://github.com/igarrux/kuali)** for participant-aware local transcription of supported online meetings.

* **[Millet](https://github.com/pretyflaco/millet)** for offline diarized transcription and AI-generated meeting summaries.

* **[Scriba](https://github.com/AlexanderAbramovPav/scriba)** for local speaker-labeled transcription and AI-agent workflows.

* **[Hyprnote](https://github.com/HyprNote/Hyprnote)** for privacy-focused open-source AI note-taking.

* **[Screenpipe](https://github.com/mediar-ai/screenpipe)** for local screen/audio context capture and searchable AI memory.

* **[Buzz](https://github.com/chidiwilliams/buzz)** for local Whisper transcription.

* **[Whisper](https://github.com/openai/whisper)** for multilingual speech recognition.

* **[Whisper.cpp](https://github.com/ggml-org/whisper.cpp)** for efficient local Whisper inference.

* **[faster-whisper](https://github.com/SYSTRAN/faster-whisper)** for high-performance transcription.

* **[WhisperX](https://github.com/m-bain/whisperX)** for word-level timestamps and diarization pipelines.

* **[pyannote.audio](https://github.com/pyannote/pyannote-audio)** for speaker diarization.

* **[Silero VAD](https://github.com/snakers4/silero-vad)** for voice activity detection.

* **[Ollama](https://github.com/ollama/ollama)** for private local LLM inference.

* **[llama.cpp](https://github.com/ggml-org/llama.cpp)** for efficient local LLM execution.

* **[Qdrant](https://github.com/qdrant/qdrant)**, **[Weaviate](https://github.com/weaviate/weaviate)**, **[Milvus](https://github.com/milvus-io/milvus)**, and **[pgvector](https://github.com/pgvector/pgvector)** for meeting-memory search.

* **[LlamaIndex](https://github.com/run-llama/llama_index)** and **[Haystack](https://github.com/deepset-ai/haystack)** for RAG over meeting knowledge.

* **[n8n](https://github.com/n8n-io/n8n)** and **[Temporal](https://github.com/temporalio/temporal)** for meeting-workflow automation.



**Frameworks for building custom systems**: Combine **Meetily/Meet2Notes + Whisper/faster-whisper + pyannote.audio + Ollama + PostgreSQL/pgvector + Qdrant + n8n + MinIO** to build a self-hosted meeting-intelligence platform. Add **CRM integrations, sales analytics, speaker/topic classification, and domain-specific LLM agents** to approach the functionality of commercial conversation-intelligence platforms.



## Recommended Open-Source Architecture



```text

┌──────────────────────────────────────────────────────────────────┐

│                         MEETING SOURCES                          │

│                                                                  │

│ Zoom │ Teams │ Google Meet │ WebRTC │ Phone │ In-Person Audio    │

└───────────────────────────────┬──────────────────────────────────┘

                                │

                                ▼

┌──────────────────────────────────────────────────────────────────┐

│                       AUDIO CAPTURE                              │

│                                                                  │

│ FFmpeg │ PipeWire │ WebRTC │ GStreamer │ OBS │ System Audio     │

└───────────────────────────────┬──────────────────────────────────┘

                                │

                                ▼

┌──────────────────────────────────────────────────────────────────┐

│                    SPEECH PROCESSING                             │

│                                                                  │

│ Whisper │ faster-whisper │ WhisperX │ Vosk │ NeMo │ sherpa-onnx │

└───────────────────────────────┬──────────────────────────────────┘

                                │

                 ┌──────────────┴──────────────┐

                 ▼                             ▼

        ┌─────────────────┐           ┌─────────────────┐

        │ Speaker         │           │ Voice Activity  │

        │ Diarization     │           │ Detection       │

        │ pyannote.audio  │           │ Silero VAD      │

        └────────┬────────┘           └────────┬────────┘

                 └──────────────┬──────────────┘

                                ▼

                    ┌──────────────────────┐

                    │ Structured Transcript│

                    │ Speaker + Timestamp │

                    └──────────┬───────────┘

                               │

                               ▼

                    ┌──────────────────────┐

                    │ LLM / AI Processing  │

                    │                      │

                    │ Ollama / llama.cpp   │

                    │ vLLM / Transformers  │

                    └──────────┬───────────┘

                               │

            ┌──────────────────┼──────────────────┐

            ▼                  ▼                  ▼

       ┌─────────┐       ┌──────────┐       ┌──────────┐

       │ Summary │       │ Actions  │       │ Topics   │

       │ Minutes │       │ Decisions│       │ Sentiment│

       └────┬────┘       └────┬─────┘       └────┬─────┘

            └──────────────────┼──────────────────┘

                               ▼

                    ┌──────────────────────┐

                    │ Meeting Knowledge    │

                    │ Base / RAG           │

                    │                      │

                    │ Qdrant / pgvector    │

                    │ OpenSearch            │

                    └──────────┬───────────┘

                               │

              ┌────────────────┼────────────────┐

              ▼                ▼                ▼

        ┌───────────┐    ┌───────────┐   ┌─────────────┐

        │ AI Chat   │    │ Search    │   │ Analytics   │

        │ Meetings  │    │ Meetings  │   │ Dashboard   │

        └───────────┘    └───────────┘   └─────────────┘

                               │

                               ▼

                    ┌──────────────────────┐

                    │ Workflow Automation  │

                    │                      │

                    │ n8n / Temporal       │

                    └──────────┬───────────┘

                               │

             ┌─────────────────┼─────────────────┐

             ▼                 ▼                 ▼

           CRM              Slack             Email

        Salesforce        Microsoft Teams     Gmail

        HubSpot           Notion              Jira

```



## Commercial → Open-Source Mapping



| Commercial Platform | Open-Source Building-Block Strategy                                          |

| ------------------- | ---------------------------------------------------------------------------- |

| **Otter.ai**        | Meetily / Meet2Notes + Whisper + pyannote + Ollama                           |

| **Fireflies.ai**    | Meet2Notes / zabt.ai + WhisperX + pyannote + RAG                             |

| **Gong**            | Transcription + diarization + LLM + CRM data + custom conversation analytics |

| **Avoma**           | Meet2Notes + WhisperX + LLM + CRM integration + RAG                          |

| **Fathom**          | Meetily + Whisper/faster-whisper + Ollama + local RAG                        |

| **Grain**           | Screenpipe/WebRTC + transcription + searchable media + custom clip system    |

| **Read AI**         | WhisperX + pyannote + LLM + behavioral/meeting analytics                     |

| **Sembly AI**       | Meet2Notes + WhisperX + LLM + RAG + workflow automation                      |

| **Supernormal**     | Meetily + Whisper + Ollama + structured prompt templates                     |

| **tl;dv**           | Meetily/Meet2Notes + recording + transcription + RAG                         |

| **Chorus.ai**       | WhisperX + pyannote + LLM + CRM + conversation analytics                     |

| **Jamie AI**        | OpenWhispr / Meetily + Whisper + local LLM                                   |

| **MeetGeek**        | Meet2Notes + WhisperX + LLM + integrations                                   |

| **Granola**         | Hyprnote + local transcription + LLM + meeting memory                        |

| **Krisp AI**        | FFmpeg/PipeWire + Whisper + VAD + noise-processing stack                     |



> These mappings are **architectural equivalents, not drop-in replacements**. Commercial platforms include proprietary meeting integrations, cloud infrastructure, polished UX, enterprise controls, CRM integrations, analytics models, and specialized AI pipelines.



## Open-Source Capability Matrix



| Capability                | Meetily | Meet2Notes | OpenWhispr | zabt.ai | WhisperX | pyannote | Ollama |

| ------------------------- | ------: | ---------: | ---------: | ------: | -------: | -------: | -----: |

| Meeting Recording         |       ✅ |          ✅ |          ✅ |      ⚠️ |        ❌ |        ❌ |      ❌ |

| Real-Time Transcription   |       ✅ |          ✅ |          ✅ |      ⚠️ |       ⚠️ |        ❌ |      ❌ |

| File Transcription        |       ✅ |          ✅ |          ✅ |       ✅ |        ✅ |        ❌ |      ❌ |

| Speaker Diarization       |      ⚠️ |          ✅ |         ⚠️ |       ✅ |        ✅ |        ✅ |      ❌ |

| Speaker Recognition       |      ⚠️ |          ✅ |         ⚠️ |      ⚠️ |       ⚠️ |        ✅ |      ❌ |

| Meeting Summaries         |       ✅ |          ✅ |          ✅ |       ✅ |        ❌ |        ❌ |      ✅ |

| Action Items              |       ✅ |          ✅ |          ✅ |       ✅ |        ❌ |        ❌ |      ✅ |

| Meeting Q&A               |      ⚠️ |          ✅ |         ⚠️ |      ⚠️ |        ❌ |        ❌ |      ✅ |

| Searchable Meeting Memory |      ⚠️ |          ✅ |          ✅ |      ⚠️ |        ❌ |        ❌ |     ⚠️ |

| RAG                       |      ⚠️ |          ✅ |         ⚠️ |      ⚠️ |        ❌ |        ❌ |      ✅ |

| Local Processing          |       ✅ |          ✅ |          ✅ |       ✅ |        ✅ |        ✅ |      ✅ |

| Self-Hosted               |       ✅ |          ✅ |          ✅ |       ✅ |        ✅ |        ✅ |      ✅ |

| CRM Intelligence          |       ❌ |         ⚠️ |          ❌ |       ❌ |        ❌ |        ❌ |     ⚠️ |

| Sales Coaching            |       ❌ |         ⚠️ |          ❌ |       ❌ |        ❌ |        ❌ |     ⚠️ |

| Sentiment Analysis        |      ⚠️ |         ⚠️ |         ⚠️ |      ⚠️ |        ❌ |        ❌ |      ✅ |

| Topic Extraction          |      ⚠️ |          ✅ |         ⚠️ |       ✅ |        ❌ |        ❌ |      ✅ |



> `⚠️` indicates that the capability requires configuration, another component, or custom development.



## Best Open-Source Combinations



### Privacy-First Meeting Assistant



```text

Meetily

   +

Whisper / Parakeet

   +

Ollama

   +

SQLite

```



Best for:



* Individual professionals

* Sensitive meetings

* Offline transcription

* Private meeting notes

* Local AI



### Enterprise Self-Hosted Meeting Intelligence



```text

Meet2Notes / zabt.ai

        +

WhisperX

        +

pyannote.audio

        +

PostgreSQL

        +

MinIO

        +

Ollama / vLLM

        +

pgvector / Qdrant

        +

n8n / Temporal

        +

Grafana / Metabase

```



Best for:



* Enterprises

* Legal teams

* Healthcare organizations

* Financial institutions

* Internal meetings

* Privacy-sensitive organizations



### Open-Source Sales Conversation Intelligence



```text

Meeting Capture

      ↓

WhisperX

      ↓

pyannote.audio

      ↓

Speaker-Labeled Transcript

      ↓

LLM

      ↓

┌─────────────────────────────┐

│ MEDDIC / BANT / SPICED      │

│ Objection Detection         │

│ Competitor Mentions         │

│ Buying Signals              │

│ Next Steps                  │

│ Risk Signals                │

└──────────────┬──────────────┘

               ↓

          CRM Integration

               ↓

      Salesforce / HubSpot

```



### Private Meeting Knowledge Base



```text

Meetings

   ↓

WhisperX

   ↓

Diarization

   ↓

Transcript

   ↓

Embeddings

   ↓

Qdrant / pgvector

   ↓

RAG

   ↓

Ollama / vLLM

   ↓

"Ask My Meetings"

```



## What Open Source Can Replace



Open-source software can provide much of the technical foundation for:



* Meeting recording

* Audio capture

* Video capture

* Speech-to-text

* Speaker diarization

* Speaker recognition

* Timestamping

* Transcript storage

* Meeting summaries

* Action-item extraction

* Decision extraction

* Topic extraction

* Meeting search

* Semantic search

* RAG

* AI meeting chat

* Local LLM inference

* Meeting knowledge bases

* Workflow automation

* CRM synchronization

* Custom analytics

* Private/on-premise deployments

* Offline processing



## What Open Source Does Not Automatically Replace



A commercial platform such as Gong, Fireflies.ai, or Otter.ai may combine:



* Production-grade Zoom/Teams/Meet integrations

* Cloud-scale recording infrastructure

* Meeting bots

* Enterprise administration

* Calendar synchronization

* CRM integrations

* Sales methodology analytics

* Conversation scoring

* Sales coaching

* Revenue intelligence

* Team-wide behavioral analytics

* Enterprise support

* Compliance certifications

* Managed AI infrastructure

* Highly polished end-user applications



These capabilities can be built around open-source components but normally require substantial engineering.



## Suggested Open-Source Technology Stack



### Capture



```text

WebRTC

+

FFmpeg

+

PipeWire

+

GStreamer

+

OBS

```



### Transcription



```text

Whisper

/

faster-whisper

/

WhisperX

/

Whisper.cpp

/

sherpa-onnx

```



### Speaker Intelligence



```text

pyannote.audio

+

SpeechBrain

+

Silero VAD

```



### LLM



```text

Ollama

/

llama.cpp

/

vLLM

/

Transformers

```



### Meeting Memory



```text

PostgreSQL

+

pgvector

/

Qdrant

/

Weaviate

/

Milvus

```



### Automation



```text

n8n

/

Temporal

/

Airflow

```



### Storage



```text

MinIO

+

PostgreSQL

```



### Analytics



```text

ClickHouse

+

Grafana

+

Metabase

```



## Example Open-Source Meeting Intelligence Flow



```text

                         MEETING

                            │

                            ▼

                   ┌────────────────┐

                   │ Audio / Video  │

                   └───────┬────────┘

                           │

                           ▼

                   ┌────────────────┐

                   │ FFmpeg /       │

                   │ WebRTC / OS    │

                   │ Audio Capture  │

                   └───────┬────────┘

                           │

                           ▼

                   ┌────────────────┐

                   │ VAD / Noise    │

                   │ Processing     │

                   └───────┬────────┘

                           │

                           ▼

                   ┌────────────────┐

                   │ WhisperX /     │

                   │ faster-whisper │

                   └───────┬────────┘

                           │

                           ▼

                   ┌────────────────┐

                   │ Speaker        │

                   │ Diarization    │

                   │ pyannote       │

                   └───────┬────────┘

                           │

                           ▼

                 ┌─────────────────────┐

                 │ Structured          │

                 │ Transcript          │

                 └──────────┬──────────┘

                            │

                            ▼

                 ┌─────────────────────┐

                 │ LLM Processing      │

                 │ Ollama / vLLM       │

                 └──────────┬──────────┘

                            │

          ┌─────────────────┼──────────────────┐

          ▼                 ▼                  ▼

       Summary          Action Items       Decisions

          │                 │                  │

          └─────────────────┼──────────────────┘

                            ▼

                 ┌─────────────────────┐

                 │ Vector / Search DB  │

                 │ Qdrant / pgvector   │

                 └──────────┬──────────┘

                            │

             ┌──────────────┼──────────────┐

             ▼              ▼              ▼

          AI Chat        Search          Analytics

             │              │              │

             └──────────────┼──────────────┘

                            ▼

                    CRM / Slack / Email

```



## Privacy & Security



A self-hosted meeting-intelligence platform should consider:



* Encryption at rest

* TLS

* Access controls

* Role-based permissions

* SSO

* MFA

* Encryption of recordings

* Secure object storage

* Database encryption

* Audit logs

* Data-retention policies

* Automatic deletion

* Consent management

* Recording indicators

* Speaker-data protection

* PII detection/redaction

* Secrets management

* Model-access controls

* Tenant isolation



Potential open-source building blocks include:



* **[Keycloak](https://github.com/keycloak/keycloak)** — identity and SSO.

* **[Authentik](https://github.com/goauthentik/authentik)** — identity provider.

* **[Open Policy Agent](https://github.com/open-policy-agent/opa)** — policy enforcement.

* **[OpenBao](https://github.com/openbao/openbao)** — secrets management.

* **[Vault](https://github.com/hashicorp/vault)** — secrets management.

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — security and search analytics.



> Meeting recordings can contain highly sensitive personal, financial, medical, legal, or business information. Recording laws and consent requirements vary by jurisdiction. A technically local/self-hosted architecture does not by itself make a meeting-recording workflow legally compliant.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: project name, official/repository link, 1–2 sentence description, and whether it is SaaS or open-source.

4. For open-source projects, include the actual GitHub repository whenever available.

5. Clearly distinguish complete meeting assistants from transcription/AI building blocks.

6. Mention important licensing, maturity, privacy, or model-dependency limitations where relevant.

7. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



* This is a **community-curated** list — not exhaustive and not an endorsement.

* Commercial meeting-intelligence products change features, pricing, integrations, and AI capabilities frequently.

* Many open-source projects listed here are **components rather than complete replacements** for commercial meeting-intelligence platforms.

* Speech-recognition accuracy varies with language, accent, microphone quality, overlapping speech, background noise, and domain-specific terminology.

* Speaker diarization is probabilistic and should not automatically be treated as authoritative identity evidence.

* Meeting recording may be subject to consent, privacy, employment, data-protection, and sector-specific laws.

* Self-hosted deployments remain responsible for their own security, retention, access control, backups, and compliance.

* Always verify current project status, license, dependencies, supported operating systems, model licenses, and third-party service requirements before production deployment.



---



**Made for enterprises, sales teams, researchers, developers, knowledge workers, privacy-conscious organizations, and open-source AI builders.**

Let's make meeting intelligence more **private, transparent, searchable, interoperable, and developer-friendly**.
