DCETOP = $(LW_BASE_PATH)
DCEIDL = $(LW_BASE_PATH)/bin/dceidl
IDL_INCLUDE_DIR = $(DCETOP)/include
IDLFLAGS = -I$(IDL_INCLUDE_DIR) -keep c_source

idl_srcdir=$(top_srcdir)/idl

CLEANFILES = \
    demo_h.h \
    demo_cstub.c \
    demo_sstub.c \
    demo_privsep_h.h \
    demo_privsep_cstub.c \
    demo_privsep_sstub.c \
    fwmgmt_h.h \
    fwmgmt_cstub.c \
    fwmgmt_sstub.c \
    pkgmgmt_h.h \
    pkgmgmt_cstub.c \
    pkgmgmt_sstub.c \
    pmd_h.h \
    pmd_cstub.c \
    pmd_sstub.c \
    netmgmt_h.h \
    netmgmt_cstub.c \
    netmgmt_sstub.c \
    usermgmt_h.h \
    usermgmt_cstub.c \
    usermgmt_sstub.c \
    privsepd_h.h \
    privsepd_cstub.c \
    privsepd_sstub.c \
    pkgmgmt_privsep_h.h \
    pkgmgmt_privsep_cstub.c \
    pkgmgmt_privsep_sstub.c \
    netmgmt_privsep_h.h \
    netmgmt_privsep_cstub.c \
    netmgmt_privsep_sstub.c \
    fwmgmt_privsep_h.h \
    fwmgmt_privsep_cstub.c \
    fwmgmt_privsep_sstub.c \
    usermgmt_privsep_h.h \
    usermgmt_privsep_cstub.c \
    usermgmt_privsep_sstub.c

BUILT_SOURCES = demo_h.h \
                demo_privsep_h.h \
                fwmgmt_h.h \
                pkgmgmt_h.h \
                pmd_h.h \
                netmgmt_h.h \
                usermgmt_h.h \
                privsepd_h.h \
                pkgmgmt_privsep_h.h \
                netmgmt_privsep_h.h \
                fwmgmt_privsep_h.h \
                usermgmt_privsep_h.h

demo_h.h demo_cstub.c: $(idl_srcdir)/demo.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header demo_h.h -I$(idl_srcdir) $<
demo_privsep_h.h demo_privsep_cstub.c: $(idl_srcdir)/demo_privsep.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header demo_privsep_h.h -I$(idl_srcdir) $<
fwmgmt_h.h fwmgmt_cstub.c: $(idl_srcdir)/fwmgmt.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header fwmgmt_h.h -I$(idl_srcdir) $<
pkgmgmt_h.h pkgmgmt_cstub.c: $(idl_srcdir)/pkgmgmt.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header pkgmgmt_h.h -I$(idl_srcdir) $<
pmd_h.h pmd_cstub.c: $(idl_srcdir)/pmd.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header pmd_h.h -I$(idl_srcdir) $<
netmgmt_h.h netmgmt_cstub.c: $(idl_srcdir)/netmgmt.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header netmgmt_h.h -I$(idl_srcdir) $<
usermgmt_h.h usermgmt_cstub.c: $(idl_srcdir)/usermgmt.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header usermgmt_h.h -I$(idl_srcdir) $<

privsepd_h.h privsepd_cstub.c: $(idl_srcdir)/privsepd.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header privsepd_h.h -I$(idl_srcdir) $<
pkgmgmt_privsep_h.h pkgmgmt_privsep_cstub.c: $(idl_srcdir)/pkgmgmt_privsep.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header pkgmgmt_privsep_h.h -I$(idl_srcdir) $<
netmgmt_privsep_h.h netmgmt_privsep_cstub.c: $(idl_srcdir)/netmgmt_privsep.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header netmgmt_privsep_h.h -I$(idl_srcdir) $<
fwmgmt_privsep_h.h fwmgmt_privsep_cstub.c: $(idl_srcdir)/fwmgmt_privsep.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header fwmgmt_privsep_h.h -I$(idl_srcdir) $<
usermgmt_privsep_h.h usermgmt_privsep_cstub.c: $(idl_srcdir)/usermgmt_privsep.idl
	$(DCEIDL) $(IDLFLAGS) -keep c_source -header usermgmt_privsep_h.h -I$(idl_srcdir) $<
