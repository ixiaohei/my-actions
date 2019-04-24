FROM openjdk:8-jdk-alpine

LABEL "maintainer"="Huan Zhang<tobecodingmaster@gmail.com>"
LABEL "repository"="https://github.com/ixiaohei/my-actions"
LABEL "homepage"="http://github.com/ixiaohei/my-actions"
LABEL "version"="1.0.0"

LABEL "com.github.actions.name"="Execute Gradle task"
LABEL "com.github.actions.description"="Executes single Gradle task"
LABEL "com.github.actions.icon"="play"
LABEL "com.github.actions.color"="green"

COPY "entrypoint.sh" "/entrypoint.sh"
ENTRYPOINT ["/entrypoint.sh"]
CMD ["check"]
