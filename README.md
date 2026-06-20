git add .
git commit -m "asus commit"
git push origin main



So you can use:

```python
gemini = OpenAI(base_url="https://generativelanguage.googleapis.com/v1beta/openai/", api_key="AIz....")
gemini.chat.completions.create(...)
```