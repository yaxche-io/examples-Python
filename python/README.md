# examples-Python/python
The **python** subdirectory of this repository contains examples to help you get started working with the data and tools hosted by the ISB-CGC on the Google Cloud Platform.

### Programmatic API Examples
The ISB-CGC programmatic API is implemented using Google Cloud Endpoints.  These services run on App Engine and can be accessed in several different ways.  You can use the [APIs Explorer](https://apis-explorer.appspot.com/apis-explorer/?base=https://api-dot-isb-cgc.appspot.com/_ah/api#p/) to try them out directly in your web browser.  
  *  **api_test_url.py** shows you how to construct https requests programmatically from python
  *  **api_test_service.py** shows you how to build a service object and use them that way  (note that we have found that accessing these endpoints using a service object is roughly twice as fast as the https requests approach, so we suggest that you start there)
  *  **query_ccle_reads.py** script shows you how to use both the ISB-CGC API and the Genomics "reads" API to query the open-access CCLE DNAseq and RNAseq reads that we have loaded into Google Genomics
  