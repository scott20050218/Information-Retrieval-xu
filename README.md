### **Project Proposal: SearchNewsEngine - A Real-time News Topic Tracking System with Parallel Computing**

#### **1. Project Name**

**SearchNewsEngine**

#### **2. Team Members & Team Name**

Rui Li, Junhan Hao
Team Name: P.B group

#### **3. Problem Statement**

In the age of information explosion, news media face significant challenges:

- **Information Overload:** Inability to manually track all news sources in real-time.
- **Trend Lag:** Difficulty in promptly identifying emerging topics, leading to missed hotspots.

#### **4. How We Incorporate Parallel Computing**

    Parallel Data Ingestion :

        Create multiple producer threads, each independently responsible for crawling data from different news sources (e.g., RSS Feeds from BBC, Reuters, CNN).

        This significantly improves data collection throughput, preventing one slow source from slowing down the entire system.

#### **5. How We Incorporate Information Retrieval**

    Indexing:

        Build a full-text inverted index for all processed news.


    Searching/Filtering:

        Search Bar: Users can input keywords to retrieve relevant topics and historical news.


    Ranking & Recommendation:

        Search results are sorted by relevance.

