
# RepoKit — A GitHub Token Toolbox 🛠️

A clean, fast, and privacy-respecting GitHub utility built with 100% vanilla HTML, CSS, and JavaScript.

## 🧠 What is RepoKit?

**RepoKit** is a lightweight, open-source tool that gives you full control over your GitHub account through your browser — using a **GitHub personal access token**. No installs, no servers, just raw power.

It supports bulk actions like deleting repositories, editing topics, un-starring forks, closing issues, and more.

## ✨ Features

- 🔥 **Repo Nuker** - Delete repositories in bulk  
- 📦 **Repo Archiver** - Archive or unarchive repos  
- ⭐ **Star Sweeper** - Unstar repositories you don't care about  
- 🐛 **Issue Wiper** - Close lingering issues across all repos
- 🍴 **Fork Sweeper** - Delete forked repos you no longer need
- ✏️ **Repo Renamer** - Rename multiple repositories at once
- 🏷️ **Repo Tagger** - Edit topics and tags in bulk
- 🔒 **Privacy Switcher** - Change repo visibility (public/private)
- 📝 **Repo Desc Editor** - Update descriptions and homepage URLs
- 📖 **README Syncer** - Push README templates to multiple repos
- 🧪 **Frontend Only** - Zero backend, runs entirely in your browser

## ⚙️ How to Get Your GitHub Token

To use RepoKit, you'll need a GitHub Personal Access Token with the following scopes:

**Required scopes:** `repo`, `delete_repo`, `user`

### Step-by-Step Instructions:

1. **Generate Token**: 👉 [Click here to generate your token](https://github.com/settings/tokens/new?scopes=repo,delete_repo,user&description=RepoKit%20Token)

2. **Set Token Name**: Use "RepoKit Token" or any name you prefer

3. **Select Scopes**: Ensure these are checked:
   - ✅ `repo` (Full control of private repositories)
   - ✅ `delete_repo` (Delete repositories) 
   - ✅ `user` (Read user profile data for design only) 

4. **Generate & Copy**: Click "Generate token" and copy the token immediately

5. **Paste in RepoKit**: Enter the token in the input field and click "Connect"

⚠️ **Security Note**: Your token is stored only in memory during your session and is never saved to disk or localStorage.

## 🚀 Getting Started

1. **Open RepoKit** - Visit the deployed app or open `index.html` in your browser
2. **Connect Token** - Paste your GitHub token and click "Connect"
3. **Choose Tools** - Click on any tool card to expand it
4. **Load Data** - Click "Load Repositories" or relevant load button
5. **Select & Execute** - Choose items and perform bulk actions

## 🛠️ Tech Stack

- **100% Vanilla** - Pure HTML, CSS, JavaScript
- **No Dependencies** - Zero external libraries or frameworks
- **GitHub REST API v3** - Official GitHub API integration
- **Privacy First** - No tracking, no data collection
- **Mobile Responsive** - Works on desktop and mobile devices

## 📁 Project Structure

```
RepoKit/
├── index.html          # Complete single-file application
├── README.md          # This documentation
└── (optional favicon)
```

## 🔧 Features in Detail

### 🔥 Repo Nuker
- Loads all your repositories
- Select multiple repos for deletion
- Confirmation dialog prevents accidents
- Permanent deletion warning

### 📦 Repo Archiver  
- Toggle archive status on multiple repos
- Filter by active/archived status
- Preserves repository but makes it read-only

### ⭐ Star Sweeper
- View all your starred repositories
- Filter by language, name, or date
- Bulk unstar repos you no longer follow

### 🐛 Issue Wiper
- Lists open issues across all repositories
- Add optional closing comment
- Bulk close selected issues

### 🍴 Fork Sweeper
- Identifies all forked repositories
- Shows parent repository information
- Delete unused forks in bulk

### ✏️ Repo Renamer
- Inline editing of repository names
- Bulk rename with single action
- Real-time validation

### 🏷️ Repo Tagger
- Edit repository topics/tags
- Comma-separated topic input
- Bulk topic updates

### 🔒 Privacy Switcher
- Toggle between public/private status
- Visual indicators for current status
- Bulk privacy updates

### 📝 Repo Desc Editor
- Edit repository descriptions
- Update homepage URLs
- Save all changes at once

### 📖 README Syncer
- Paste or type README template
- Select target repositories
- Push to multiple repos simultaneously
- Handles existing README updates

## 🛡️ Security & Privacy

- **Token Security**: Tokens are stored only in browser memory
- **No Server**: Everything runs client-side in your browser
- **No Tracking**: Zero analytics or data collection
- **Open Source**: Full code transparency
- **Local Control**: You control all actions and data

## 🚀 Deployment

### GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access via `https://09sychic.github.io/repokit`

### Local Usage
1. Download `index.html`
2. Open in any modern web browser
3. Works offline after initial load


## 🔄 API Rate Limits

GitHub API has rate limits:
- **5,000 requests/hour** for authenticated requests
- RepoKit shows current rate limit status
- Large operations may need multiple sessions

## ⚠️ Important Warnings

- **Irreversible Actions**: Repository deletion cannot be undone
- **Token Security**: Never share your personal access token
- **Backup First**: Consider backing up important repositories
- **Test Small**: Try operations on test repositories first

## 🐛 Troubleshooting

### Token Issues
- Ensure all required scopes are selected
- Check token hasn't expired
- Verify token has necessary permissions

### API Errors
- Check GitHub API status page
- Verify repository permissions
- Ensure stable internet connection

### Browser Issues
- Use modern browser (Chrome, Firefox, Safari, Edge)
- Enable JavaScript
- Check browser console for errors

## 🧾 License

MIT License - Feel free to use, modify, and distribute.

## 🙏 Credits & Acknowledgments

**RepoKit** is a side project by **Drae**

- 🧑‍* *GitHub**: [@09sychic](https://github.com/09sychic)
- 💬 **Discord**: `@drae`
- 🛠️ **Icons**: [Octicons](https://primer.style/octicons) & [Heroicons](https://heroicons.com)
- 🎨 **Inspiration**: GitHub's clean design language
- 🔧 **API**: GitHub REST API v3

---

## 💡 Contributing

Found a bug or want a feature? 
- Open an issue on GitHub
- Submit a pull request
- Suggest improvements


---

**⚡ Built with vanilla web technologies for maximum compatibility and zero dependencies.**

*Happy repository management! 🚀*
