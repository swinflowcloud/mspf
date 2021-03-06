# Micro Service Plugin framework (Mspf)

Current version 0.1.2

This is an open-source plugin framework for python micro service in python. Developer can design and release their plugin in this framwork. This framework can be used as plugin market to support to manage numerous plugins.

Features:
<ul>
<li>(1) Supports standalone the django-based App plugins</li>
<li>(2) Supports to create, edit, remove the plugins</li>
<li>(3) Uploads and downloads a plugin for migration</li>
<li>(4) Supports online plugin development in python</li>
<li>(5) Supports online debugging python plugin (developing)</li>
</ul>
Deployment requirements:

This framework can run at Windows and Linux operation platform, the platform needs to install python environments.

for development environments: 

<ul>
<li>Python 3.9</li>
<li>Django-3.2.4:<br>
   pip install django</li>
<li>Watchdog 2.1.3:<br>
   pip install watchdog</li>
<li>Configparser-5.0.2:<br>
   pip install configparser</li>
<li>Python-socketio: <br>
   pip install python-socketio</li>
</ul>

for production environments, we need the following components.

<ul>
<li>Nginx</li>
<li>uwsgi</li>
</ul>

The depoyment guide is in the user manual.pdf

0.1.0
<ul>
<li>(1) released the basic version based on Django</li>
<li>(2) can support the python code editing</li>
</ul>

0.1.1
<ul>
<li>(1) fixed the code editor bugs</li>
<li>(2) completed the user mannual for development</li>
</ul>

0.1.2
<ul>
<li>(1) added the deployments for production environment</li>
<li>(2) designed the uwsgi.ini</li>
</ul>

