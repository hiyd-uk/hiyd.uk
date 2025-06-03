# Security Policy

**Last updated: June 3, 2025**

## Our Security Commitment

Hyd is designed with security and privacy as core principles. This document outlines our security practices and how to report security concerns.

## Security Architecture

### Local-First Design

- **No Server Communication**: Hyd operates entirely on your device
- **No Data Transmission**: Your content never leaves your device
- **Offline Operation**: Full functionality without internet connection
- **No User Accounts**: No authentication or account management required

### Data Security

- **Local Storage Only**: All data stored in device-specific secure storage
- **No Cloud Sync**: Eliminates remote attack vectors
- **Minimal Permissions**: Apps request only essential device permissions
- **Sandboxed Execution**: Runs within platform security sandboxes

## Platform Security

### iOS App Security

- **App Store Review**: Vetted through Apple's security review process
- **iOS Sandbox**: Operates within iOS security sandbox
- **Keychain Integration**: Uses iOS Keychain for secure preference storage
- **Code Signing**: Digitally signed and verified

### Chrome Extension Security

- **Manifest V3**: Built using the latest Chrome extension security standards
- **Minimal Permissions**: Requests only necessary permissions
- **Content Security Policy**: Implements strict CSP headers
- **Extension Store Review**: Reviewed by Chrome Web Store security team

## Supported Versions

We provide security updates for:

| Version | Supported          |
| ------- | ------------------ |
| Latest  | ✅ Yes             |
| Previous| ✅ Yes (6 months)  |
| Older   | ❌ No              |

## Reporting Security Vulnerabilities

We take security seriously. If you discover a security vulnerability, please:

### How to Report

1. **Email**: Send details to <security@hyd.app>
2. **Subject Line**: Include "SECURITY" in the subject
3. **Information**: Provide detailed reproduction steps
4. **Responsible Disclosure**: Allow us time to address before public disclosure

### What to Include

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment
- Your contact information (optional)

### Response Timeline

- **Acknowledgment**: Within 48 hours
- **Initial Assessment**: Within 1 week
- **Resolution**: Target 30 days for critical issues
- **Updates**: Regular communication throughout process

## Security Best Practices for Users

### Device Security

- Keep your device OS updated
- Use device lock screens and biometric authentication
- Install apps only from official stores
- Regular device backups

### Content Security

- Review generated content before publishing
- Keep local content backups
- Use secure Jekyll hosting practices
- Follow Jekyll security guidelines

## Known Security Considerations

### Local Storage Limitations

- Data security depends on device security
- Physical device access could expose local data
- Device theft or loss affects data security
- No remote wipe capabilities

### Browser Extension Considerations

- Browser security affects extension security
- Shared computer usage may expose data
- Browser sync may replicate local data
- Extension updates require user action

## Security Updates

We regularly:

- Monitor for security vulnerabilities
- Update dependencies and frameworks
- Review and improve security practices
- Coordinate with platform security teams

## Third-Party Security

Since Hyd operates locally:

- No third-party data processors
- No external API dependencies
- No cloud service integrations
- Minimal attack surface

## Compliance

### Privacy Compliance

- GDPR compliant (no data collection)
- CCPA compliant (no data sale)
- COPPA compliant (no child data collection)

### Platform Compliance

- Apple App Store guidelines
- Chrome Web Store policies
- Platform security requirements

## Contact

For security concerns or questions:

- **Security Email**: <security@hyd.app>
- **General Support**: <support@hyd.app>
- **Website**: hyd.thechels.uk

## Security Philosophy

Hyd's security model is built on the principle that the most secure data is data that never leaves your device. By operating entirely locally, we eliminate entire classes of security vulnerabilities associated with data transmission, cloud storage, and remote processing.

Your content remains under your complete control, protected by your device's security measures and your own security practices.
