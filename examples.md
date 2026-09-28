# Примеры запросов к API

## Python (requests)
```python
import requests

response = requests.get(
    "https://api.example.com/users",
    headers={"Authorization": "Bearer token"},
    params={"page": 1, "limit": 10}
)
print(response.json())
