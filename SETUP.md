# GitHub Profile Setup

Your profile README lives in a repository **with the same name as your GitHub username**.

## Steps

### 1. Create the profile repository on GitHub

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** `Muhoti` (must match your username exactly)
3. **Description:** `Senior Full Stack & GIS Developer — Portfolio`
4. Set to **Public**
5. Check **Add a README file** (you will replace it)
6. Click **Create repository**

### 2. Push this README

```powershell
cd g:\Development\Meru\github-profile
git init
git add README.md
git commit -m "Add professional GitHub profile README"
git branch -M main
git remote add origin https://github.com/Muhoti/Muhoti.git
git push -u origin main
```

If the repo already has a README from GitHub, pull first:

```powershell
git pull origin main --rebase
git push -u origin main
```

### 3. Verify

Visit **https://github.com/Muhoti** — the README should appear at the top of your profile.

### 4. Pin your best repositories

On your GitHub profile, click **Customize your pins** and select up to 6 repos, for example:

- `smsolutions_admin`
- `smsolutions_api`
- `OSL_UMCollect`
- `meru_amis`
- `OSL-Incident-Reporter`
- `MutationSurveyMobile`

### 5. Optional improvements

- Add a profile photo at [github.com/settings/profile](https://github.com/settings/profile)
- Set **Bio:** `Senior Full Stack & GIS Developer | PostGIS · React · Node.js · Flutter`
- Set **Website:** `https://smsolutions.co.ke`
- Add **Pronouns / Location:** Nairobi, Kenya (optional)

## Notes

- This README features all projects from your CV without over-emphasizing any single county repo.
- Many client repos are private — the portfolio describes impact even when code is not public.
- Update the **Featured Projects** section when you ship new work.
