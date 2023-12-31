---
sidebar_position: 3
---

# 基本原则 & 建议

在和 ChatGPT 对话时，亦或者在使用和设计 prompt 时，有以下几个原则与建议。记住这几个原则，能让你写出更好的 prompt 😁

## 原则一：建议使用最新的模型

如果你是直接使用 AI 产品，比如 ChatGPT 或者 Midjourney，那无需在意这个原则。如果你是通过 API 或者 OpenAI Playground 的方式使用，则建议你先使用最新的模型测试。

## 原则二：Prompt 里最好包含完整的信息

这个是对结果影响最大的因素。比如如果你想让 AI 写一首关于 OpenAI 的诗。

Less effective prompt:

```other
Write a poem about OpenAI.
```

它生成的答案可能就会很宽泛，而更好的方式是增加更多的信息。

Better prompt:

```other
Write a short inspiring poem about OpenAI, focusing on the recent DALL-E product launch (DALL-E is a text to image ML model) in the style of a {famous poet}
```

## 原则三：Prompt 最好简洁易懂，并减少歧义

这个比较好理解，即使你跟人说话，说一些简单的短句，对方也会更容易听懂，AI 也是这样。另外，在 prompt 里也需要减少一些歧义，少用模棱两可的词语。

比如像这个就很不明确，什么叫 not too much more？

```other
The description for this product should be fairly short, a few sentences only, and not too much more.
```

更好的 prompt 是这样的，明确告知要写多少句话，就比较明确：

```other
Use a 3 to 5 sentence paragraph to describe this product.
```

另外需要注意的是，简单并不代表简短。你的 prompt 也可以很长，只要你的 prompt 描述更充分就可以，即使长一点也没有关系。

## 原则四：Prompt 要使用正确的语法、拼写，以及标点

特别是在使用英语的 prompt 的时候，一定要注意语法和拼写。
:::info 🚧
例子待补充
:::

## 原则五：从简单的先开始，并给产品多一点耐心

最后一点算是我个人的建议。如我在前面提到的例子 ` What is 100*100/40*56？`一样，如果发现机器理解错误，不妨补充点信息，不妨多实验几次，给 AI 多一点耐心。
