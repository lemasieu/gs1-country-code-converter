# GS1 Country Code Converter

A simple, interactive web tool that identifies the country or GS1 Member Organization associated with a barcode prefix. Enter the first 3 to 7 digits of any GS1 barcode (EAN/UPC) and instantly find out which country or region it belongs to.

## 🚀 Live Demo

Check out the live demo: [https://www.xn--msiu-goa8b.vn/github/gs1-country-code-converter](https://www.xn--msiu-goa8b.vn/github/gs1-country-code-converter)

## ✨ Features

- **Barcode Prefix Lookup** – Enter the first 3 to 7 digits of any GS1 barcode
- **Instant Results** – See the corresponding country or GS1 Member Organization in real-time
- **Comprehensive Coverage** – Supports GS1 prefixes assigned to countries and regions worldwide
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- JSON (GS1 prefix data)

## 📁 Project Structure

```
gs1-country-code-converter/
├── index.html              # Main HTML file
├── style.css               # Stylesheet
├── script.js               # JavaScript logic for prefix lookup
├── data.json               # GS1 prefix data
└── README.md               # Project documentation
```


## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/gs1-country-code-converter.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd gs1-country-code-converter
   ``` 
3. **Run the application with a local server**

⚠️ Important: This project loads data from a JSON file, so you need to use a local development server instead of opening `index.html` directly in your browser to avoid CORS issues.

- **Using VS Code** – Install the "Live Server" extension, right-click on `index.html`, and select "Open with Live Server"
- **Using Python** – Run `python -m http.server` (Python 3) or `python -m SimpleHTTPServer` (Python 2) and open `http://localhost:8000`
- **Using Node.js** – Install `http-server` globally (`npm install -g http-server`) and run `http-server` in the project folder

## 📝 How It Works

1. **Enter barcode digits** – Type the first 3 to 7 digits of any GS1 barcode (EAN-13, UPC, etc.) into the input field
2. **View the result** – The corresponding country, region, or GS1 Member Organization appears instantly
3. **Clear the field** – Use the reset button to clear the input and start a new search

### Important Notes:

- Entering only 2 digits (except '99') will not return an accurate result
- The GS1 prefix indicates the GS1 Member Organization that issued the barcode, not necessarily the country of manufacture

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open-source and available under the MIT License.
