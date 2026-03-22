ARG BUILD_ARCH
FROM homeassistant/${BUILD_ARCH}-addon-otbr:2.16.5

# Replace the broken migration script with our fixed version
COPY rootfs/usr/local/bin/migrate_otbr_settings.py /usr/local/bin/migrate_otbr_settings.py
RUN chmod +x /usr/local/bin/migrate_otbr_settings.py
