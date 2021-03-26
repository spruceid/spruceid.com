# spruceid.com

This repo contains resources and configuration for [Spruce Systems, Inc.][]'s [Second-level domain][], `spruceid.com`.

## [Well-Known Resources][rfc8615]
- [did:web][] DID Document
- Matrix [client][matrix-client] and [server][matrix-server] homeserver delegation

## Other Resources
- [robots.txt](http://www.robotstxt.org)
- [favicon.ico](https://en.wikipedia.org/wiki/Favicon)

## [Netlify configuration][]
- Set headers for `well-known` resources: `Content-Type`, [Access-Control-Allow-Origin][]
- Redirect all other requests to the `www` subdomain.

[Access-Control-Allow-Origin]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Origin
[Spruce Systems, Inc.]: https://www.spruceid.com/
[Second-level domain]: https://en.wikipedia.org/wiki/Second-level_domain
[Netlify configuration]: https://docs.netlify.com/configure-builds/file-based-configuration/
[matrix-server]: https://matrix.org/docs/spec/server_server/r0.1.4#get-well-known-matrix-server
[matrix-client]: https://matrix.org/docs/spec/client_server/r0.6.1#get-well-known-matrix-client
[did:web]: https://w3c-ccg.github.io/did-method-web/
[rfc8615]: https://tools.ietf.org/html/rfc8615
