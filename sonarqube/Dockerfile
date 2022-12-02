FROM sonarqube:9.7.1-community
# Pluginのインストール
RUN set -x \
    && wget -O /opt/sonarqube/extensions/plugins/sonar-ldap-plugin-2.2.0.608.jar "https://binaries.sonarsource.com/?prefix=Distribution/sonar-ldap-plugin//sonar-ldap-plugin-2.2.0.608.jar"
# 設定ファイルを上書き
COPY sonar.properties /opt/sonarqube/conf/sonar.properties