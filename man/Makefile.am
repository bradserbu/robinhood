dist_man_MANS=robinhood.1 rbh-report.1 rbh-find.1 rbh-du.1 rbh-diff.1

if LUSTRE_HSM
dist_man_MANS+=lhsmtool_cmd.1
endif

# Manually generate man pages from each executable --help
manpages:
	export VERSION=${VERSION}; ../scripts/make_mans.sh
