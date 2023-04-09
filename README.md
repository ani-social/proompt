# proompt
Stable Diffusion Shii

# USAGE
## First run the main.py 
```
python main.py
```

## CODE SNIPPETS
### PYTHON
<code>
import requests

response = requests.post("http://127.0.0.1:7860/run/predict", json={
	"data": [
		"hello world",
	]
}).json()

data = response["data"]
<code>
### JAVASCRIPT
<code>
const response = await fetch("http://127.0.0.1:7860/run/predict", {
	method: "POST",
	headers: { "Content-Type": "application/json" },
	body: JSON.stringify({
		data: [
			"hello world",
		]
	})
});

const data = await response.json();
<code>
