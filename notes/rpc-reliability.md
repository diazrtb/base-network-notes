# RPC Reliability

RPC providers are an important part of applications that communicate with Base.

## Reliability Considerations

When working with RPC services, developers should consider:

- Request failures
- Response latency
- Rate limits
- Temporary network errors
- Provider availability

Applications can handle temporary RPC problems by retrying appropriate requests, showing clear error messages, and avoiding unnecessary repeated calls.

Keeping RPC behavior predictable can improve the reliability of blockchain applications.
## Request Optimization

Applications can improve RPC performance by reducing unnecessary requests.

Useful practices include:

- Cache data that does not change frequently.
- Batch related read operations when possible.
- Avoid repeatedly requesting the same data.
- Limit unnecessary polling.
- Handle rate limits gracefully.

Efficient request patterns can reduce latency and make applications more reliable.
