# goodbits

A list of good things.

## Add to the list

Make a commit adding a line of JSON to [list.ndjson](./list.ndjson). The file format is [newline delimited json](http://ndjson.org/).

Make your entry a JSON object with a `"cid"` property with the [CID](https://docs.ipfs.tech/concepts/content-addressing/) of the resource and a `"tags"` property  to express what kind of goodness should be associated with the CID.

### Example

```json
{ "cid": "bafybeicaniz6j6bn2dgm3iln5cegevguhqftu7aefwjsz6mrgrhcdhkus4", "tags": ["https://nftstorage.link/tags/bypass-default-csp"] }
```

Note that `https://nftstorage.link/tags/bypass-default-csp` tag is currently used to bypass default CSP value.
