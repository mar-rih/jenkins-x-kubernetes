FROM 558184000342.dkr.ecr.us-west-2.amazonaws.com/medad-dspace-base:latest

LABEL Marwan Alrihawi <marwan.alrihawi@naseej.com>

COPY /config.properties /usr/local/tomcat/webapps/MedadDspaceServices/WEB-INF/classes/config.properties
COPY /entrypoint.sh /dspace/bin/entrypoint.sh
RUN chmod 777 -R /dspace/bin/entrypoint.sh

# EXEC
CMD ["run"]
ENTRYPOINT ["/dspace/bin/entrypoint.sh"]
