# Coding test for Go developers: In-memory data structure store

Need to implement simple in-memory data structure store. See Redis for example.

Required data strutures:
- Strings
- Lists

Required operations:
- Get for strings
- Set for strings
- Update for strings
- Push back/front for lists
- Pop front/back for lists
- Remove for strings and lists

Required features:
- Keys with a limited TTL
- Go client API library
- HTTP REST API
- Data persistence (Postgres or sqlite)
  
Add unit tests for Go API and integration tests for REST API (without full coverage, just for example).

Optional features:
- Perfomance tests
- Authentication
