bin_PROGRAMS = tnt

tnt_SOURCES = \
	Bid.vala \
	Card.vala \
	Colour.vala \
	Game.vala \
	GraphicalCard.vala \
	GraphicalHand.vala \
	GraphicalPlayer.vala \
	Hand.vala \
	IAPlayer.vala \
	Player.vala \
	Scores.vala \
	Tnt.vala \
	About.vala \
	SynthethicScore.vala

INCLUDES = \
	-include config.h \
	$(TNT_CFLAGS) \
	-DLOCALEDIR=\""$(localedir)"\" \
	-DPKGDATADIR=\""$(pkgdatadir)"\" \
	-DPKGLIBDIR=\""$(pkglibdir)"\" \
	-DDATADIR=\""$(datadir)"\" 

VALAFLAGS = \
	-g --vapidir=$(srcdir)/../vapi --pkg config \
	@TNT_PACKAGES@

tnt_LDADD = \
	$(TNT_LIBS)
