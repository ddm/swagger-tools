[![build](https://travis-ci.org/ddm/swagger-tools.svg)](https://travis-ci.org/ddm/swagger-tools)
[![dependencies](https://david-dm.org/ddm/swagger-tools.svg)](https://david-dm.org/ddm/swagger-tools)

This is just a fork of [https://github.com/apigee-127/swagger-tools](https://github.com/apigee-127/swagger-tools) to add
support for the 'brackets' collectionFormat which is not officially part of the 
[swagger-spec](https://github.com/swagger-api/swagger-spec) but is supported by [swagger-js](https://github.com/swagger-api/swagger-js) and [swagger-ui](https://github.com/swagger-api/swagger-ui).

This is hopefully a temporary fork and will be deprecated as soon as possible. Use the original [swagger-tools npm package](https://www.npmjs.com/package/swagger-tools) unless you specifically use the 'brackets' collectionFormat in your swagger definition.

See [Issue 191 on swagger-js](https://github.com/swagger-api/swagger-js/issues/191#issuecomment-92985498) and [PR 192 on swagger-tools](https://github.com/apigee-127/swagger-tools/pull/192#issuecomment-93261480) for more context on the issue...