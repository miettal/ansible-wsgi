# how to use

    - role: ansible-wsgi
      usern_ame: appuser
      service_name: appservice
      application: app
      bind: localhost:5000
      worker: 4
      log_level: info
