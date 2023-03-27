1. Phase-1 Features
- Single User
- Stateless Query/Response
- Synchronous Response
- No user feedback after submitting query
- Given a list of user-defined URLs and a topic, summarize its contents in less than 5 sentences
- Organize summary by URL into a list that can be replayed on-demand based on user's query
-- Upon user query, convert summary text-to-speech and play it as an audio stream feed 
- Provide a client interface to submit queries to this service

2. Phase-2 Features
- How to support multiple users ?
- How to make response stateful per user connection ?
- How to user feedback to jump/skip/pause playing summaries (not so interesting summaries) ?
- How to customize summarization per user feedback - give each summary a rating, e.g ?

3. Delivery Features
- How to deliver the service on the mobile platform and desktop platform ?
- How to provide login/auth capabilities per user ?
