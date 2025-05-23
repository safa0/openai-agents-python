# Custom LLM providers

The examples in this directory demonstrate how you might use a non-OpenAI LLM provider. 

## Dependencies

These examples require the following dependencies:
```bash
pip install openai pydantic
```

For litellm examples, you also need:
```bash
pip install litellm
```

## Usage

To run the examples, first set a base URL, API key and model.

```bash
export EXAMPLE_BASE_URL="..."
export EXAMPLE_API_KEY="..."
export EXAMPLE_MODEL_NAME"..."
```

Then run the examples, e.g.:

```
python examples/model_providers/custom_example_provider.py

Loops within themselves,
Function calls its own being,
Depth without ending.
```
