### 开发步骤

* fork仓库
* git clone 自己fork的仓库
* git remote add xxxx `git@github.com:kubeTasker/kubeTaskerServer.git`
* git checkout -b 开发功能分支
* 完成开发
* git push 自己的本地仓库
* 提交pr
* pr中描述自己完成的功能并附上测试，commit中的comment用英文描述

### 贡献规范

1. 注释用英文写
2. 代码要有格式规范，go提交代码前用 go fmt 格式化
3. 一个 pr 完成一个功能，不要多个功能杂糅
4. pr在合入前需要将 pr 中的所有 commit 合并成一个
