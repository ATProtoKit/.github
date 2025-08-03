<p align="center">
  <img src="https://github.com/ATProtoKit/.github/blob/main/resources/atprotokit_main_icon.png" height="128" alt="An icon for ATProtoKit family of Swift packages, which contains one large rounded rectangle in an 3D isometric top view. At the top stack, the @ symbol is in a white colour. The shape is a dark blue colour.">
</p>

<h1 align="center">The ATProtoKit Project</h1>

This is the official repository for ATProtoKit and its family of projects, including forks and semi-related projects that help ATProtoKit work. The goal is to create a fully Swift implementation of the AT Protocol, Bluesky, and any other services built on top of the protocol. The intention is to interoperate with the official TypeScript and Go implementations of the protocol.

With the exception of the main ATProtoKit repository and any forks, all repositories in the project are licensed under Apache 2.0. In order to comply with the licence, all you need to do is attach the licence and mention the existence of the package(s) in your Credits or Contributions page. If you’re using the Swift Package Manager or some other manager that pulls in the code, the first part should already be compliant.

> **Note**: Even though the main ATProtoKit repository is under the MIT licence, please do consider also crediting the Swift package.

This is a work-in-progress and many things may break or not work. Contributions and donations are welcome!

## Swift Packages

| Package                        | Documentation                                                                                    | Swift Package Index                                                                                         | Source Code                 |
| ------------------------------ | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- | --------------------------- |
| **ATProtoKit**                 | [DocC](https://atprotokit.cjrriley.com/documentation/atprotokit/)                                | [![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FMasterJ93%2FATProtoKit%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/MasterJ93/ATProtoKit)<br>[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FMasterJ93%2FATProtoKit%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/MasterJ93/ATProtoKit) | [Source Code](https://github.com/MasterJ93/ATProtoKit) |
| **ATCryptography**             | [DocC](https://swiftpackageindex.com/ATProtoKit/ATCryptography/documentation/atcryptography)     | [![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATCryptography%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/ATProtoKit/ATCryptography)<br>[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATCryptography%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/ATProtoKit/ATCryptography) | [Source Code](https://github.com/ATProtoKit/ATCryptography) |
| **ATCommonTools**              | _Not available online at this time._                                                             | _Not submitted to Swift Package Index at this time._                                                                                                      | [Source Code](https://github.com/ATProtoKit/ATCommonTools/tree/main) |
| **ATSyntaxTools**              | [DocC](https://swiftpackageindex.com/ATProtoKit/ATSyntaxTools/documentation/atsyntaxtools)       | [![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATSyntaxTools%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/ATProtoKit/ATSyntaxTools)<br>[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATSyntaxTools%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/ATProtoKit/ATSyntaxTools) | [Source Code](https://github.com/ATProtoKit/ATSyntaxTools) |
| **ATIdentityTools**            | [DocC (ATIdentityTools)](https://swiftpackageindex.com/ATProtoKit/ATIdentityTools/documentation/atidentitytools)<br>[DocC (DIDCore)](https://swiftpackageindex.com/ATProtoKit/ATIdentityTools/documentation/didcore) | [![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATIdentityTools%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/ATProtoKit/ATIdentityTools)<br>[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FATProtoKit%2FATIdentityTools%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/ATProtoKit/ATIdentityTools) | [Source Code](https://github.com/ATProtoKit/ATIdentityTools/tree/main) |

## Conversion Progress
For reference on what has been converted, here's a table of all the converted packages so far, and what's left to be converted.

### TypeScript Packages
| TypeScript Package Name       | ATProtoKit Swift package             |
| ----------------------------- | ------------------------------------ |
| api	                          | ATProtoKit                           |
| aws	                          | _TBD._                               |
| bsky (AppView)                | _TBD._                               |
| bsync                         | _TBD._                               |
| common	                      | ATCommonTools                        |
| common-web                    | ATCommonWeb (within ATCommonTools)   |
| crypto                        |	ATCryptography                       |
| dev-env                       | _TBD._                               |
| dev-infra	                    | _TBD._                               |
| did                           |	DIDCore (within ATIdentityTools)     |
| identity                      | ATIdentityTools                      |
| internal	                    | _TBD._                               |
| lex-ci                        | _TBD._                               |
| lexicon	                      |	_ATLexiconTools_                     |
| oauth	                        | _ATOAuthKit_                         |
| ozone	                        | _TBD._                               |
| pds                           | _TBD._                               |
| repo                          |	_ATRepository (and swift-at-mst)_    |
| sync                          | _TBD._                               |
| syntax                        | ATSyntaxTools                        |
| xrpc                          | ATProtoKit                           |
| xrpc-server	                  | _TBD._                               | 

<!-- ### TypeScript Services -->

<!-- ### Go Packages -->

<!-- ### Go Services -->

_(Any ATProtoKit Swift packages where the names are in italics suggests the Swift package doesn't exist at this time.)_
