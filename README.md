# openapi-specification-extensions
A resource for common and standardised OpenAPI specification (vendor) extensions.

As well as a list of vendor-documented specification-extensions, this repository contains the results of an analysis of extensions and formats used in real-world OpenAPI definitions, as at late March 2017. It is also planned to replicate [this analysis](http://www.apiful.io/intro/2016/05/09/analyzing-api-specifications.html) but on a much larger scale.

## Vendor-documented extensions

* [Amazon AWS](http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-swagger-extensions.html)
* [Apiary](https://help.apiary.io/api_101/swagger-extensions/)
* [Apigee-127](https://github.com/apigee-127/a127-documentation/wiki/Swagger-specification-file#user-content-apigee-127-swagger-specification-reference)
* [APIMatic](https://docs.apimatic.io/advanced/swagger-server-configuration-extensions/)
* [APIs.guru](https://github.com/APIs-guru/openapi-directory/wiki/specification-extensions)
* [Microsoft Azure](https://github.com/Azure/autorest/tree/master/docs/extensions)
* [Rebilly Redoc](https://github.com/Rebilly/ReDoc/blob/master/docs/redoc-vendor-extensions.md)
* [swaggerplusplus](https://github.com/mermade/swaggerplusplus)

## Analysis of specification-extensions

Source|Analysis
|---|---|
[APIs.guru](https://github.com/apis-guru/openapi-directory)|[391 definitions](extensions/apis-guru.tsv)
[GitHub](https://github.com/)|[25136 definitions](extensions/github.tsv)
[Mermade](https://github.com/mermade/openapi-definitions)|[454 definitions](extensions/mermade.tsv)
[SOM Research HAPI](https://github.com/som-research/hapi)|[513 definitions](extensions/hapi.tsv)
[SwaggerHub](http://swaggerhub.com)|[22872 definitions](extensions/swaggerhub.tsv)
Combined|[49366 definitions](extensions/combined.tsv)

## Analysis of formats

Source|Analysis
|---|---|
[APIs.guru](https://github.com/apis-guru/openapi-directory)|[391 definitions](formats/apis-guru.tsv)
[GitHub](https://github.com/)|[25136 definitions](formats/github.tsv)
[Mermade](https://github.com/mermade/openapi-definitions)|[454 definitions](formats/mermade.tsv)
[SOM Research HAPI](https://github.com/som-research/hapi)|[513 definitions](formats/hapi.tsv)
[SwaggerHub](http://swaggerhub.com)|[22872 definitions](formats/swaggerhub.tsv)
Combined|[49366 definitions](formats/combined.tsv)

## Analysis of $refs with additional properties

Source|Analysis
|---|---|
Combined|[49366 definitions](refs/combined.csv)
