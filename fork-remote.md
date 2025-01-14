<!--
 * @Date: 2021-12-16 14:50:54
 * @LastEditors: Future Meng
 * @LastEditTime: 2025-01-14 23:33:08
-->

1. 查看是否添加了更新源
   ```
   git remote -v
   ```
2. 添加更新源
   ```
   git remote add upstream https://github.com/infiniflow/ragflow.git
   ```
3. 从源更新
   ```
   git fetch upstream
   ```
4. 合并源的分支
   ```
   git merge upstream/main
   ```

5. 推送到
   ```
   git push
   ```