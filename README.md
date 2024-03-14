
# **Git**
## **Git flow**

---
### **Init**

**For the first time**

```bash
git flow init
```
---

### **Feature**

**For creating a new feature branch**
```bash
git flow feature start <feature-name>
```

**For finishing a feature branch**
```bash
git flow feature finish <feature-name>
```
---

### **Release**

**For starting a new release branch**
```bash
git flow release start <release-name>
```

**For finishing a release branch**
```bash
git flow release finish <release-name>
```
---

### **Branch**


**For switching the branch or** `git checkout`
```bash
git switch <branch-name>
```
**For to see the branches**
```bash
git branch <branch-name>
```

**For deleting a branch**
```bash
git branch -d <branch-name>
```

**For deleting a branch in remote**
```bash
git push origin --delete <branch-name>
```

**For restoring a file**
```bash
git restore <file-name>
```
---
## **Git fork**

**For see the remote**
```bash
git remote -v
```

**For add the remote**
```bash
git remote add upstream <origin-url>
```

**For pull the remote**
```bash
git pull <remote-name> <remote-branch>
```
