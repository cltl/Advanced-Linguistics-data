### Advanced-linguistics-data
This repository contains annotated data from the Dutch FrameNet annotation tool. It is structured as follows:

* **Exploring_data_structure.ipynb** is a notebook you can run to learn about the structure of the dataset and to start playing around with it.
* **MH17** contains a subfolder called **annotated_data**, which contains the annotations per reference text in a json folder, and a json folder called **structured_data.json**, which maps wikidata identifiers to labels. The raw data is in English.
* **Utrecht_shooting** is structured the same way as MH17. The raw data is in Dutch. Only this data contains compound information.
* **typical_frames** contains the typicality scores for the event type "mass shooting". The json file contains the frame:score pairs unordered. The excel sheet shows the frames ranked and contrasted with frames of other event types. MH17 belongs to the event type "aircraft shootdown", but almost completely overlaps with "mass shooting" conceptually, so we assume that it can be applied to that event type as well.

## Remarks

* In the MH17 corpus, the title of the text is part of the raw layer but unannotated. You don't have to pay attention to it.
* The reftype annotations are of poor quality, so don't use them.
* Not all predicates in the reference texts are annotated. The annotators only paid attention to the predicates that are relevant in reconstructing the full narrative surrounding the main event. So this is deliberate.

### Authors
* **Levi Remijnse** (l.remijnse@vu.nl)

### License
This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
