# 📖 AI Interactive E-Book Generator 互动童书自动生成工作流

能够根据用户输入的主题，自动创作适合5-12岁儿童的英文绘本，并生成包含互动元素的HTML和PDF双格式输出。

用AI赋能儿童教育，让每个孩子都能拥有个性化的互动绘本。

# 这个工作流有3个亮点： 
第一，支持难度自适应，根据年龄段自动调整语言复杂度； 
第二，保证角色一致性，通过image-to-image技术保证主角跨页面一致； 
第三，集成了互动元素，包括点击、拖拽、问答等，提升阅读体验。


# 项目结构说明

# 本地运行
## 运行流程
bash scripts/local_run.sh -m flow

## 运行节点
bash scripts/local_run.sh -m node -n node_name

# 启动HTTP服务
bash scripts/http_run.sh -m http -p 5000

