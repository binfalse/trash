
all: unchange.zip sedml-change.zip

unchange.zip: unchanged/model/calzone_thieffry_tyson_novak_2007.cellml unchanged/manifest.xml unchanged/experiment/Calzone2007-simulation-figure-1B-cellml.xml
	cd unchanged && zip -r ../unchange.zip * 

sedml-change.zip: sedml-change/model/calzone_thieffry_tyson_novak_2007.cellml sedml-change/manifest.xml sedml-change/experiment/Calzone2007-simulation-figure-1B-cellml.xml
	cd sedml-change && zip -r ../sedml-change.zip *

clean:
	rm -f unchange.zip sedml-change.zip

