for windows : bind volumes this way :

      - type: bind
        source: ./source_local_directory
        target: c:\target_directory
        bind:
            propagation: cached


for Linux :
        -  ../angular/Angular-Material-Showroom/dist/angular-material-sandbox01:/usr/share/nginx/html:ro