# Changelog Component

## Overview
The **Changelog Component** is a simple HTML and CSS-based UI component that displays software update logs in a structured and user-friendly format. It helps users track new features, improvements, and bug fixes.

## Features
- 📜 **Versioned Changelog** - Display updates based on software versions.
- 🎨 **Customizable UI** - Style the component to fit your design.
- 🚀 **Lightweight & Fast** - Pure HTML and CSS implementation.
- 📅 **Date-Based Sorting** - Lists updates in chronological order.
- 🔥 **Icons for Better Visualization** - Easily distinguish between new features, bug fixes, and improvements.

## Usage

### Basic Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Changelog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .changelog {
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        .version {
            font-size: 20px;
            font-weight: bold;
            color: #007bff;
        }
        .date {
            font-size: 14px;
            color: gray;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            padding: 5px 0;
        }
    </style>
</head>
<body>

    <div class="changelog">
        <h2>Changelog</h2>
        
        <div>
            <p class="version">Version 1.2.0</p>
            <p class="date">2025-02-03</p>
            <ul>
                <li>🆕 Added user profile page</li>
                <li>✅ Optimized page load speed</li>
                <li>🔧 Updated UI design</li>
            </ul>
        </div>

        <div>
            <p class="version">Version 1.1.0</p>
            <p class="date">2025-01-20</p>
            <ul>
                <li>🆕 Added logout button</li>
                <li>🐞 Fixed button delay issue</li>
            </ul>
        </div>
    </div>

</body>
</html>
```

## Styling
Use CSS to customize the look and feel of the changelog component:
```css
.changelog {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
.changelog .version {
  font-weight: bold;
  color: #007bff;
}
.changelog .date {
  font-size: 14px;
  color: gray;
}
```

## License
This project is licensed under the MIT License.

