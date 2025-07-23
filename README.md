## 通过npm安装

```bash
# 1. 安装 Node.js （≥ 20）
curl -qL https://www.npmjs.com/install.sh | sh

# 2. 全局安装 qwen-code
npm install -g @qwen-code/qwen-code

# 3. 验证安装 
qwen --version
```


## 通过源码安装 

```bash
# 1. 克隆仓库
git clone https://github.com/QwenLM/qwen-code.git

# 2. 安装依赖并全局部署
cd qwen-code
npm install
# npm install -g .

# 3. 验证安装：
qwen --version
```


## 使用教程

```bash
# 1. cli启动
qwen

# 2. 按提示输入key，url和model
> sk-xxxx
> https://dashscope.aliyuncs.com/compatible-mode/v1
> qwen3-coder-plus

# 3. 输入问题
>  Describe the main pieces of this system's architecture



# 或直接在shell中配置临时环境变量
export OPENAI_API_KEY="sk-xxx"
export OPENAI_BASE_URL="https://dashscope.aliyuncs.com/compatible-mode/v1"
export OPENAI_MODEL="qwen3-coder-plus"

# 或源码安装时在项目根目录创建 .env 文件
OPENAI_API_KEY=sk-xxx
OPENAI_BASE_URL=https://dashscope.aliyuncs.com/compatible-mode/v1
OPENAI_MODEL=qwen3-coder-plus
```


## 相关参考

1. https://www.kdjingpai.com/qwen-codejiyu-g/
2. 
