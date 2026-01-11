# ionic

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

Ionic mono-repo root package.json, used mainly to execute build scripts. This package is not published to npm.

## 🚀 Tech Stack

- Node.js

## ✨ Features

- Modern and scalable architecture

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/amitdubeyup/ionic.git
cd ionic

# Install dependencies
npm install
```

## ⚙️ Configuration

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Update the `.env` file with your configuration values.

## 🚀 Usage

```bash
# Build for production
npm run build

```

## 📜 Available Scripts

- `npm run build` - node .scripts/build.js
- `npm run release.dev` - node .scripts/release-dev.js
- `npm run release.prepare` - node .scripts/prepare.js
- `npm run release` - node .scripts/release.js
- `npm run changelog` - conventional-changelog -p angular -i ./CHANGELOG.md -k core -s

## 📁 Project Structure

```
ionic/
├── package.json
├── .env.example
├── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Amit Dubey**

- GitHub: [@amitdubeyup](https://github.com/amitdubeyup)
