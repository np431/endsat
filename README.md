# ends.at – Simple and Flexible URL Redirects  

## 🚀 What is ends.at?  
**ends.at** provides a quick and easy way to create a short, custom URL that redirects to any link of your choice and lots of shortlinks.  
No need for complex setups—just a **GitHub account** and a simple text file.  

## ⚡ Get Started in 3 Simple Steps  

### 1️⃣ Set Up Your GitHub Repository  
- If you don’t have a GitHub account, [create one here](https://github.com/signup).  
- Click this link to automatically create the necessary repository and file:  
  👉 [Create Repository with Template](https://github.com/new?template_name=endsat&template_owner=endsat&name=endsat)  
- Ensure your repository is **public** so the redirect service can access it.

## 🔧 How It Works  
1. **You get a GitHub repository** called `endsat`.  
2. **You get a file** named `endsat.txt` containing your destination URL.  
3. **That's it!** Visiting `ends.at/your-username` automatically redirects to your chosen link.  

### 2️⃣ Add Your Redirect URL  
- Open the `endsat.txt` file in your new repository.  
- Replace `https://example.com` with the URL you want to redirect to.  
- Click **Commit changes** to save.  

### 3️⃣ Test Your Redirect  
Go to: `https://ends.at/your-github-username` (may take a minute to update each time you save the file)

If everything is configured correctly, you will be redirected immediately. 🎯  

## 🏆 Why Choose ends.at?  
✅ **Easy Setup** – No backend, no coding—just GitHub.  
✅ **Full Control** – Update your redirect anytime by editing `endsat.txt`.  
✅ **Universal Compatibility** – Works with any valid URL.  
✅ **Fast Performance** – Uses GitHub’s raw file service for quick lookups and Cloudflare Workers behind the scenes. 
✅ **Your links aren't tracked**
✅ **It's free**

## ❓ Troubleshooting  
- **404 Error?** → Ensure your repository is public and contains `endsat.txt`.    
- **Seeing an Old URL?** → GitHub caches raw files. Add `?timestamp=12345` to force refresh.  

## FYI
URLs don't need to start with `http://` or `https://`.

## Need to say hello? Send a message to hello [at] ends.at


