# CLAUDE.md - AI Assistant Guide for User-Lawn Repository

## Repository Overview

**Repository Type:** GitHub Profile README
**Owner:** Lawn (Junyoung Lee - 이준영)
**Purpose:** Personal GitHub profile page showcasing professional identity, interests, and contact information
**Primary Language:** Korean (한국어) with English elements
**Last Updated:** 2025-11-30

---

## 🎯 Repository Purpose

This is a special GitHub repository that serves as the user's **GitHub Profile README**. When a repository named `username/username` exists with a README.md file, GitHub displays that README on the user's profile page. This repository creates Lawn's professional online presence.

### Key Objectives:
1. **Professional Identity**: Present Lawn as a Product Manager and entrepreneur
2. **Technical Interests**: Highlight focus on UX, mobile environments, and human-computer interaction
3. **Accessibility**: Provide multiple contact channels (LinkedIn, Velog, Instagram, Email)
4. **Personal Branding**: Maintain a consistent, professional, and friendly tone

---

## 📁 Repository Structure

```
User-Lawn/
├── README.md           # Main profile content (displayed on GitHub profile)
├── gif/
│   └── Lawn.gif       # Animated GIF used in profile (2MB)
└── logo/
    ├── Gmail.png      # Email icon/logo
    ├── Veloglogo.png  # Velog (Korean blogging platform) logo
    ├── instagram.png  # Instagram logo
    └── linkedin.png   # LinkedIn logo
```

### File Purposes:

#### README.md
- **Current State**: Nearly empty (single newline)
- **Expected State**: Should contain profile introduction, social links, and professional information
- **Previous Content**: Included bilingual introduction, social media links, animated GIFs, and professional details
- **Format**: GitHub-flavored Markdown with HTML for advanced layout

#### Assets (gif/ and logo/)
- **gif/Lawn.gif**: Decorative animated GIF for visual appeal (external URL used in README)
- **logo/**: Social media icons (currently external URLs are used instead of local files)
- **Note**: The README historically uses external URLs from user-images.githubusercontent.com rather than relative paths to local assets

---

## 🎨 Content Conventions

### Language and Tone
- **Primary Language**: Korean (한국어)
- **Secondary Language**: English for international accessibility
- **Tone**: Professional yet personable, using emojis strategically (🌱, 🤖, etc.)
- **Voice**: First-person, friendly introduction style

### Content Structure (Historical Pattern)
1. **Header**: Greeting and name with signature emoji (🌱)
2. **Social Links**: Horizontal icon links (LinkedIn, Velog, Instagram)
3. **Introduction**: Brief professional bio in Korean
4. **Background**: Academic and research experience
5. **Contact Section**: "More About Me" with detailed links
6. **Visual Elements**: Right-aligned GIFs for visual interest

### Formatting Standards
- **HTML + Markdown Mix**: Uses both HTML tags and Markdown for layout control
- **Image Alignment**: `<img align="right">` for visual elements
- **Link Format**: HTML `<a>` tags with image icons for social media
- **Icon Height**: Consistently 25px for social media icons, 130-150px for GIFs
- **Emoji Usage**: Strategic use (👋, 🌱, 🤖, 🧐, 💬, 📫, 📚)

---

## 👤 Profile Information

### Professional Identity
- **Name**: Lawn (이준영 / Junyoung Lee)
- **Role**: PM (Product Manager) and Entrepreneur (사업가)
- **Signature**: 🌱 Lawn (grass/lawn emoji as personal brand)

### Professional Interests
- **UX Focus**: Mobile environment user experience
- **Background**: Industrial Engineering (산업공학) major
- **Research**: Human factors engineering related to facility access for students with disabilities
- **Current Focus**: WWDC Human Interface Guidelines study and blogging

### Contact Channels
- **Email**: name.lawn@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/junyoung-lee-lawn/
- **Velog** (Korean blog): https://velog.io/@lawn
- **Instagram**: https://www.instagram.com/hi.lawn
- **Brunch** (Korean blog): https://brunch.co.kr/@3756ea803def4ac

---

## 🔧 Development Workflows

### Making Changes to README.md

#### Before Editing:
1. **Read Current State**: Always read README.md first to understand current content
2. **Check Git History**: Review recent commits to understand evolution
3. **Verify Assets**: Confirm referenced images/GIFs are accessible
4. **Consider Context**: This is a personal profile - maintain user's voice and style

#### Content Guidelines:
1. **Preserve Personal Voice**: Keep Lawn's friendly, professional tone
2. **Maintain Bilingual Approach**: Include both Korean and English where appropriate
3. **Update Carefully**: Profile READMEs are highly personal - confirm changes align with user intent
4. **Visual Balance**: Maintain right-aligned decorative elements
5. **Link Validity**: Test all external links before committing

#### Technical Considerations:
- **External URLs**: README uses `https://user-images.githubusercontent.com/` for images
- **Local Assets**: Local logo/ and gif/ files exist but may not be actively used
- **HTML Support**: GitHub README supports HTML - use for advanced layouts
- **Markdown Compatibility**: Ensure GitHub-flavored Markdown compatibility
- **Mobile Responsiveness**: Consider how content renders on mobile GitHub

### Git Workflow

#### Branch Strategy:
- **Development Branches**: Use `claude/` prefixed branches with session IDs
- **Current Branch**: `claude/claude-md-milsieg4o1ngi8na-019uWD1kSfKzFNnBS2sbZFBf`
- **Protection**: Never push to branches not matching the session ID pattern

#### Commit Practices:
```bash
# Standard workflow
git add README.md
git commit -m "Update profile: [describe changes]"
git push -u origin claude/claude-md-milsieg4o1ngi8na-019uWD1kSfKzFNnBS2sbZFBf

# For new assets
git add logo/newlogo.png
git commit -m "Add new social media logo"
git push -u origin <branch-name>
```

#### Commit Message Style:
- **Format**: `Update README.md` or `Update profile: [specific change]`
- **Be Descriptive**: Explain what aspect of the profile was updated
- **Examples**:
  - "Update README.md" (historical pattern - simple)
  - "Update profile: Add new blog link"
  - "Update profile: Refresh professional bio"
  - "Add new social media icons"

### Asset Management

#### Adding New Images:
1. **Location**: Place in appropriate directory (`logo/` or `gif/`)
2. **Naming**: Use descriptive, lowercase names (e.g., `github.png`)
3. **Size**: Optimize images (logos ~7-60KB, GIFs <2MB)
4. **Format**: PNG for logos (transparency), GIF for animations
5. **Usage**: Reference in README with relative or absolute URLs

#### Updating Assets:
1. **Backup**: Keep previous versions if replacing
2. **References**: Update all README references to new filenames
3. **Testing**: Verify images display correctly on GitHub

---

## 🚨 Important Constraints

### What NOT to Do:
1. **❌ Don't Delete Content Without Confirmation**: Profile READMEs are personal - always confirm removals
2. **❌ Don't Change Personal Information**: Name, contact details, professional role require user approval
3. **❌ Don't Add Unverified Links**: Only include links user has provided or verified
4. **❌ Don't Override Language**: Maintain Korean-primary, English-secondary pattern
5. **❌ Don't Remove Emojis**: They're part of personal branding (especially 🌱)
6. **❌ Don't Push to Wrong Branch**: Only push to `claude/` prefixed branches with matching session IDs
7. **❌ Don't Over-Engineer**: Keep profile simple, personal, and authentic

### What TO Do:
1. **✅ Preserve Personal Voice**: Keep friendly, professional Korean tone
2. **✅ Maintain Visual Balance**: Keep decorative elements and layout structure
3. **✅ Verify Links**: Test external URLs before committing
4. **✅ Ask When Uncertain**: Profile content is personal - confirm major changes
5. **✅ Keep It Simple**: Avoid complex layouts that might break on mobile
6. **✅ Document Changes**: Clear commit messages for profile updates
7. **✅ Test Rendering**: Preview how changes appear on GitHub

---

## 🔍 Common Tasks

### Task: Update Professional Bio
```markdown
**Steps:**
1. Read current README.md
2. Identify bio section (typically after social links)
3. Maintain Korean-primary language
4. Preserve formatting and emojis
5. Commit: "Update profile: Refresh professional bio"
```

### Task: Add New Social Media Link
```markdown
**Steps:**
1. Obtain platform URL and logo/icon
2. Add logo to logo/ directory (if using local)
3. Insert link in social links section
4. Match existing format (HTML <a> tag with <img>)
5. Set height='25px' for consistency
6. Test link functionality
7. Commit: "Update profile: Add [platform] link"
```

### Task: Update Contact Information
```markdown
**Steps:**
1. Confirm new contact details with user
2. Update "More About Me" section
3. Verify all links are functional
4. Update any inline email/contact references
5. Commit: "Update profile: Update contact information"
```

### Task: Refresh GIFs/Images
```markdown
**Steps:**
1. Add new GIF to gif/ directory or obtain external URL
2. Update <img> tags in README
3. Verify alignment (align='right') is preserved
4. Check dimensions (height='130-150px' for large GIFs)
5. Test rendering on GitHub preview
6. Commit: "Update profile: Refresh visual elements"
```

---

## 📝 Profile Content Template

### Historical Structure Reference:
```markdown
## Hi 👋, I'm Lawn🌱

[Social Media Icons - Horizontal Left-Aligned]
<a href='URL'><img align='left' alt="Platform" src="URL" height='25px'/></a>

[Right-Aligned Decorative GIF]
<img align="right" alt="GIF" src="URL" height="130px"/>

[Korean Introduction Paragraph]
PM(Product Manager)이자 사업가 🌱Lawn 입니다.
<br/>
> [Details about interests and background]

[Second Right-Aligned GIF]
<img align="right" alt="GIF" src="URL" height="150px"/>

### 🧐 More About Me:
- 💬 &nbsp; [Contact info]
- 📫 &nbsp; [Social links]
- 📚 &nbsp; [Blog/writing links]
```

---

## 🌐 External Resources

### Image Hosting:
- **Current Method**: `https://user-images.githubusercontent.com/74142881/[ID].png`
- **Alternative**: Use relative paths to local assets in `logo/` and `gif/`
- **Best Practice**: Local assets are more reliable but external URLs currently used

### Useful Links for AI Assistants:
- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [GitHub README Best Practices](https://github.com/matiassingers/awesome-readme)

---

## 🎓 Context for AI Assistants

### Repository Category:
This is a **personal branding** repository, not a software project. Treat it as:
- **High Personal Value**: Changes directly impact user's professional presence
- **Public Facing**: Visible to all GitHub visitors on user's profile
- **Creative Content**: Balance professional information with personality
- **Multilingual**: Respect Korean-primary, English-secondary approach

### When Working on This Repository:
1. **Read First**: Always read existing content before suggesting changes
2. **Ask Questions**: Confirm intent for personal content changes
3. **Preserve Style**: Maintain existing tone, voice, and formatting patterns
4. **Test Thoroughly**: Preview changes as they'll appear on GitHub
5. **Cultural Sensitivity**: Respect Korean language and cultural elements
6. **Professional Context**: Remember this represents someone's professional identity

### Current State Alert:
⚠️ **README.md is currently nearly empty** - it appears content was recently removed or reset. The previous version (HEAD~1) contained rich profile content. When updating, consider restoring or creating new comprehensive profile content.

---

## 📊 Repository Statistics

- **File Count**: 3 directories, ~7 files (excluding .git)
- **Primary File**: README.md
- **Asset Count**: 4 logos, 1 GIF
- **Languages**: Markdown, HTML
- **Repository Size**: ~2MB (mostly Lawn.gif)
- **Commit History**: Multiple README.md updates (recent pattern)
- **Branch**: Currently on `claude/claude-md-milsieg4o1ngi8na-019uWD1kSfKzFNnBS2sbZFBf`

---

## 🔄 Version History Notes

Based on git history analysis:
- **Recent Pattern**: Multiple "Update README.md" commits
- **Content Evolution**: README has been updated frequently
- **Stability**: Asset files (logo/, gif/) appear stable
- **Current State**: README content recently cleared/minimal

---

## ✅ Quick Checklist for AI Assistants

Before making changes:
- [ ] Read current README.md content
- [ ] Understand user's request and intent
- [ ] Check if changes align with personal branding
- [ ] Verify all links and assets are valid
- [ ] Preview how changes will render on GitHub
- [ ] Confirm language/tone matches existing style
- [ ] Test on correct git branch
- [ ] Write clear commit message
- [ ] Push to correct claude/ branch

---

## 📞 Questions to Ask User

When uncertain about changes:
1. "Should I restore the previous README content or create new content?"
2. "Do you want to use local assets (logo/, gif/) or continue with external URLs?"
3. "Should I maintain the Korean-primary language approach?"
4. "Are your contact details (email, social links) still current?"
5. "Would you like to add or update any professional information?"
6. "Should I preserve the existing visual layout with right-aligned GIFs?"

---

**Last Updated**: 2025-11-30
**Maintained By**: Claude AI Assistant
**For**: Lawn (이준영 / Junyoung Lee)
**Repository**: https://github.com/User-Lawn/User-Lawn
