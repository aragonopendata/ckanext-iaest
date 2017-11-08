Clone for: https://github.com/ckan/ckanext-dcat.git#egg=ckanext-dcat

## Installation

1.  Install ckanext-harvest ([https://github.com/ckan/ckanext-harvest#installation](https://github.com/ckan/ckanext-harvest#installation)) (Only if you want to use the RDF harvester)

2. . /<CKAN_HOME>/bin/activate

3. cd <CKAN_HOME>/src

3.  Install the extension on your virtualenv:

        (pyenv) $ pip install -e git+https://github.com/aragonopendata/ckanext-iaest.git#egg=ckanext-iaest

4.  Install the extension requirements:

        (pyenv) $ pip install -r ckanext-iaest/requirements.txt

5.  Enable the required plugins in your ini file:

        ckan.plugins = iaest iaest_rdf_harvester

6. Enable Profile
	ckanext.dcat.rdf.profiles = euro_dcat_ap euro_dcat_ap_iaest 

7. Create user with username harvest