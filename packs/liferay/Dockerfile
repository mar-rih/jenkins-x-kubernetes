FROM marrih/naseejmedad:k8s

LABEL Marwan Alrihawi <marwan.alrihawi@naseej.com>

RUN ln -s /opt/liferay-portal-6.2-ce-ga6 /opt/liferay-portal

ENV LIFERAY_PATH_DIR=/opt/liferay-portal

WORKDIR /opt/liferay-portal/deploy

ADD portal-setup-wizard.properties /opt/portal-setup-wizard.properties