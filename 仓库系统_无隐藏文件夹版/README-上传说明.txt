========================================
📦 仓库系统 - 上传说明
========================================

由于 Windows 不显示以点开头的文件夹（如 .github），
这个版本把配置文件放在了 "github/workflows/" 文件夹中。

上传到 GitHub 后，你需要做一步简单的操作：

1. 上传本文件夹中的所有文件到 GitHub 仓库
   （包括 github/、app/、build.gradle 等所有文件）

2. 上传完成后，进入 GitHub 仓库页面

3. 找到 "github" 文件夹，点击进入

4. 点击右上角的 "..." 或 "Rename" 
   把文件夹重命名为 ".github"（前面加一个点）

   或者更简单的方法：
   - 在仓库首页点击 "Add file" → "Create new file"
   - 文件名输入：.github/workflows/build-apk.yml
   - 把 github/workflows/build-apk.yml 的内容复制进去
   - Commit
   - 然后删除原来的 github/ 文件夹

5. 完成后，点击 Actions 标签，应该能看到 "Build APK" 工作流

========================================
