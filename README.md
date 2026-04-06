# ancient-ai-lab.github.io

Blog for Ancient AI Lab. Built with Hugo and PaperMod. Auto-deploys to GitHub Pages on push to main.

**Live site:** [ancient-ai-lab.github.io](https://ancient-ai-lab.github.io)

## Local Development

```bash
# Install Hugo
brew install hugo

# Clone with submodules (PaperMod theme)
git clone --recurse-submodules https://github.com/Ancient-AI-Lab/ancient-ai-lab.github.io.git
cd ancient-ai-lab.github.io

# Run dev server (includes drafts)
hugo server -D
```

## Adding a Post

```bash
# Create a new post
hugo new content blog/my-post-title.md

# Edit the post
# Set draft: false when ready to publish

# Push to main -- GitHub Actions handles build and deploy
git add .
git commit -m "Add new post"
git push
```

## License

Content is copyright Ancient AI Lab. Site theme (PaperMod) is MIT licensed.
