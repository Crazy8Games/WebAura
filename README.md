# WebAura Details

This is a simple demo website project showcasing the power of WebAura, WebSSAura, and WebScriptAura.

## Installation
**command prompt**: npm install -g webaura-package

## Overview

This demo website consists of three main components:

1. **WebAura (HTML based)**: WebAura is a markup language for structuring webpages. It allows defining sections such as header, content, and footer in a concise and expressive syntax.

2. **WebSSAura (CSS based)**: WebSSAura is a stylesheet language for styling webpages. It provides a powerful way to define styles for various elements, including colors, fonts, and layout, using a clear and intuitive syntax.

3. **WebScriptAura (JS based)**: WebScriptAura is a scripting language for adding interactivity to webpages. It enables developers to write JavaScript code in a structured and organized manner, making it easier to maintain and extend the functionality of web applications.

## Syntax

### WebAura (HTML based)
```html
@page
{
    title: "Demo Website";
}

@section header
{
    <header>
        <h1>Welcome to WebAura Demo</h1>
    </header>
}

@section content
{
    <div class="main-content">
        <p>This is a simple demo website showcasing the power of WebAura, WebSSAura, and WebScriptAura.</p>
        <button onclick="changeColor()">Change Color</button>
    </div>
}

@section footer
{
    <footer>
        <p>&copy; 2024 WebAura Inc. All rights reserved.</p>
    </footer>
}
