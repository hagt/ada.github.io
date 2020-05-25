## Film-Analytical Annotations

[![Image Advene](advene.png "Annotations in Advene")](advene.png)

Throughout the project, the FU Berlin project team created a very high quality data set of manual film-analytical annotations for a set of feature films, documentaries, and television news. These valuable annotations are published here as Linked Open Data under the CC BY-SA 3.0 license to make the data available to other film scientists as well as researchers from other domains.

### Annotation Creation

The annotations were created based on a film scholar's analytical framework ([eMAEX method](https://www.ada.cinepoetics.fu-berlin.de/en/Methoden/eMAEX/index.html)) to study the aesthetics of audio-visual images. The annotation work followed a strict annotation routine to precisely describe the films of the [corpus](../corpus) under different levels of description (see [ontology](../ontology)).

The annotation process is carried out with [Advene](https://www.advene.org/), a free software toolkit for annotating audio-visual documents. We worked closely with Olivier Aubert, the author of Advene, on the one hand to improve the user interface for faster annotation work, and on the other hand to enable the import of the AdA ontology and the export of W3C compliant video annotations as RDF data.

To create annotations that conform to the AdA ontology, you can use the [Advene template package](https://github.com/ProjectAdA/public/tree/master/advene_template) that we provide in our GitHub repository.

### Structure

The datasets created in the AdA project consist of thousands of annotations that use timecode-based references to the original video material. Each annotation refers to a fragment of a movie using start and end timecodes to which the annotation applies. The actual content of the annotation relates to the annotation types and values defined in the AdA ontology. Each annotation also contains metadata about the author and the creation date.

For example, the following information is available to characterize the camera movement at minute 41 of the feature film "The Company Men":

| Annotation ID | [ed63d084-717f-11e9-99b8-0242ac130003[(http://ada.filmontology.org/resource/media/294704ee3bd55a6888235ae7721120c29522eddd3cc273cc8365fa0eef2ac56d/ed63d084-717f-11e9-99b8-0242ac130003) |
| Begin timecode | 00:41:29 | 
| End  timecode | 00:41:50 | 
| Annotation Type | [Camera Movement Type](http://ada.filmontology.org/resource/2020/03/17/AnnotationType/CameraMovementType)|
| Annotation Value | [tracking shot](http://ada.filmontology.org/resource/2020/03/17/AnnotationValue/CameraMovementType_tracking_shot)|
| Author | anton |
| Date | 2018-05-04 22:10:22 |

### Encoding



[comment]: <> (Scene Segmentation)


