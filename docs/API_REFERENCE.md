# API Reference & Prompt Tips

## How It Works
1. Upload your resume (PDF/DOCX)
2. Paste the job description
3. AI generates a tailored cover letter

## Prompt Engineering Tips
- **Be specific**: Include the company name and role in the prompt
- **Match keywords**: Extract keywords from job description and ensure they appear
- **Tone matching**: Formal for enterprise, conversational for startups
- **Quantify achievements**: "Increased sales by 30%" > "Improved sales"

## Supported LLM Providers
| Provider | Model | Quality | Speed | Cost |
|----------|-------|---------|-------|------|
| OpenAI | GPT-4o | Excellent | Fast | $$ |
| Anthropic | Claude 3.5 | Excellent | Fast | $$ |
| Google | Gemini Pro | Great | Fast | $ |
| Ollama | Llama 3 | Good | Local | Free |

## Environment Variables
```bash
OPENAI_API_KEY=sk-...        # OpenAI API key
ANTHROPIC_API_KEY=sk-ant-... # Anthropic API key
MODEL_PROVIDER=openai        # openai | anthropic | google | ollama
```

## Example Output
A well-crafted cover letter should:
- Open with a compelling hook related to the company
- Match 70%+ of the job description keywords
- Include 2-3 quantified achievements
- End with a clear call to action
