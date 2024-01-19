# gitops demo data

```bash
# download all data of an organization as YAML files in the structure of /$resource/$id.yaml
$ download
$ tree .
# output abbreviated
├── datacontracts
│   └── urn:datacontract:checkout:s3_customers_history_npii_v1.yaml
├── dataproducts
│   └── urn:dataproduct:checkout:customers.yaml
├── datausageagreements
│   └── checkout.snowflake_orders_v2__controlling_looker_target_performing_report.yaml
├── definitions
│   └── checkout
│      └── customer_email.yaml
├── sourcesystems
│   └── article-service.yaml
└── teams
    └── search.yaml

# upload all files to an organization, doing the reverse of download
$ upload
```
