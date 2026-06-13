# DeepSeek API Guide for International Developers

> 🚀 Complete guide to using DeepSeek API from outside China. Save 100x on AI costs.

## Why DeepSeek?

| Model | Input (per 1M tokens) | Output (per 1M tokens) | Quality |
|-------|----------------------|------------------------|---------|
| OpenAI GPT-4o | $15.00 | $60.00 | ⭐⭐⭐⭐⭐ |
| DeepSeek V4-Flash | **$0.14** | **$0.28** | ⭐⭐⭐⭐ |
| DeepSeek V4-Pro | **$0.435** | **$0.87** | ⭐⭐⭐⭐⭐ |

**Same quality. 100x cheaper.**

## Quick Start

### Python

```python
from openai import OpenAI

client = OpenAI(
    api_key="your-deepseek-api-key",
    base_url="https://api.deepseek.com"
)

response = client.chat.completions.create(
    model="deepseek-chat",
    messages=[{"role": "user", "content": "Hello!"}]
)

print(response.choices[0].message.content)
```

### Node.js

```javascript
import OpenAI from 'openai';

const client = new OpenAI({
    apiKey: 'your-deepseek-api-key',
    baseURL: 'https://api.deepseek.com'
});

const response = await client.chat.completions.create({
    model: 'deepseek-chat',
    messages: [{ role: 'user', content: 'Hello!' }]
});

console.log(response.choices[0].message.content);
```

## Payment Solutions for International Users

### Option 1: Recharge Service
Use [ChinaAI.tools](https://www.ziwenh.xyz/#products) to top up your DeepSeek account via PayPal.

### Option 2: Alipay
1. Download Alipay app
2. Link international Visa/Mastercard
3. Pay on DeepSeek's platform

### Option 3: Wise
1. Create Wise account
2. Convert USD to CNY
3. Transfer to DeepSeek's Alipay

## Benchmarks

| Benchmark | DeepSeek V4 | GPT-4o |
|-----------|-------------|--------|
| MMLU | 88.5% | 88.7% |
| HumanEval | 90.2% | 90.2% |
| MATH | 76.8% | 76.6% |

## Cost Comparison

### Customer Support Chatbot (10K messages/month)

| Provider | Monthly Cost |
|----------|-------------|
| GPT-4o | $195.00 |
| DeepSeek V4-Flash | **$0.91** |
| **Savings** | **$194.09 (99.5%)** |

### Content Generation (100K words/day)

| Provider | Monthly Cost |
|----------|-------------|
| GPT-4o | $153,000 |
| DeepSeek V4-Flash | **$673** |
| **Savings** | **$152,327 (99.6%)** |

## Resources

- [DeepSeek Official Docs](https://api-docs.deepseek.com/)
- [Complete Guide](https://www.ziwenh.xyz/blog/how-to-use-deepseek-api-outside-china.html)
- [Price Comparison](https://www.ziwenh.xyz/blog/deepseek-vs-openai-price-comparison-2026.html)

## Contributing

Contributions welcome! Please open an issue or PR.

## License

MIT
