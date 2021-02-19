``` yaml
# add any configuration here for all CLI languages
# refer to the faq.md for more details
directive:
    - where:
        group: diskpool disk-pool
      set:
        group: disk-pool
    - where:
        group: diskpool iscsi-target
      set:
        group: disk-pool iscsi-target
```