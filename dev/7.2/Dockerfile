FROM chialab/php:7.2
LABEL maintainer="dev@chialab.io"

# Install XDebug.
RUN install-php-extensions xdebug \
    && echo "zend_extension=\"$(php-config --extension-dir)/xdebug.so\"" > $PHP_INI_DIR/conf.d/xdebug.ini
