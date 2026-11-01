
# Riftbound RAG — Proof of Concept

## Overview

This project explores the feasibility of building a Retrieval-Augmented Generation (RAG) assistant for the Riftbound Trading Card Game community.

The goal is to help players find relevant information about gameplay questions, card interactions, rules, and deck-building strategies.

## Project Status

Early-stage, non-commercial proof of concept. No Reddit data has been collected or processed.

## Proposed Functionality

- Retrieve a limited sample of posts and comments from r/riftboundtcg, subject to Reddit's approval.
- Preserve the context of questions, answers, and discussion threads.
- Explore semantic search using text embeddings and a vector database.
- Evaluate RAG-based question answering using a language model.
- Provide links to original discussions for source attribution.

## Proposed Technologies

- Python
- PRAW (Reddit API)
- Sentence Transformers
- ChromaDB or FAISS
- Large Language Model (LLM)

## Reddit API Usage

This project intends to use Reddit's official Data API for read-only access, subject to authorization.

The application will not automatically publish posts, submit comments, vote, or send messages.

Any retrieval, storage, embedding generation, or AI-assisted use of Reddit content will be subject to Reddit's applicable terms and explicit permissions.

The project will consider data minimization, deletion handling, and appropriate source attribution.

## Future Development

If the proof of concept demonstrates useful results and the necessary permissions are obtained, the project may be expanded into a publicly accessible question-answering assistant.

## Disclaimer

This is an independent experimental project and is not affiliated with or endorsed by Reddit, Riot Games, or Riftbound.
