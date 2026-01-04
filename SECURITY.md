# Security Policy

## 🔒 Reporting a Vulnerability

I take the security of this portfolio website seriously. If you discover a security vulnerability, please report it responsibly.

### How to Report

Please **DO NOT** create a public GitHub issue for security vulnerabilities.

Instead, report security issues via:

1. **Email:** [sahooshuvranshusekhar@gmail.com](mailto:sahooshuvranshusekhar@gmail.com)
   - Use subject line: `[SECURITY] Vulnerability Report`
   - Include detailed description of the vulnerability
   - Provide steps to reproduce (if applicable)

2. **Discord:** [Its_Shuvranshu](https://discord.com/users/879695880528216075)
   - Send a direct message with details
   - Mark the message as urgent

### What to Include

When reporting a vulnerability, please include:

- **Type of vulnerability** (XSS, CSRF, injection, etc.)
- **Location** (URL, file path, or component)
- **Steps to reproduce** the issue
- **Potential impact** of the vulnerability
- **Suggested fix** (if you have one)

### Response Timeline

- **Initial Response:** Within 48 hours
- **Status Update:** Within 5 business days
- **Fix Implementation:** Varies based on severity
  - Critical: 1-3 days
  - High: 3-7 days
  - Medium: 7-14 days
  - Low: 14-30 days

## 🛡️ Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| Latest  | ✅ Yes            |
| Older   | ❌ No             |

This is a static portfolio website, so only the latest deployed version receives security updates.

## 🔐 Security Measures

This portfolio implements several security best practices:

### Frontend Security

- ✅ **Content Security Policy (CSP)** - Planned for implementation
- ✅ **HTTPS Only** - Enforced via GitHub Pages
- ✅ **No Inline Scripts** - External JavaScript files
- ✅ **Input Validation** - Forms validate user input
- ✅ **XSS Prevention** - Sanitized user inputs
- ✅ **CORS Configuration** - Proper cross-origin settings

### External Resources

- ✅ **CDN Resources** - Using trusted CDNs only
- ✅ **Subresource Integrity (SRI)** - Planned for CDN resources
- ✅ **No Sensitive Data** - No API keys or credentials in code

### Best Practices

- ✅ **Regular Updates** - Dependencies updated regularly
- ✅ **Code Review** - All changes reviewed before deployment
- ✅ **Minimal Permissions** - Following principle of least privilege
- ✅ **Secure Links** - Using `rel="noopener noreferrer"` for external links

## 📋 Known Limitations

As a static website hosted on GitHub Pages:

- No server-side authentication
- No database security concerns
- Limited backend security requirements
- No user data storage

## 🔄 Security Update Process

1. Vulnerability reported
2. Severity assessment
3. Fix development and testing
4. Security patch deployment
5. Reporter notification
6. Public disclosure (if applicable)

## 📢 Security Advisories

Security updates will be announced via:

- GitHub repository releases
- Commit messages tagged with `[SECURITY]`
- Portfolio website updates section

## 🤝 Responsible Disclosure

I believe in responsible disclosure and will:

- Acknowledge your report within 48 hours
- Keep you informed of progress
- Credit you (if desired) when the issue is resolved
- Not take legal action against good-faith security researchers

## 📞 Contact

For non-security related issues:
- **GitHub Issues:** [Create an issue](https://github.com/SahooShuvranshu/SahooShuvranshu.github.io/issues)
- **General Inquiries:** [sahooshuvranshusekhar@gmail.com](mailto:sahooshuvranshusekhar@gmail.com)

---

**Thank you for helping keep this portfolio website secure!** 🔒

*Last Updated: January 2026*
