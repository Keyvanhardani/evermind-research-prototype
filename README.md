# EverMind Research Prototype

EverMind is a research prototype exploring an agent architecture that can expand its knowledge without retraining the underlying language model.  
What may initially sound impractical or even impossible is already functioning in this prototype.

The system integrates new datasets from sources such as the Hugging Face Hub, Kaggle and custom collections within minutes and consolidates them into a scalable multi layer vector memory that preserves identity, behaviour and long term reasoning across sessions.

A self generated reward mechanism continuously reorganises this memory, enabling the agent to refine its understanding over time while the underlying language model remains external.  
All components operate on standard CPU hardware, allowing knowledge expansion without specialised compute resources.

---

## Key Features

### 1. Multi Layer Vector Memory
- Ingests new datasets in minutes  
- Stores embeddings and high level semantic structures  
- Maintains identity, behaviour and episodic knowledge  
- Operates fully on CPU hardware

### 2. External Language Model Integration
- Works with any local or API based LLM  
- The LLM is never retrained  
- System growth happens entirely in the memory architecture

### 3. Reward Driven Memory Reorganisation
- Internal self critique mechanism  
- Reinforces relevant information  
- Compresses and restructures older memory structures  
- Enables long term refinement without modifications to the model

### 4. Layered Memory Consolidation
- Large memory collections can be grouped into multi layer structures  
- Supports time based grouping, for example yearly layers  
- Supports size based grouping, for example fifty gigabyte working memory blocks  
- Enables long term knowledge retention with stable retrieval latency

### 5. Progressive Memory Layer Consolidation

EverMind maintains a layered memory architecture in which large volumes of collected knowledge are periodically consolidated into smaller compressed long term layers.  
For example, memory blocks of approximately fifty gigabytes can be summarised through the external language model into compact structured representations of about one gigabyte.  
These compressed layers act as long term semantic models that preserve global knowledge patterns while reducing latency and storage needs.

During retrieval, EverMind evaluates all memory layers in parallel on CPU hardware.  
This includes the active working memory, historical episodic layers and the compressed long term layers.  
The system does not require a GPU at any stage of this process.  
All consolidation, retrieval and scoring operations run entirely on standard CPU infrastructure.

---

## System Architecture

The architecture consists of:

- **Agent Core**  
  Coordinates retrieval, reasoning, learning cycles and interaction with the external language model.

- **Vector Memory**  
  Stores embeddings, episodic knowledge and the progressively consolidated long term memory layers.

- **Reward Mechanism**  
  Generates internal feedback signals and reorganises the memory based on relevance, coherence and stability.

- **External Language Model**  
  Executes reasoning and high level processing while remaining unchanged throughout the lifecycle of the agent.

- **CPU Hardware Layer**  
  Ensures that all memory operations run without GPU requirements.

---

## Use Cases
- Persistent AI agents  
- Long term knowledge systems  
- Memory augmented reasoning  
- Integration of large datasets without retraining  
- Low resource research on standard hardware

---

## Status
This repository contains an early stage research prototype.  
A detailed technical report is currently in preparation.

---

## Contact
For research collaboration inquiries, please reach out via GitHub or LinkedIn.
