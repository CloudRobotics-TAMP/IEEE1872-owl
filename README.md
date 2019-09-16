# IEEE1872-owl

IEEE1872-owl is an OWL specification of the Core Ontology for Robotics and Automation (CORA) and other ontologies in IEEE 1872-2015 standard.

# Included ontologies

We modularized the ontologies in different levels of axiomatization. The ontologies are:

* cora-bare.owl: A standalone taxonomy of the concepts and properties in CORA, without links to SUMO or CORAX.
* sumo-cora.owl: The taxonomy of concepts of SUMO used in the remaining ontologies.
* cora.owl: It is cora-base linked to sumo-cora, rparts and corax. This is the recommended implementation in this library.
* cora-fullaxiom.owl: A version of cora.owl + pos.owl with the result of our best effort to translate SUO-KIF axioms in SUMO and IEEE 1872-2015 to OWL. Use this implementation with care. 
* rtask.owl: A version of cora-fullaxiom.owl + cap.owl + task.owl + action.owl. 
* corax.owl: The OWL implementation of CORAX.
* rparts.owl: The OWL implementation of RPARTS.
* pos.owl: The OWL implementation of POS.
* cap.owl: The OWL implementation of CAPABILITY.
* task.owl: The OWL implementation of TASK.
* action.owl: The OWL implementation of ACTION.
* annotation.owl: Some annotation properties for the ontologies in this project.

# Access

All ontologies can be accessed through the "http://purl.org/ieee1872-owl" prefix:

* http://purl.org/ieee1872-owl/cora-bare
* http://purl.org/ieee1872-owl/sumo-cora
* http://purl.org/ieee1872-owl/cora
* http://purl.org/ieee1872-owl/cora-fullaxiom
* http://purl.org/ieee1872-owl/rtask
* http://purl.org/ieee1872-owl/corax
* http://purl.org/ieee1872-owl/rparts
* http://purl.org/ieee1872-owl/pos
* http://purl.org/ieee1872-owl/cap
* http://purl.org/ieee1872-owl/task
* http://purl.org/ieee1872-owl/action
* http://purl.org/ieee1872-owl/annotation


# Bibliography

* E. Tosello, L. Tagliapietra, Z. Fan, A. Gatto Castro, E. Pagello. "RTASK: A Cloudbased Knwoledge Engine for Robot Task and Motion Planning". Fields of Robotics, Journal of. 2018. 

