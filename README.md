<div align="center">
  <img src="https://github.com/user-attachments/assets/b8d658ab-496e-4c3e-9b38-c3d5f234b346" alt="NewsDataHub API" width="120"/>
</div>

# NewsDataHub API

Access news data from trusted sources worldwide through a simple REST API. Start exploring with our free news API tier - no credit card required.  Visit our [main website][website] to learn more about our service.

## Academic Use

If you're affiliated with an educational institution and need access to paid account for research purposes, please email us directly: 
- info [at] newsdatahub [dot] com to discuss academic pricing options.

## Quick Start

### Python
```python
import requests

headers = {
    'X-Api-Key': 'your_api_key_here'
}

response = requests.get('https://api.newsdatahub.com/v1/news', headers=headers)
news_data = response.json()
```

### JavaScript
```javascript
const axios = require('axios');

const headers = {
    'X-Api-Key': 'your_api_key_here'
};

async function getNews() {
    try {
        const response = await axios.get('https://api.newsdatahub.com/v1/news', { headers });
        console.log(response.data);
    } catch (error) {
        console.error('Error:', error.message);
    }
}

getNews();
```

## Features

- Multi-regional coverage across 9 countries (US, UK, Canada, Spain, France, Germany, India, Pakistan, Australia)
- Rich article metadata
- Simple REST API with standardized JSON responses
- Free tier with 100 daily requests

## Getting Started

1. [Sign up][signup] for your free API key
2. Add the key to your requests using the `X-Api-Key` header
3. Start fetching news data!

## Documentation

Visit our [API Reference][docs] for complete documentation. Our documentation includes detailed information about:
- Authentication
- Pagination
- Result filtering options
- Code samples in Python, Node.js, Go, and Ruby


## Example Response

View a sample API response from our paid plan in [data.json](data.json). This example demonstrates the full range of available fields including sentiment analysis and keyword extraction capabilities.

[website]: https://newsdatahub.com
[signup]: https://newsdatahub.com
[docs]: https://newsdatahub.com/docs
[contact]: mailto:support@newsdatahub.com
