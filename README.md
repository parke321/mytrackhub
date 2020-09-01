# My Personal Track Hub
SNP genotype data (generated by AncestryDNA) tracks for UCSC Genome Browser

Use https://raw.githubusercontent.com/parke321/mytrackhub/master/hub.txt in the UCSC Track Data Hub https://genome.ucsc.edu/cgi-bin/hgHubConnect to see this material.


    mytrackhub/ 		- directory containing track hub files
		hub.txt 	-  a short description of hub properties
		genomes.txt 	- list of genome assemblies included in the hub data
		hg19/ 		- directory of data for the hg19 (GRCh37) human assembly
			trackDb.txt 	- display properties for tracks in this directory
			dnase.html 	- description text for a DNase track 
			dnaseLiver.bigWig - wiggle plot of DNase in liver
			dnaseLiver.bigBed - regions of active DNase
        	dnaseLung.bigWig 	- wiggle plot of DNase in lung
        	dnaseLung.bigWig 	- regions of active DNase
