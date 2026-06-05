# Community 代码样例

本目录保留社区互动相关的 C# 后端样例代码。

## 包含文件

- `RecipeCommentsController.cs`：评论 API 入口，包含评论列表、创建、删除和评论点赞。
- `RecipeCommentService.cs`：评论业务逻辑，包含评论权限校验、评论创建、删除和点赞切换。
- `RecipeLikeService.cs`：菜谱点赞逻辑，包含事务处理、并发冲突处理和计数更新。
- `RecipeSaveService.cs`：菜谱收藏逻辑，包含收藏切换、分类查询和计数统计。
- `RecipeInteractionService.cs`：用户互动事件记录，用于支持行为统计和推荐信号。

这些文件用于展示社区模块的 API 设计、业务校验、事务处理和互动数据建模思路。
