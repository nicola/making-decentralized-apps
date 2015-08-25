# Making Decentralized (Web) Apps
Practical tutorial on how to get the awesomeness out of the decentralized web

## Solid: The Social Linked Data stack

### Writing a sample app

```javascript
var rdf = require('rdf-ext')()
var LdpStore = require('rdf-store-ldp')

var store = new LdpStore(rdf)
store.graph('https://www.w3.org/People/Berners-Lee/card', function(graph, err) {
  
})
```

### Understanding WebID

### Decentralized storage

### Experimental distributed storage
