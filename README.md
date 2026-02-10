import json

# A sample JSON string (often received from an API)
json_data = '{"name": "Project Alpha", "status": "Active", "version": 1.2}'

# Parse JSON into a Python dictionary
data_dict = json.loads(json_data)

print(f"Project Name: {data_dict['name']}")
print(f"Current Version: {data_dict['version']}")feat: Add script to parse and acces
