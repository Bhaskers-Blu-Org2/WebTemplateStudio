﻿## Next Steps

//{[{

### Sample Data

Replace the sample data stored in /server/sample_data.py.
Replace the default images. Sample images are consumed from https://wtsrepository.blob.core.windows.net/sampledata/.
//}]}

## File Structure

The back-end is based on [Flask](https://github.com/pallets/flask).
The front-end is served on http://localhost:3000/ and the back-end on http://localhost:3001/.

```
.
├── server/ - Flask server that provides API routes and serves front-end
│ ├── constants.py - Defines the constants for the endpoints and port
//{[{
│ ├── sample_data.py - Contains all sample text data for generate pages
//}]}
│ └── server.py - Configures Port and HTTP Server and provides API routes
└── README.md
```
