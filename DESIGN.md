# Programmeerproject - Design Document
### Jelle Mul
### 11402148

### Data
De Data wordt opgehaald van de API van Peerby Go, deze heeft het onderstaande format.
[
	{
		id: String,
		productArchetype: {
      id: String,
      name: String,
		},
		contactInfo: {
			geolocation: {
				lat: Number,
				lng: Number,
			},
			...
    },
    suppliers: [
	     {
		      geolocation: {
			         lat: String,
			         lng: String,
		      },
       },
       ...
    ],
    ...
	},
	...
]
