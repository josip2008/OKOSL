OUTPUTS := ./00_opis_vjestine/00_opis_vjestine.pdf
OUTPUTS += ./01_uvod/01_uvodno_predavanje.pdf
OUTPUTS += ./01_uvod/zzv_1.pdf
OUTPUTS += ./02_datoteke_direktoriji/02_rad_s_datotekama_i_direktorijima.pdf
OUTPUTS += ./02_datoteke_direktoriji/zzv_2.pdf
OUTPUTS += ./03_pretrazivanja_filtri_cjevovodi/03_pretrazivanja_filtri_cjevovodi.pdf
OUTPUTS += ./03_pretrazivanja_filtri_cjevovodi/zzv_3.pdf
OUTPUTS += ./04_varijable_kontrola_toka_zamjenski_znakovi/04_varijable_kontrola_toka_zamjenski_znakovi.pdf
OUTPUTS += ./04_varijable_kontrola_toka_zamjenski_znakovi/zzv_4.pdf
OUTPUTS += ./05_regex/05_regex.pdf
OUTPUTS += ./05_regex/zzv_5.pdf
OUTPUTS += ./06_korisnici_grupe/06_korisnici_i_grupe.pdf
OUTPUTS += ./07_procesi/07_procesi.pdf
OUTPUTS += ./07_procesi/zzv_7.pdf
OUTPUTS += ./08_linux_u_praksi/08_linux_u_praksi.pdf

all: $(OUTPUTS)

$(OUTPUTS): %.pdf: %.tex
	cd $(dir $<D) && pdflatex $(notdir $<) && pdflatex $(notdir $<)

.PHONY: all
