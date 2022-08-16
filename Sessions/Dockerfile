# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM jamesmortensen1/base:4.4.0-20220816
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium SessionMap Configuration
#========================

EXPOSE 5556

COPY start-selenium-grid-sessions.sh \
    /opt/bin/

COPY selenium-grid-sessions.conf /etc/supervisor/conf.d/
