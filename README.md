# Interact with a Large Language Model

This example demonstrates how to interact with a Large Language Model (LLM) via an API endpoint. It simulates sending a user prompt to an LLM inference engine and processing the model's response. The code highlights the typical structure of an API request to an LLM service, similar to how one would use models like Qwen3.8-2.4T-A95B on platforms like DigitalOcean Inference Engine. Note that without a valid API endpoint and key, the script will demonstrate the interaction pattern but will report connection errors.

## Language

`python`

## How to Run

1. Install the `requests` library: `pip install requests`
2. Set your LLM API endpoint and key as environment variables (e.g., `export LLM_API_ENDPOINT='YOUR_API_URL'` and `export LLM_API_KEY='YOUR_KEY'`).
3. Run the script: `python main.py`

## Original Article

This example accompanies the Turkish article: [Büyük Dil Modelleri (LLM'ler) ve Qwen3.8-2.4T-A95B'nin Yeri Nedir?](https://fatihsoysal.com/blog/buyuk-dil-modelleri-llmler-ve-qwen3-8-2-4t-a95bnin-yeri-nedir/).

## License

MIT — see [LICENSE](LICENSE).
