It is a Heatmap with Top chart by D3.js tentatively used for showing the bandwidth usage of network ports with figures available from a TSV files.

Notes for customising for use in your site:

* a script may be required to generate the tsv file required. (The bandwidth data here was collected from the MRTG log files, and the description was collected from the equipment configuration files.)
* heatmapdata.tsv in tsv format with following columns:
 * device: the index for y-axis
 * port: the index for x-axis
 * incoming: incoming bandwidth usage of the port
 * outgoing: outgoing bandwidth usage of the port
 * timestamp: the timestamp for this bandwidth record
 * mrtg: the filename of the original MRTG log file
 * desc: a description of the port


Benjamin Ng @ 2017
