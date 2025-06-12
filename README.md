# @gleanwork/typescript-sdk

This is a fork of [@modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) whose discovery falls back to `/.well-known/openid-configuration` for OAuth authorization servers that do not respond to `/.well-known/oauth-authorization-server`, like Google.

For more details see [this issue](https://github.com/modelcontextprotocol/typescript-sdk/issues/616).
