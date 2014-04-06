all:    crosscap-construction.pdf \
        crosscap-embedding-print.pdf \
        crosscap-embedding-01.pdf \
        crosscap-embedding-02.pdf \
        crosscap-embedding-03.pdf \
        crosscap-embedding-04.pdf \
        crosscap-embedding-05.pdf \
        crosscap-embedding-06.pdf \
        crosscap-embedding-07.pdf \
        crosscap-embedding-08.pdf \
        crosscap-embedding-09.pdf \
        crosscap-embedding-10.pdf \
        crosscap-embedding-11.pdf \
        petersen-edge-fourcoloring.pdf \
        petersen-grundlage.pdf \
        petersen-vertex-threecoloring.pdf \
        petersen-zweikreuzungen.pdf \

%.eps: %.dia
	dia "$<" -e "$@"

%.pdf: %.eps
	epstopdf "$<"
