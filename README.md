# how to use

    - role: ansible-wsgi
      user_name: appuser
      service_name: appservice
      application: app
      bind: localhost:5000
      log_level: info
      gunicorn_config:
        workers: 4
        worker-connections: 32
        timeout: 300
