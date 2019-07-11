---
layout: layout.pug
navigationTitle: Couchbase
title: Couchbase
menuWeight: 15
excerpt: 
featureMaturity:
community: true
model: /dcos/services/couchbase/data.yml
render: mustache
category: Databases
---

DC/OS {{ model.techName }} service is an autonomous service that makes it easy to deploy and operate {{ model.serverName }} and the {{ model.syncGatewayName }} on Mesosphere {{ model.productName }}.

#include /dcos/services/include/community-warning.tmpl