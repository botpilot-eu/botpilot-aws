# BotPilot

**BotPilot** is an open source chatbot platform designed for educational institutions and organizations. It empowers you to launch privacy-friendly, scalable AI chatbots tailored for a wide variety of educational scenarios—all with minimal technical overhead.

---

## 🚀 Features

- **Instant Chat Launch**  
  Spin up preconfigured chatbot sessions simply by sharing a URL.

- **Flexible System Prompts**  
  Manage context-specific system prompts for different teaching, support, or informational use cases. Adapt the bot’s personality and behavior with ease.

- **Multi-Integration Support**  
  Seamlessly connect to major LLM APIs including OpenAI, Claude (Anthropic), and extensible support for others.

---

## 🎯 Design Goals

- **Frustration-Free**  
  User and admin interfaces are streamlined for maximum clarity and ease of use.

- **Highly Scalable & Low-Fixed-Cost**  
  Runs serverlessly with AWS Lambda, optimizing for peak usage and minimal idle costs.

- **Self-Hosted & Flexible**  
  Maintain full data control by deploying in your own AWS account. Easy configuration via YAML, so you don’t need to be a developer to adapt the system to your needs.

- **Unlimited Extensibility**  
  Harness the power of community or custom Python plugins to add features, integrations, or specialized workflows.

- **Enterprise-Ready**  
  Robust permission system enables secure, role-based access. Isolate user groups (institutes, classes, teams) with independent spaces.

- **Compliant & Proven**  
  Built to align with GDPR (DSGVO) and EU AI Act requirements. Battle-tested in real-world educational environments.

---

## 🛠️ Tech Stack

- **Backend:** Python on AWS Lambda (serverless)
- **Frontend:** Vue.js (lightweight & responsive)
- **LLM Integration:** OpenAI API, Claude, extendable

---

# Stay tuned, the code will arrive soon!


## 🌱 Getting Started

1. **Deploy Backend:**  
   - Clone repository.
   - Configure AWS Lambda functions (see `/backend/README.md`).
2. **Configure Bots:**  
   - Define your bots and prompts in YAML (see sample in `/config/bots.yaml`).
3. **Deploy Frontend:**  
   - Build and host Vue.js app (see `/frontend/README.md`).
4. **Set Up Integrations:**  
   - Add your API keys for OpenAI, Claude, or other LLM providers.
5. **Share Chat URLs:**  
   - Launch chats with a single link, ready for student or staff engagement.

---

## 🔌 Extending with Plugins

- Add new features, LLM providers, or integrations by dropping in Python plugins.
- See `/plugins/README.md` for guides and examples.

---

## 🔒 Security and Compliance

- Enforced data protection and privacy best practices.
- Role-based access control for all management and usage features.
- All data stored securely in your environment.

---

## 📄 Documentation

- [User Guide](docs/user_guide.md)
- [Admin Guide](docs/admin_guide.md)
- [YAML Configuration Reference](docs/configuration.md)
- [Plugin Development](docs/plugins.md)

---

## 💬 Community & Support

- [GitHub Issues](https://github.com/botpilot-eu/botpilot-aws/issues)
- [Discussions Forum](https://github.com/botpilot-eu/botpilot-aws/discussions)

---

## 📜 License

[MIT License](LICENSE)