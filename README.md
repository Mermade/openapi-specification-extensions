# openapi-specification-extensions

A resource for common and standardised [OpenAPI specification](https://spec.openapis.org/oas/latest.html) (vendor) extensions.

As well as a list of vendor-documented specification-extensions, this repository contains the results of two analyses of extensions, formats and $ref siblings used in real-world OpenAPI definitions, as at late March 2017 and April 2021. 

See also this [blog post](https://blog.postman.com/what-we-learned-from-200000-openapi-files/).

## Vendor-documented extensions

* [Adyen](https://github.com/Adyen/adyen-openapi#vendor-extensions)
* [AIRR](http://docs.airr-community.org/en/latest/datarep/overview.html#airr-extension-properties)
* [Alibaba Cloud API Gateway](https://www.alibabacloud.com/help/doc-detail/88956.htm)
* [Amazon AWS](http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-swagger-extensions.html)
* [api-ref-resolver](https://github.com/apiture/api-ref-resolver#readme)
* [Apiary](https://help.apiary.io/api_101/swagger-extensions/)
* [Apigee-127](https://github.com/apigee-127/a127-documentation/wiki/Swagger-specification-file#user-content-apigee-127-swagger-specification-reference)
* [APIMatic](https://docs.apimatic.io/advanced/swagger-server-configuration-extensions/)
* [APIs.guru](https://github.com/APIs-guru/openapi-directory/wiki/specification-extensions)
* [Bump.sh](https://help.bump.sh/markdown-support#adding-topics-to-your-documentation)
* [Bungie.net](https://github.com/Bungie-net/api#extension-properties-on-openapi-specs-or-how-to-generate-much-cooler-clients-for-the-bnet-api-if-you-want-to-take-the-time-to-do-so)
* [DocuSign](https://github.com/docusign/eSign-OpenAPI-Specification/blob/master/DocuSign-Extensions.md)
* [EVRYTHNG](https://developers.evrythng.com/docs/openapi-description#section-extensions)
* [Exegesis](https://github.com/exegesis-js/exegesis/blob/master/docs/OAS3%20Specification%20Extensions.md)
* [express-openapi](https://github.com/kogosoftwarellc/open-api/tree/master/packages/express-openapi#vendor-extensions)
* [GitHub](https://github.com/github/rest-api-description/blob/main/extensions.md)
* [go-swagger](https://goswagger.io/use/models/schemas.html#custom-extensions)
* [Google Cloud Endpoints](https://cloud.google.com/endpoints/docs/openapi/openapi-extensions)
* [IBM API Connect](https://www.ibm.com/support/knowledgecenter/SSMNED_5.0.0/com.ibm.apic.toolkit.doc/rapim_cli_swagger_extensions.html)
* [Kusk](https://kubeshop.github.io/kusk/openapi-extension/)
* [Kusk Gateway](https://kubeshop.github.io/kusk-gateway/extension/)
* [Microsoft Azure](https://github.com/Azure/autorest/tree/master/docs/extensions)
* [Microsoft Connectors](https://docs.microsoft.com/en-us/connectors/custom-connectors/openapi-extensions)
* [Microsoft Flow](https://flow.microsoft.com/en-us/documentation/customapi-how-to-swagger/)
* [Microsoft Typespec (fka Cadl)](https://microsoft.github.io/typespec/next/standard-library/openapi/reference/js-api#getopenapitypename)
* [Nintex Workflow Cloud](https://help.nintex.com/en-US/xtensions/04_Reference/REF_OpenAPISwipeFile.htm#OpenAPI_Specification_Extensions)
* [NSwagStudio/NJsonSchema](https://github.com/rsuter/NJsonSchema/wiki/Enums) - documentation pending (x-typeName, x-enumNames)
* [ReadMe.io](https://docs.readme.com/docs/openapi-extensions)
* [Rebilly Redoc](https://github.com/Rebilly/ReDoc/blob/master/docs/redoc-vendor-extensions.md)
* [Red Hat Fuse Online](https://access.redhat.com/documentation/en-us/red_hat_fuse/7.5/html/integrating_applications_with_fuse_online/customizing_ug#providing-client-credentials_dev-client-connector)
* [RepreZen Swagger-Normalizer](http://docs.reprezen.com/swagger_normalizer/)
* [Restish](https://rest.sh/#/openapi?id=openapi-extensions)
* [SAP OpenAPI Specification Extensions for the SAP Ecosystem](https://github.com/sap/OpenAPI-Specification)
* [Spring Cloud Contract OpenAPI 3.0 Converter](https://github.com/springframeworkguru/spring-cloud-contract-oa3#defining-contracts-in-openapi)
* [SQL-Translator-Parser-OpenAPI](https://metacpan.org/pod/SQL::Translator::Parser::OpenAPI#OPENAPI-SPEC-EXTENSIONS)
* [Stripe](https://github.com/stripe/openapi#vendor-extensions)
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen/wiki/Vendor-Extensions)
* [SwaggerHub](https://app.swaggerhub.com/help/apis/vendor-extensions)
* [swaggerplusplus](https://github.com/mermade/swaggerplusplus)
* [Twilio](https://github.com/twilio/guardrail/blob/master/modules/microsite/docs/scala/akka-http/guardrail-extensions.md)
* [TypeForm OpenAPI-micro-merge](https://github.com/Typeform/openapi-micro-merge#extensions)
* [Unisys COBOL](https://public.support.unisys.com/ePortalIC-10.0/index.jsp?topic=%2F82073594_clearpath_eportal_developerhelp%2Fhtml%2Fsection-000064331.htm)
* [Vert.x](https://vertx.io/docs/vertx-web-api-service/java/#_using_the_extension_code_x_vertx_event_bus_code)
* WaveMaker Studio (x-WM- extensions) - documentation pending
* [WSO2 API Microgateway](https://docs.wso2.com/display/MG300/Supported+OpenAPI+Extensions)
* [Yandex API Gateway](https://cloud.yandex.com/en/docs/api-gateway/concepts/extensions/)
* [Zuplo](https://zuplo.com/docs/articles/open-api#zuplo-extensions)

## Analysis of specification-extensions

### 2021

Facet|Analysis
|---|---|
Extensions|[193953 definitions](extensions/2021/extensions.tsv)
Formats|[193953 definitions](formats/2021/formats.tsv)
Ref Sibling|[193953 definitions](refs/2021/refs.tsv)

### 2017

### Analysis of extensions

Source|Analysis
|---|---|
[APIs.guru](https://github.com/apis-guru/openapi-directory)|[391 definitions](extensions/2017/apis-guru.tsv)
[GitHub](https://github.com/)|[25136 definitions](extensions/2017/github.tsv)
[Mermade](https://github.com/mermade/openapi-definitions)|[454 definitions](extensions/2017/mermade.tsv)
[SOM Research HAPI](https://github.com/som-research/hapi)|[513 definitions](extensions/2017/hapi.tsv)
[SwaggerHub](http://swaggerhub.com)|[22872 definitions](extensions/2017/swaggerhub.tsv)
Combined|[49366 definitions](extensions/2017/combined.tsv)

#### Analysis of formats

Source|Analysis
|---|---|
[APIs.guru](https://github.com/apis-guru/openapi-directory)|[391 definitions](formats/2017/apis-guru.tsv)
[GitHub](https://github.com/)|[25136 definitions](formats/2017/github.tsv)
[Mermade](https://github.com/mermade/openapi-definitions)|[454 definitions](formats/2017/mermade.tsv)
[SOM Research HAPI](https://github.com/som-research/hapi)|[513 definitions](formats/2017/hapi.tsv)
[SwaggerHub](http://swaggerhub.com)|[22872 definitions](formats/2017/swaggerhub.tsv)
Combined|[49366 definitions](formats/2017/combined.tsv)

#### Analysis of $refs with additional properties

Source|Analysis
|---|---|
Combined|[49366 definitions](refs/2017/combined.csv)

