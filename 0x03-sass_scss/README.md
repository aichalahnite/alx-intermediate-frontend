
# CSS Preprocessors: SASS/SCSS for Efficient Styling

## 📚 Project Overview

This project introduces the basics of using **SASS/SCSS**, a CSS preprocessor that enables more powerful and efficient styling. You'll learn how to install SASS, use variables, nested rules, mixins, and more to simplify your stylesheets.

> **Project Duration**: May 19, 2025 – May 26, 2025  
> **Repository**: `alx-intermediate-frontend`  
> **Directory**: `0x03-sass_scss`  
> **Status**: Mandatory  
> **Review Type**: Manual QA  

---

## ✅ Tasks

### 0. Project Set Up  
**Objective**: Install and set up SASS

#### Instructions:
- Inside the `alx-intermediate-frontend` repository, create a directory named:  
  `0x03-sass_scss`

#### 🐧 Linux Installation (Optional)
- Install Node.js version 20.16 using nvm:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
exit  # then reopen terminal
```

🌍 Install Anywhere (Optional)

- If Node.js is already installed, install SASS via npm:
```bash
npm install sass@3.7.4
```

📝 Required File:
- 0-installation-script: Include the steps you followed to install SASS.

---

### 1. Creating a Sass File to Output Debug Message 'Hello World'

**Objective**: Output a debug message in SASS

**Instructions**:
- Write a SASS file that prints: Hello world using @debug

📝 Required File:
- 0-debug_log.scss

💡 Example:
```scss
@debug "Hello world";
```

---

### 2. Using Sass Variables to Assign Text Color

**Objective**: Use variables to define color for tags

**Instructions**:
- Use a SASS variable to assign the text color #3D3D3D to both body and p tags.

📝 Required File:
- 1-color_variable.scss

💡 Example Output:
```scss
body {
  color: #3D3D3D;
}

p {
  color: #3D3D3D;
}
```

---

### 3. Nesting

**Objective**: Use nested syntax in SASS

**Instructions**:
- In a SASS file:
  - Set no margin or padding for body
  - Set margin of 10px for all p tags inside body

📝 Required File:
- 2-nested_tag.scss

💡 Example Output:
```scss
body {
  margin: 0px;
  padding: 0px;
}

body p {
  margin: 10px;
}
```

---

### 4. Margin Mixins

**Objective**: Create and use mixins for margins

**Instructions**:
- Create a mixin for setting left and right margins
  - body: 10px
  - div: 15px

📝 Required File:
- 3-mixin_margins.scss

💡 Example Output:
```scss
body {
  margin-left: 10px;
  margin-right: 10px;
}

div {
  margin-left: 15px;
  margin-right: 15px;
}
```

---

### 5. Manual Review

Once all files are complete, request a Manual QA Review.

---

## 🗂 Repository Structure

```
alx-intermediate-frontend/
└── 0x03-sass_scss/
    ├── 0-installation-script
    ├── 0-debug_log.scss
    ├── 1-color_variable.scss
    ├── 2-nested_tag.scss
    └── 3-mixin_margins.scss
```

---

🔚 © 2025 ALX - All rights reserved.
