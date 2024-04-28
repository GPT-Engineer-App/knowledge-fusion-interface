# knowledge-fusion-interface

用中文输出下面功能界面，一级、二级界面都需要，并合并在一个软件界面上
：1. 实体提取界面：
- 功能：
- 展示自动提取的各类实体。
- 显示实体类型，并提供手动确认和编辑功能。

 2. 关系抽取界面：
- 功能：
- 展示不同实体之间的关系，如“属于”、“部分-整体”、“因果”等。
- 允许用户查看和编辑关系，并添加新的关系。

 3. 事件抽取界面：
- 功能：
- 显示从数据中提取的各类事件。
- 提供事件类型判断和属性确定功能。

 4. 概念抽取界面：
- 功能：
- 展示关键的概念词和概念短语。
- 显示概念的层次和类别，并支持手动编辑。

 5. 知识融合界面：
- 功能：
- 展示来自不同数据源抽取的知识。
- 提供融合、去重和消歧功能，确保知识库一致性。

 6. 知识推理界面：
- 功能：
- 基于知识库中的知识与逻辑关系，展示自动推理和新知识发现。
- 支持用户探索推理过程，查看推理结果。

 7. 知识应用界面：
- 功能：
- 展示知识库中的知识应用于不同场景，如问答、信息检索、智能推荐等。
- 提供应用场景选择和应用效果展示。

 8. 知识维护界面：
- 功能：
- 提供人工或机器方式维护知识库的功能。
- 支持知识补充、修正和升级，确保知识准确性和最新性。

9. 知识质量评估界面：
- 功能：
- 设定评估指标和方法对知识库的质量进行评估。
- 显示评估结果，并提供改进建议。


## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/knowledge-fusion-interface.git
cd knowledge-fusion-interface
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
