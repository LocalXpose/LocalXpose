# 👾 LocalXpose

<div align="center">

[![LocalXpose Website](https://img.shields.io/badge/Website-6023c0?style=for-the-badge&logo=rocket&logoColor=white)](https://localxpose.io?utm_source=github&utm_medium=profile&utm_content=header_badge)
[![Documentation](https://img.shields.io/badge/Docs-000000?style=for-the-badge&logo=readthedocs&logoColor=white)](https://localxpose.io/docs?utm_source=github&utm_medium=profile&utm_content=docs_badge)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=readthedocs&logoColor=white)](https://localxpose.io/blog?utm_source=github&utm_medium=profile&utm_content=blog_badge)
[![Official GitHub Action](https://img.shields.io/badge/Action_\(Official\)-2088FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marketplace/actions/localxpose-tunnel)

**Expose your localhost to the world 🌍**  
*Secure tunnels for development, testing, and sharing*

</div>

---

## 🎯 What We Do

LocalXpose provides secure tunneling that just works. No VPN headaches, no fighting firewalls, no DNS drama.

**For Developers:** Share your local dev server instantly. Test webhooks, demo to clients, collaborate with teammates - all through secure, reliable tunnels.

**For Production:** Access servers and IoT devices behind any firewall. Whether you're managing infrastructure or deploying edge applications, connect to anything, anywhere - without requiring client installs or complex networking.

## 🔧 Built for Real-World Challenges

- **Development & Testing**: Instant HTTPS for localhost, webhook debugging, API integrations
- **Remote Access**: Manage servers without VPNs, access industrial systems behind firewalls
- **IoT & Edge**: Connect devices anywhere - no client software, no customer pain
- **Infrastructure**: Built-in SSL termination, load balancing, and DNS handling

## 🛠️ Get Started in Seconds

<details>
<summary><b>📦 Installation Options</b></summary>

### Package Managers
```bash
# Homebrew (macOS)
brew install --cask localxpose

# Snap (Linux)
sudo snap install localxpose

# NPM
npm install -g loclx

# Chocolatey (Windows)
choco install localxpose
```

### Docker
```bash
docker pull localxpose/localxpose
```

Find us on:
- 🐳 [Docker Hub](https://hub.docker.com/r/localxpose/localxpose)
- 📦 [npm](https://www.npmjs.com/package/loclx)
- 🍺 [Homebrew](https://formulae.brew.sh/cask/localxpose)
- 🍫 [Chocolatey](https://community.chocolatey.org/packages/localxpose)
- 📸 [Snapcraft](https://snapcraft.io/localxpose)

</details>

## 🆕 LocalXpose GitHub Action

<div align="center">
  
**✨ NEW: Test and preview without deployment! ✨**

</div>

Our brand new [GitHub Action](https://github.com/LocalXpose/localxpose-action) lets you create secure tunnels right in your workflows. Perfect for:

- 🧪 **Integration Testing** - Test against external services without deploying
- 👀 **Preview Deployments** - Share PR previews instantly
- 🔗 **Webhook Testing** - Receive webhooks in your CI/CD pipeline
- 🚀 **Zero Config** - Works out of the box with your existing setup

```yaml
- name: Start LocalXpose Tunnel
  uses: LocalXpose/localxpose-action@v1
  with:
    port: 3000
    subdomain: preview
```

[**Try it now →**](https://github.com/LocalXpose/localxpose-action) We'd love your feedback! 💬

## 🌟 Features Developers Love

- **🔒 Secure by Default** - HTTPS tunnels with end-to-end encryption
- **⚡ Lightning Fast** - Optimized for low latency
- **🎯 Custom Subdomains** - Professional URLs for your projects
- **🌐 Multiple Protocols** - HTTP, HTTPS, TCP, and UDP support
- **📊 Real-time Analytics** - Monitor traffic and performance
- **🔧 Developer Friendly** - Simple CLI, comprehensive API
- **💪 Production-Grade** - Built for high bandwidth and request volume
- **🛡️ Rock-Solid Reliability** - Resilient infrastructure our customers depend on


## 💻 Quick Example

```bash
# Expose your local web server
loclx tunnel http --to localhost:3000

# Custom subdomain
loclx tunnel http --to 3000 --subdomain awesome
# -> (http, us) awesome.loclx.io => [running]

# TCP tunnel for databases, SSH, etc.
loclx tunnel tcp --to localhost:22 --port 2222
```

## 🤝 Open Source & Community

While our core tunneling service powers thousands of developers daily, we're committed to giving back to the community:

### Our Open Source Projects
- ✨ [**localxpose-action**](https://github.com/LocalXpose/localxpose-action) - GitHub Action for seamless tunnel integration
- 📚 More tools and libraries coming soon!

### We Support
- 💜 [**SaaS-UI**](https://github.com/saas-js/saas-ui) - Proud sponsor of this amazing React component library

*We're working on open-sourcing more of our tooling and libraries. Stay tuned! 🚀*

## 🎉 Join the LocalXpose Community

<div align="center">

**Ready to level up your development workflow?**

[![Create Your Account](https://img.shields.io/badge/Create_Free_Account-6023c0?style=for-the-badge&logo=rocket&logoColor=white)](https://localxpose.io/signup?utm_source=github&utm_medium=profile&utm_campaign=readme&utm_content=main_cta)

*No credit card required • Generous free tier • Cancel anytime*

</div>

---

<div align="center">

### Connect With Us

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=x&logoColor=white)](https://x.com/localxpose)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@localxpose.io)
[![System Status](https://img.shields.io/badge/System_Status-4EE3C2?style=flat-square&logo=instatus&logoColor=white)](https://localxpose.instatus.com)
<!-- [![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/localxpose) -->

<sub>Built with ❤️ by developers, for developers</sub>

</div>
