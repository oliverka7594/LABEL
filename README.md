[ Project Overview ]
LABEL is a dynamic web application that enables users to create account, log in/log out, creating labels, deleting or modifying them.

To showcase my tech stacks within a tight time frame, the feature "creating labels" and label rendering are implemented with both server-side and client-side dynamic (React + REST API + Flask). The remaining features are solely through server side processing (Flask) for simplicity and efficiency.
______________________________________________________________________

[How to run the web locally]
1. make sure you "cd label_client_dy"
2. (create an virtual env), "pip install -r requirements.txt"
3. "pip install -e ."
4. "./bin/labelrun"
5. create an account and explore
______________________________________________________________________

[ Schedule ]
May 30          May 31              June 2                      
React recap     Work flow design    Framework design + setup    
                Database design     Server-side implementation 
                Framework design    (label/templates)

June 3                              June 4
Server-side implementation          Unit tests
(label/views)
Client-side implementation
(label/api + label/js)
______________________________________________________________________

[ File Tree ]
label
├── __init__.py
├── config.py
├── model.py
├── api
│   ├── __init__.py
│   ...
│   └── index.html
├── js
│   └── ...
├── static
│   ├── css
│   │    └── style.css
│   └── js
│       └── ...
├── templates
│   ...
│   └── index.html
└── views
    ├── __init__.py
    ...
    └── index.py
______________________________________________________________________

Feel free email me if you run into any problems:
olikang2333@gmail.com
______________________________________________________________________