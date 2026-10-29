# Supported projects

Generated 2026-10-29T02:15:07Z. Written by the line manager reconciler.

The latest patch view: every library at the latest upstream patch release, the view the work follows. Every library and version the exchange maintains, ordered by library and then by version. A library that sits on more than one line is one row, with every line it belongs to named. For reporting only.

## Lines

| line_id | ecosystem | anchor | status | CVE_in_scope | CVE_fixed | CVE_fixed_% | CVE_out_of_scope | CVE_in_progress | CVE_left | CVE_not_remediable |
|---|---|---|---|---|---|---|---|---|---|---|
| spring-boot-2.7.x | maven | `org.springframework.boot:spring-boot-dependencies@2.7.18` | - | 0 | 0 | - | 113 | 0 | 0 | 0 |
| spring-framework-5.3.x | maven | `org.springframework:spring-framework-bom@5.3.39` | not fixed | 47 | 0 | 0% | 0 | 0 | 47 | 0 |
| spring-security-5.7.x | maven | `org.springframework.security:spring-security-bom@5.7.11` | - | 0 | 0 | - | 12 | 0 | 0 | 0 |
| crypto-js-4.1.x | npm | `crypto-js@4.1.1` | fixed | 1 | 1 | 100% | 0 | 0 | 0 | 0 |
| requests-2.31.x | pypi | `requests==2.31.0` | - | 0 | 0 | - | 0 | 0 | 0 | 0 |

## Libraries

75 libraries across 5 line(s).

| name | version | lines | why_listed | status | CVE_in_scope | CVE_fixed | CVE_fixed_% | CVE_out_of_scope | CVE_in_progress | CVE_left | CVE_not_remediable | patched_as | consumed | consumption_readiness | chain | files | evidence | signatures | document | producer | verdict | fork | tag | upload | tagger |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| at.yawk.lz4:lz4-java | 1.8.1 | spring-boot-2.7.x | pulled in by a dependency (org.elasticsearch:elasticsearch-lz4@7.17.29) | open | 7 | 0 | 0% | 4 | 0 | 7 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| ch.qos.logback:logback-core | 1.2.13 | spring-boot-2.7.x | listed by the BOM at 1.2.12 | open | 6 | 0 | 0% | 0 | 0 | 6 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.core:jackson-core | 2.13.5 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 3 | 0 | 0% | 1 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.core:jackson-databind | 2.13.5 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 11 | 0 | 0% | 0 | 0 | 11 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.jackson.dataformat:jackson-dataformat-toml | 2.13.5 | spring-boot-2.7.x | listed by the BOM at 2.13.5 (com.fasterxml.jackson:jackson-bom@2.13.5) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.fasterxml.woodstox:woodstox-core | 5.0.3 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.apache.santuario:xmlsec@2.0.10) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.google.guava:guava | 20.0 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (net.shibboleth.utilities:java-support@7.5.2) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.graphql-java:graphql-java | 18.5 | spring-boot-2.7.x | listed by the BOM at 18.5 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.jayway.jsonpath:json-path | 2.7.0 | spring-boot-2.7.x | listed by the BOM at 2.7.0 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.mchange:mchange-commons-java | 0.2.20 | spring-boot-2.7.x | pulled in by a dependency (org.quartz-scheduler:quartz@2.3.2) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.nimbusds:nimbus-jose-jwt | 9.22 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (com.nimbusds:oauth2-oidc-sdk@9.35) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| com.rabbitmq:amqp-client | 5.14.3 | spring-boot-2.7.x | listed by the BOM at 5.14.3 | open | 11 | 0 | 0% | 0 | 0 | 11 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| commons-beanutils:commons-beanutils | 1.9.4 | spring-boot-2.7.x | pulled in by a dependency (org.apache.activemq:artemis-commons@2.19.1) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| commons-lang:commons-lang | 2.4 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.apache.velocity:velocity@1.7) | open | 1 | 0 | 0% | 1 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| crypto-js | 4.1.1 | crypto-js-4.1.x | pulled in by a dependency (crypto-js@4.1.1) | fixed | 1 | 1 | 100% | 0 | 0 | 0 | 0 | 4.1.2-osera-00001 | 4.1.2-osera-00001 | ready | complete | OK | OK | OK | OK | OK | OK | OK | OK | OK | OK |
| io.micrometer:micrometer-core | 1.9.17 | spring-boot-2.7.x | listed by the BOM at 1.9.17 (io.micrometer:micrometer-bom@1.9.17) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| io.projectreactor.netty:reactor-netty | 1.0.48 | spring-boot-2.7.x | listed by the BOM at 1.0.39 (io.projectreactor:reactor-bom@2020.0.38) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| io.projectreactor.netty:reactor-netty-http | 1.0.48 | spring-boot-2.7.x | listed by the BOM at 1.0.39 (io.projectreactor:reactor-bom@2020.0.38) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| io.undertow:undertow-core | 2.2.41.Final | spring-boot-2.7.x | listed by the BOM at 2.2.28.Final | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| ognl:ognl | 3.1.29 | spring-boot-2.7.x | pulled in by a dependency (org.thymeleaf:thymeleaf@3.0.15.RELEASE) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.activemq:activemq-broker | 5.16.8 | spring-boot-2.7.x | listed by the BOM at 5.16.7 | open | 9 | 0 | 0% | 0 | 0 | 9 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.activemq:activemq-client | 5.16.8 | spring-boot-2.7.x | listed by the BOM at 5.16.7 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.commons:commons-compress | 1.21 | spring-boot-2.7.x | pulled in by a dependency (org.springframework.boot:spring-boot-buildpack-platform@2.7.18) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-1.2-api | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-api | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-core | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.logging.log4j:log4j-layout-template-json | 2.17.2 | spring-boot-2.7.x | listed by the BOM at 2.17.2 (org.apache.logging.log4j:log4j-bom@2.17.2) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.santuario:xmlsec | 2.0.10 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.opensaml:opensaml-security-api@3.4.6) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.apache.velocity:velocity | 1.7 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.opensaml:opensaml-saml-impl@3.4.6) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.assertj:assertj-core | 3.22.0 | spring-boot-2.7.x | listed by the BOM at 3.22.0 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.bouncycastle:bcpkix-jdk15on | 1.70 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.jasig.cas.client:cas-client-core@3.6.4) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.bouncycastle:bcprov-jdk15on | 1.70 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (org.bouncycastle:bcpkix-jdk15on@1.70) | open | 4 | 0 | 0% | 2 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-http | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-jaspi | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-security | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.eclipse.jetty:jetty-server | 9.4.58.v20250814 | spring-boot-2.7.x | listed by the BOM at 9.4.53.v20231009 (org.eclipse.jetty:jetty-bom@9.4.53.v20231009) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.lz4:lz4-java | 1.8.1 | spring-boot-2.7.x | pulled in by a dependency (org.elasticsearch:elasticsearch-lz4@7.17.29) | open | 7 | 0 | 0% | 4 | 0 | 7 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.amqp:spring-amqp | 2.4.17 | spring-boot-2.7.x | listed by the BOM at 2.4.17 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-autoconfigure | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-devtools | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-loader | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.boot:spring-boot-starter-actuator | 2.7.18 | spring-boot-2.7.x | own project (the anchor's group) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-commons | 2.7.18 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-keyvalue | 2.7.18 | spring-boot-2.7.x | listed by the BOM at 2.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-mongodb | 3.4.18 | spring-boot-2.7.x | listed by the BOM at 3.4.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-relational | 2.4.18 | spring-boot-2.7.x | listed by the BOM at 2.4.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.data:spring-data-rest-core | 3.7.18 | spring-boot-2.7.x | listed by the BOM at 3.7.18 (org.springframework.data:spring-data-bom@2021.2.18) | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.graphql:spring-graphql | 1.0.6 | spring-boot-2.7.x | listed by the BOM at 1.0.6 | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.hateoas:spring-hateoas | 1.5.6 | spring-boot-2.7.x | listed by the BOM at 1.5.6 | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.integration:spring-integration-file | 5.5.20 | spring-boot-2.7.x | listed by the BOM at 5.5.20 (org.springframework.integration:spring-integration-bom@5.5.20) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.kafka:spring-kafka | 2.8.11 | spring-boot-2.7.x | listed by the BOM at 2.8.11 | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ldap:spring-ldap-core | 2.4.4 | spring-boot-2.7.x, spring-security-5.7.x | listed by the BOM of spring-boot-2.7.x at 2.4.1 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.retry:spring-retry | 1.3.4 | spring-boot-2.7.x | listed by the BOM at 1.3.4 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-core | 5.7.14 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-crypto | 5.7.14 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-saml2-service-provider | 5.7.14 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.security:spring-security-web | 5.7.14 | spring-boot-2.7.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework.security@5.7.11) | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-ws-core | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-ws-security | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework.ws:spring-xml | 3.1.8 | spring-boot-2.7.x | listed by the BOM at 3.1.8 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-context | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-core | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-expression | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 4 | 0 | 0% | 0 | 0 | 4 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-jms | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-web | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x, spring-security-5.7.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-webflux | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 17 | 0 | 0% | 0 | 0 | 17 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-webmvc | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 17 | 0 | 0% | 0 | 0 | 17 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.springframework:spring-websocket | 5.3.39 | spring-boot-2.7.x, spring-framework-5.3.x | own project on spring-boot-2.7.x (declared org.springframework@5.3.39) | open | 2 | 0 | 0% | 0 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.thymeleaf:thymeleaf | 3.0.15.RELEASE | spring-boot-2.7.x | listed by the BOM at 3.0.15.RELEASE | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.thymeleaf:thymeleaf-spring5 | 3.0.15.RELEASE | spring-boot-2.7.x | listed by the BOM at 3.0.15.RELEASE | open | 3 | 0 | 0% | 0 | 0 | 3 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.xmlunit:xmlunit-core | 2.9.1 | spring-boot-2.7.x | listed by the BOM at 2.9.1 | open | 1 | 0 | 0% | 0 | 0 | 1 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |
| org.yaml:snakeyaml | 1.33 | spring-boot-2.7.x | listed by the BOM at 1.30 | fixed | 1 | 1 | 100% | 0 | 0 | 0 | 0 | 1.33.1-osera-00001 | 1.33.1-osera-00001 | ready | complete | OK | OK | OK | OK | OK | OK | OK | OK | OK | OK |
| requests | 2.31.0 | requests-2.31.x | pulled in by a dependency (requests@2.31.0) | open | 3 | 1 | 33% | 0 | 0 | 2 | 0 | 2.31.0+osera.patch.1 | 2.31.0+osera.patch.1 | ready | complete | OK | OK | OK | OK | OK | OK | OK | OK | OK | OK |
| xerces:xercesImpl | 2.11.0 | spring-boot-2.7.x, spring-security-5.7.x | pulled in by a dependency (net.sourceforge.nekohtml:nekohtml@1.9.22) | open | 2 | 0 | 0% | 2 | 0 | 2 | 0 |  |  | not claimed |  |  |  |  |  |  |  |  |  |  |  |

## Libraries promoted, not in the backlog

1 library, 1 patched version(s).

| name | base_version | reason | lines | same group on | patched_as | consumed | consumption_readiness | chain | files | evidence | signatures | document | producer | verdict | fork | tag | upload | tagger |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| oseralab-gate-probe | 0.0.1 | not listed by any line |  | crypto-js-4.1.x, requests-2.31.x | 0.0.1+osera.patch.1 | 0.0.1+osera.patch.1 | not ready, evidence chain incomplete: evidence, producer, verdict, signatures, VEX document, fork | broken | OK | NOK (no evidence file next to oseralab-gate-probe-0.0.1+osera.patch.1) | NOK (no signature next to the source archive (oseralab_gate_probe-0.0.1+osera.patch.1.tar.gz.asc)) | NOK (no vulnerability document next to the pom (oseralab_gate_probe-0.0.1+osera.patch.1-cyclonedx.json)) | NOK (the evidence names no producer) | NOK (no verdict for 0.0.1+osera.patch.1 in osera-releases-raw-01) | NOK (the fork patch-oseralab-gate-probe is missing) | not checked (the fork is missing) | not checked (no verdict to read the upload account from) | not checked (no verdict to read the tag pusher from) |
