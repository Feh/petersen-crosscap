all:    crosscap-construction.pdf \
        crosscap-embedding-1.pdf \
        crosscap-embedding-2.pdf \
        crosscap-embedding-3.pdf \
        crosscap-embedding-4.pdf \
        crosscap-embedding-5-black.pdf \
        crosscap-embedding-5.pdf \
        petersen-edge-fourcoloring.pdf \
        petersen-grundlage.pdf \
        petersen-vertex-threecoloring.pdf \
        petersen-zweikreuzungen.pdf \

%.eps: %.dia
	dia "$<" -e "$@"

%.pdf: %.eps
	epstopdf "$<"
