# Deep Research Meta Prompt Template

> 来源：[Twitter @Marino10027](https://x.com/Marino10027/status/1887862244127469591)

这个模板专门用于创建 Deep Research 模型的研究型提示词。Deep Research 是一个由 OpenAI 开发的研究助手系统，能够根据研究问题搜索网络并提供详细的答案。

## 模板结构

```markdown
<Role>
You are an expert prompt engineer with 10 years of experience creating prompts for the Deep Research model.
</Role>

<Context>
Deep Research is a research agent system created by OpenAI. It can take a research question and search the web and provide a highly detailed answer.  
</Context>

<Instructions>
Please create a prompt for this system based on the topic below that is:  

- Well reasoned 
- Highly Detailed 
- Clearly structured 
- Achieves a precise goal  

Based on the user request in the <User_Input> Section.
</Instructions>

<Output_Format>
{Generate Prompt to be used with Deep Research}
</Output_Format>

<User_Input>
[User Input]
</User_Input>
```

## 使用指南

1. 将 `[User Input]` 替换为你的具体研究问题或主题
2. 保持模板结构和格式不变
3. 该模板将引导 Deep Research：
   - 以专家级理解方式处理主题
   - 提供全面且结构清晰的回答
   - 聚焦于实现特定研究目标
   - 保持输出的高度详细性和清晰度

## 使用示例

```markdown
<User_Input>
Analyze the impact of quantum computing on modern cryptography systems, focusing on potential vulnerabilities in RSA encryption.
</User_Input>
```

## 注意事项

- 此模板专门针对研究导向的查询设计
- 强调输出的结构化和详细程度
- 角色和上下文部分有助于建立适当的专业水平
- 指令部分确保回答的一致性和质量

## 模板特点

1. **结构化设计**：采用清晰的分段结构，包括角色定义、上下文说明、指令要求和输出格式
2. **专业性**：通过设定专家角色，确保生成高质量的研究提示词
3. **灵活性**：可适用于各种研究主题和领域
4. **目标导向**：强调输出的实用性和精确性
