# TIGQA: An Expert-Annotated Question-Answering Dataset in Tigrinya
## 动机：
 * 解决资源匮乏语言（如提格雷尼亚语）在自然语言处理（NLP）任务中面临的挑战，特别是在机器阅读理解（MRC）领域。
## 贡献：
  * TIGQA数据集的创建,专家标注，一些baseline没有框架结构
### 该文章仍然使用bert以及2017年ACL的DrQA，质量欠佳 
# PromISe: Releasing the Capabilities of LLMs with Prompt Introspective Search
## 动机：
 * 有的评估基准主要使用统一的手工Prompt，这可能无法充分利用大型语言模型（LLMs）的全部能力。这种单一的提示方式可能导致对LLMs性能的低估
## 方法实现：
 * ![image](https://github.com/bixie6868/project/assets/78329110/fd41f275-9106-43b8-8ff0-5972600efa31)
# K-VQG: Knowledge-aware Visual Question Generation for Common-sense Acquisition（WACV2023）
## 动机：
 * 视觉问题生成（VQG）研究主要集中在从答案或问题类别生成问题，而忽略了引入知识的目标。
## 贡献：
 *  构建了一个新颖的、带有知识注释的VQG数据集K-VQG
 *  提出了一个使用遮蔽知识三元组作为输入的知识感知VQG模型
 *  在构建的数据集上评估了所提出模型的性能
## 构造数据集：
 *  数据集包含：image, question, answer, target knowledge triplet, bounding box of the question target --> 人工标注question
 *  标注过程：
 *   ![image](https://github.com/bixie6868/project/assets/78329110/8ffbf915-7455-4b87-8495-392f91ff8dc2)
## 实验方法：
 * 给定image 以及 target knowledge triplet 生成一个对应的问题
 * ![image](https://github.com/bixie6868/project/assets/78329110/d407444a-a005-4c6e-b634-959ae02064d7)
 * ![image](https://github.com/bixie6868/project/assets/78329110/2e0a2ff8-a5b4-4c3c-9cf5-d22a0b047a9c)
# Advancing Large Multi-modal Models with Explicit Chain-of-Reasoning and Visual Question Generation
## 动机：
* 构建不仅准确而且具备显式推理能力的LMMs，生成数据集促进思维链式推理与提问机制相结合。
## 贡献：
 * 提出结合推理过程合问题生成能力到LLM上
 * 提出一个新的数据集，用于训练
 * 生成显示推理过程和提问的能力



