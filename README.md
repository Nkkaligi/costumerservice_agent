# NovaSound X1 Customer Support Agent

A multi-phase AI customer support agent built with RAG, MCP tools, and a Gradio interface.

## Features

- **Product Q&A (RAG)**  
  Answers questions about battery life, warranty, Bluetooth pairing, noise cancellation, and more using a ChromaDB knowledge base + OpenAI.

- **Order & Ticket Tools (MCP)**  
  - Check order status  
  - Create support tickets  
  - View ticket status  
  All actions are scoped to the authenticated demo customer.

- **Human-in-the-loop Refunds (Phase 3)**  
  - Customers can request refunds  
  - Only authorized reviewers can approve/reject  
  - Full audit trail  
  - No real payments are ever processed

- **Gradio Dashboard**  
  - Customer chat interface  
  - Separate Reviewer panel for pending refunds

## Tech Stack

- OpenAI (chat + embeddings)
- ChromaDB
- FastMCP (Model Context Protocol)
- SQLite
- Gradio
- Designed to run in Google Colab or locally

## Demo Tokens

| Role     | Token                 |
|----------|-----------------------|
| Alice    | `demo-alice-token`    |
| Bob      | `demo-bob-token`      |
| Reviewer | `demo-reviewer-token` |

## Project Structure
