.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. dpowcoin_qt test_dpowcoin_qt
clean: FORCE
	$(MAKE) -C .. dpowcoin_qt_clean test_dpowcoin_qt_clean
check: FORCE
	$(MAKE) -C .. test_dpowcoin_qt_check
dpowcoin-qt dpowcoin-qt.exe: FORCE
	 $(MAKE) -C .. dpowcoin_qt
apk: FORCE
	$(MAKE) -C .. dpowcoin_qt_apk
