# GitHub Pages Setup Instructions

## Important: Complete These Steps to Deploy Your Resume

Your resume template is ready! Follow these steps to make it live on GitHub Pages:

### Step 1: Enable GitHub Pages with GitHub Actions

1. Go to your repository: https://github.com/Vrushabh59/Vrushabh-resume
2. Click on **Settings** (top menu)
3. In the left sidebar, scroll down to **Code and automation** section
4. Click on **Pages**
5. Under **Build and deployment**:
   - **Source**: Select **"GitHub Actions"** from the dropdown
   - (Do NOT select "Deploy from a branch")
6. Save the settings

### Step 2: Merge the Pull Request

1. Go to the Pull Request: https://github.com/Vrushabh59/Vrushabh-resume/pull/1
2. Review the changes
3. Click **"Merge pull request"**
4. Click **"Confirm merge"**

### Step 3: Wait for Deployment

After merging:
1. Go to the **Actions** tab in your repository
2. You'll see a workflow running called "Deploy Resume to GitHub Pages"
3. Wait for it to complete (usually takes 1-2 minutes)
4. Once complete, your resume will be live!

### Step 4: Access Your Resume

Your resume will be available at:
**https://vrushabh59.github.io/Vrushabh-resume/**

## Customizing Your Resume

Edit the `index.html` file to add your actual information:

### What to Update:

1. **Personal Information** (Lines 188-194):
   - Name (currently "Vrushabh Dave")
   - Title (currently "Software Developer")
   - Email
   - GitHub profile link
   - LinkedIn profile link
   - Location

2. **Professional Summary** (Lines 201-206):
   - Write your own professional summary

3. **Technical Skills** (Lines 211-237):
   - Update programming languages
   - Update frameworks and libraries
   - Update tools and technologies

4. **Professional Experience** (Lines 242-268):
   - Add your real work experience
   - Include company names, dates, and responsibilities

5. **Projects** (Lines 273-296):
   - Add your actual projects
   - Include project descriptions and technologies

6. **Education** (Lines 301-307):
   - Add your educational background
   - Include university name, degree, and dates

7. **Certifications** (Lines 312-316):
   - Add your certifications

8. **Achievements** (Lines 321-326):
   - Add your achievements and awards

### Making Changes:

1. Edit `index.html` in GitHub or locally
2. Commit your changes
3. Push to the `main` branch
4. GitHub Actions will automatically redeploy your updated resume

## Need Help?

- Check the README.md file for more details
- The template is mobile-responsive and print-friendly
- Test locally by opening index.html in your browser

---

**Note**: Make sure to update the LinkedIn URL with your actual profile, or remove it if you don't have one.
