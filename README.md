# University API
## Installation

 Create a virtual environment:

 ```python3 -m venv .venv```

 Activate the virtual environment:

 ```.venv\Scripts\Activate.ps1```

 If powershell blocks the activation, use this: 
 ```Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass.venv\Scripts\Activate.ps1```

 Then install the requirements:

 ```python -m pip install -r requirements.txt```

## Test

Test the following URLs:

```http://127.0.0.1:8000/```

```http://127.0.0.1:8000/students/```

```http://127.0.0.1:8000/students/s1```

```http://127.0.0.1:8000/students/s10```
