

# requests.js

**requests.js** is a lightweight JavaScript library for making AJAX requests with ease. It provides simple methods for handling HTTP GET, POST, PUT, and DELETE requests using the `XMLHttpRequest` API.

## Features

- Simple and intuitive API.
- Supports GET, POST, PUT, and DELETE requests.
- Handles JSON data easily.
- Lightweight with no external dependencies.

## Installation

You can include `requests.js` in your project by downloading it or linking it directly.

### Download
Clone this repository and include `requests.js` in your project:
```bash
git clone https://github.com/lodwickmasete/requests.js.git

Include in HTML

<script src="requests.js"></script>

Usage

Here’s how to use requests.js:

GET Request
`
requests.get('https://api.example.com/data', 
  function (response) {
    console.log('Data:', response);
  },
  function (error) {
    console.error('Error:', error);
  }
);

POST Request

requests.post('https://api.example.com/data', 
  { key: 'value' }, 
  function (response) {
    console.log('Data saved:', response);
  },
  function (error) {
    console.error('Error:', error);
  }
);

PUT Request

requests.put('https://api.example.com/data/1', 
  { key: 'updatedValue' }, 
  function (response) {
    console.log('Data updated:', response);
  },
  function (error) {
    console.error('Error:', error);
  }
);

DELETE Request

requests.delete('https://api.example.com/data/1', 
  function (response) {
    console.log('Data deleted:', response);
  },
  function (error) {
    console.error('Error:', error);
  }
);

Contributing

Contributions are welcome! If you have any ideas or suggestions, feel free to open an issue or submit a pull request.

License

This project is licensed under the MIT License.
