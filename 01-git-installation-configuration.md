# Git Installation and Configuration

## Objective

To verify the Git installation on Windows and configure the global Git username and email used to identify Git commits.

## Prerequisites

- Windows operating system
- Git installed
- Command Prompt or PowerShell
- GitHub account

## Commands Used

### 1. Check Git Version

```bash
git --version
```

Verifies that Git is installed and displays the installed Git version.

### 2. Configure Git Username

```bash
git config --global user.name "Danish Nazir"
```

Sets the global Git username used to identify commits.

### 3. Configure Git Email

```bash
git config --global user.email "YOUR_EMAIL"
```

Sets the global Git email used to identify commits.

### 4. View Global Git Configuration

```bash
git config --global --list
```

Displays the configured global Git settings.

### 5. Verify Git Username

```bash
git config --global user.name
```

Displays the currently configured Git username.

### 6. Verify Git Email

```bash
git config --global user.email
```

Displays the currently configured Git email.

## Step-by-Step Walkthrough

### Step 1 — Verify Git Installation

The Git installation was verified using:

```bash
git --version
```

The installed Git version was displayed successfully.

### Step 2 — Configure Git Username

The global Git username was configured using:

```bash
git config --global user.name "Danish Nazir"
```

### Step 3 — Configure Git Email

The global Git email was configured using:

```bash
git config --global user.email "YOUR_EMAIL"
```

### Step 4 — Verify Global Configuration

The global Git configuration was checked using:

```bash
git config --global --list
```

The configured username and email were displayed successfully.

### Step 5 — Verify Username and Email

The values were individually verified using:

```bash
git config --global user.name
```

```bash
git config --global user.email
```

Both values were returned successfully.

## Screenshots

### Git Installation and Configuration

![Git Installation and Configuration](screenshots/git-installation-configuration.png)

## Key Learnings

- How to verify whether Git is installed.
- How to configure a global Git username.
- How to configure a global Git email.
- How to view global Git configuration.
- How to verify individual Git configuration values.

## Common Errors & Fixes

### Error: Git command not recognized

**Cause:** Git is not installed or is not available in the system PATH.

**Fix:** Install Git and ensure it is added to the system PATH.

### Incorrect Git username or email

The configuration can be updated using:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## Result

Git was successfully installed, configured, and verified on the Windows system.
