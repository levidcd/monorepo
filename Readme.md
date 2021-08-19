# 什么是 monorepo?

# 能解决什么问题

# 有哪些方案，有什么优劣

# 有没有实例

- 调整目录结构，将相互关联的项目放置在同一个目录，推荐命名为 packages；
- package.json 添加 `"workspaces": [ "packages/*"`
  ],

`yarn install` 查看生成的依赖

# 怎么运行
  `yarn workspace <workspace_name> <command>` 在指定的package里运行指定的命令

  `yarn workspaces run <command>` 在所有package中运行指定的命令,若某个package中没有对应的命令则会报错

# 是否适用于当前项目
