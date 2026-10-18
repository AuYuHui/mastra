---
'@mastra/observability': patch
---

Fixed storage exporters dropping updates for rebuilt spans that already exist in storage after an earlier flush or exporter restart.
