FROM gutek/aspnet-core:update1-mono

ENV DNX_VERSION=1.0.0-rc1-final DNX_USER_HOME=/opt/dnx
RUN dnu commands install Microsoft.Dnx.Watcher $DNX_VERSION --packages $DNX_USER_HOME/bin

VOLUME /project

