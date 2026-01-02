## How to edit contents in repository

### Easy way
1. Click pencil (Edit file) button on Github Web
2. Edit file
3. Click 'Commit changes' button

### Hard way

#### 1. Clone Repository

```bash
git clone https://github.com/snuuq/reference.git
cd reference
```

#### 2. Edit file in local folder

```bash
# 1. Update to the latest version before starting work
git pull origin main

# 2. Edit files in local folder
code .
# OR just use text editor

# 3. Commit & Push
git add .
git commit -m "feat: add resources"
git push origin main
```

> If you find this difficult, you can use [Github Desktop](https://github.com/apps/desktop)
