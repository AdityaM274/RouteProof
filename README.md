# RouteProof

Evidence-aware route comparison on a fictional campus.

Created24October2026. Aditya Mittal authorized the project and Codex generated design, code, tests and documentation. No manual human implementation or real-user testing claimed. No external code/assets/packages or runtime AI. MIT licensed.

Run: python -m http.server 4183, then open localhost:4183. Tests: npm test (Node built-in runner; no npm install). Use any ordinary static web hosting. Nothing is sent to a server or persisted.

Dataset is fictional and inspections synthetic, not PCU campus data. Not a real accessibility/safety guarantee. Dijkstra minimizes distance only among paths satisfying encoded conditions. All exclusions and underlying data accompany a reviewed receipt; any input edit invalidates approval. Max100nodes/1000edges in solver; UI uses a fixed demo graph.
