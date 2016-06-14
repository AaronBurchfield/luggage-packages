include /usr/local/share/luggage/luggage.make

TITLE=Apple\ Setup\ Done
REVERSE_DOMAIN=com.github.AaronBurchfield.applesetupdone
PAYLOAD=pack-apple-setup-done

pack-apple-setup-done: l_var_db l_Library_Receipts
	@sudo touch ${WORK_D}/Library/Receipts/.SetupRegComplete
	@sudo touch ${WORK_D}/private/var/db/.AppleSetupDone
	@sudo chown root:admin ${WORK_D}/Library/Receipts/.SetupRegComplete
	@sudo chown root:wheel ${WORK_D}/private/var/db/.AppleSetupDone
