# Game Rock, Paper, Scissors, Lizard and Spock for web

## Settings

## Development mode
    
1. create a virtualenv or use docker
2. execute `pip install -r requirements/dev.txt` in your virtualenv or docker
3. define env vars 

    SECRET_KEY_PPTLS=(secret key)
    
    DB_PPTLS=(database name)
    
    DB_USER_PPTLS=(database user)
    
    DB_PASS_PPTLS=(database password)
    
    DB_HOST_PPTLS=(database address (127.0.0.1))
    
    DB_PORT_PPTLS=(database port (5432))
    
    
4. `./manage.py runserver 0.0.0.0:8000`
    
    
