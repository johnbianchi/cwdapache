lib_LTLIBRARIES = mod_authz_svn_crowd.la
mod_authz_svn_crowd_la_SOURCES = mod_authz_svn_crowd.c
mod_authz_svn_crowd_la_LDFLAGS = -module
AM_CFLAGS = `apr-1-config --cflags`
AM_CPPFLAGS = -I@APACHE_INCLUDE_DIR@ `apr-1-config --cppflags --includes` -I@SVN_DIR@/include/subversion-1
CFLAGS=-g -O1   # -O2 causes mysterious crashes
