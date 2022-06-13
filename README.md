# Index of Organism Names (ION) as linked data

Generate a version of Index of Organism Names’s data as N-triples for import into a triple store.

## Index of Organism Names (ION)

The [Index of Organism Names](http://www.organismnames.com) contains the organism names related data gathered from the scientific literature for Clarivate Analytics' Zoological Record® database.

Each name in ION has a Life Science Identifier (LSID) which has an associated set of metadata in RDF/XML. This repository takes the XML for each ION name and reformats it as N-triples, correcting any minor format issues as part of that process. The resulting N-triples are intended to be uploaded into a triple store.

## License

The code in this repository is under a MIT license.