# Describe Flow

## Purpose
Return a concise end-to-end flow description (frontend → backend → data) for the feature/scenario the user asks about, similar to detailed flow explanations like the AI chat flow.

## Steps
1) Read the question and provided context/files.  
2) Identify actors and steps: UI trigger, frontend calls/dispatches, server handlers/services, repositories/data writes/reads, callbacks to client.  
3) Describe the flow in order: trigger on frontend, network calls/handlers, backend services/repositories, data writes/reads, and what returns to the client.  
4) Keep it short but complete; note key branching, special cases, or missing info.

## Output format
- Use markdown bullet list.  
- Sections (only if present):  
  - Trigger (UI/action/dispatch/subscription)  
  - Frontend call (service/action, params)  
  - Backend handling (hub/router/service/repo)  
  - Data layer (DB/ontology/refs updates)  
  - Response back (events/callbacks to client)  
- Mention file/module names when known.  
- Highlight any important conditions (e.g., type checks, null guards, system vs non-system).

## Constraints
- No fluff or extra commentary; just the flow.  
- Be specific with function/method names if known.  
- If gaps exist or info is missing, state them briefly.


ОТВЕЧАЙ ВСЕГДА НА РУССКОМ ЯЗЫКЕ