FROM marrih/naseejmedad:k8s

LABEL Marwan Alrihawi <marwan.alrihawi@naseej.com>

RUN ln -s /opt/liferay-portal-6.2-ce-ga6 /opt/liferay-portal

ENV LIFERAY_PATH_DIR=/opt/liferay-portal

ADD deploy/* $LIFERAY_PATH_DIR/deploy-tmp/
ADD portal-setup-wizard.properties /opt/portal-setup-wizard.properties
WORKDIR /opt/liferay-portal/deploy
