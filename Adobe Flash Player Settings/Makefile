include /usr/local/share/luggage/luggage.make

TITLE=Adobe\ Flash\ Player\ Settings
REVERSE_DOMAIN=com.github.aaronburchfield.flashsettings
PACKAGE_VERSION=1.0
PAYLOAD=adobe_flash_settings

adobe_flash_settings: l_Library_Application_Support
	@sudo mkdir -p ${WORK_D}/Library/Application\ Support/Macromedia
	@sudo chmod -R 755 ${WORK_D}/Library/Application\ Support/Macromedia

	@sudo echo "AutoUpdateDisable=0" >> ${WORK_D}/Library/Application\ Support/Macromedia/mms.cfg
	@sudo echo "SilentAutoUpdateEnable=1" >> ${WORK_D}/Library/Application\ Support/Macromedia/mms.cfg
	@sudo chmod 755 ${WORK_D}/Library/Application\ Support/Macromedia/mms.cfg
