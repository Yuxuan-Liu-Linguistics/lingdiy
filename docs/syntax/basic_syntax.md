# 句法基础

## 检验成分的测试方法 Constituency Tests 
- 替代法 Substitution
- 移位法 Movement
- 部分问答法 Questions/Fragment Answers

Note1: 通过检验的一定是成分，不通过检验的有可能是成分。（例子招标😆）

我**<u>的</u>**书包落在教室了。

Note2: 词是成分。

## 结构关系 Structural Relations
- 支配 Dominance
    - 节点α支配节点β当且仅当存在从α到β的下行通路。
- 母女节点/姐妹节点 Mothers/Daughters/Sisters
    - 节点α是节点β的母节点当且仅当α直接支配β，称β为α的子女节点。
    - β和γ是姐妹节点当且仅当β和γ有共同的母节点α.
- 终端节点 Terminal Nodes
    - 节点α是终端节点当且仅当α没有子女节点。
- 彻底支配 Exhaustive Dominance
    - 节点α支配字符串S当且仅当
        - i. 节点α彻底支配所有终端t∈S
        - ii. 不存在被α支配的t'∉S
- 成分 Constituents 
    - 成分是由单一节点彻底支配的字符串。

Note：句法学目前假设语言层级结构中只使用二叉树。

## 合并 Merge
### 什么是合并？
- 句法树由重复利用句法学家称作“合并”的操作建构起来。
- 合并操作利用两个元素α和β形成一个二叉成分。
- α和β可以是词，也可以是合并操作输出的成分，也可以一个是词，另一个是更大的成分。
### 合并形成的成分如何命名？
- X = Merge(a, b)，X是a或b的投射，也就是说，a或b的部分性质或特征会传给X.
- x'的概念意味着x的性质由更低的节点投射而来。

<script src="https://giscus.app/client.js"
        data-repo="Yuxuan-Liu-Linguistics/lingdiy"
        data-repo-id="R_kgDOKmTl9g"
        data-category="Announcements"
        data-category-id="DIC_kwDOKmTl9s4CahwC"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>