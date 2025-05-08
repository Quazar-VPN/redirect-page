# Redirect Page

![License](https://img.shields.io/badge/license-MIT-blue.svg)

A user-friendly redirect page designed specifically for Quazar.

![image](https://github.com/user-attachments/assets/df9f073d-0daa-4cea-965e-64677b739130)


## Features

- **Responsive & Mobile-Ready** - Optimized for all screen sizes and devices
- **Dark/Light Mode Support** - Automatically detects and adapts to user preferences
- **Internationalization** - Supports English and Russian languages based on browser settings
- **Fast Loading** - Minimal dependencies and optimized assets for quick page loads
- **Clear Call-to-Action** - Intuitive user flow with prominent redirect button
- **Trust Indicators** - Security badges to reinforce VPN brand credibility
- **Animated Loading Indicator** - Visual feedback that enhances user experience

## Quick Start

### Basic Usage

1. Upload the `index.html` file to your web server
2. Use the page with a redirect parameter:
   ```
   https://yourdomain.com/redirect/?redirect_to=https://destination-url.com
   ```

## Technical Details

### File Structure

```
securevpn-redirect/
├── index.html      # Single-file solution with embedded CSS and JS
├── README.md       # This documentation
└── LICENSE         # MIT License
```

### Dependencies

- No external JavaScript libraries required
- Uses Google Fonts (Poppins) for typography
- All styles and functionality contained within a single HTML file

### Browser Support

Tested and working on:
- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+
- Mobile Safari/Chrome on iOS 13+
- Chrome on Android 8+

## Security Considerations

- The page uses HTTPS to ensure secure transit of data
- No cookies or local storage are used by default
- Redirect URLs are properly encoded to prevent injection attacks
- Simple, transparent code makes security auditing straightforward

## Use Cases

- VPN authentication flow redirects
- Secure transition between VPN service pages
- Payment gateway redirects for VPN subscriptions
- Affiliate program redirects with enhanced trust signals
- App store redirects from marketing pages

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
