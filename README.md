# Conversations with Tyler Semantic Search

Search the transcript history of Conversations with Tyler using the power of embeddings and semantic search. [Try it out](https://koratkar.github.io/cwt-semantic-search).

A few features will be added before I share this with more people:
- [ ] [tail free sampling](https://www.trentonbricken.com/Tail-Free-Sampling/) on the top similarity results (this is back-end)
- [ ] a cron job so that new conversations are uploaded to vector database automatically (this is back-end) – last podcast is #228
- [ ] a neat little loading bar while the results process
  - [ ] first, time the average "enter to result" for like ten queries
  - [ ] and then set that as the time in miliseconds for the result to load
  - [ ] make it hang for the last 10 percent until it's finished (like gmail)
