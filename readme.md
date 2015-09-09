# IRT EBU-TT-D Application Samples

The IRT-EBU-TT-D Application Samples are published to support early EBU-TT-D implementation by service  developers.

The intention is to facilitate collaboration and discussion about EBU-TT-D presentation. Specifically, the samples intend to foster application developments.

At time of publication the adoption of the EBU-TT-D format just started. Therefore the samples may change based on comments and feedback by other parties.

The published samples are not thought as normative reference but they may be used by any other organization as help to build reference material.

##License
The IRT EBU-TT-D Application Samples offered by Institut fuer Rundfunktechnik on GitHub are subject to the [Apache 2.0 license] (LICENSE). 


## Folder Structure

The folder structure is organized as follows:

### ttml
  * Contains the EBU-TT-D XML files. 
  * Most of the subtitles in the samples are activated from 10-20s and from 22-30s because they are customized for the sample videos. 

### png
  * Contains images that show the expected rendering of the EBU-TT-D sample.
  * Note that some "borders" just visualize the extent of certain rendering components such as regions and p elements.
  * The images are rendered with XSL-FO. XSL-FO is referenced from TTML for styling and layout. 


### video
  * Contains a 30s long mp4 video with the rendered png as still.
  * The structure of the video is as follows:
    * Title Page
    * Short Info
    * Display of the image how the subtitles should be rendered
    * Blank screen (only the rendered EBU-TT-D subtitles should be shown)
    * 2x times changing blank screen and pre-rendered subtitles to double confirm observations.

## Pattern of the file name

    [use case][three digits for use cae sample number][artefact type].[file extension]

Example for an EBU-TT-D sample XML to demonstrate rendering of text alignment with the value start:

    textalign-start-001-ttml.xml  

Example for an EBU-TT-D sample image to demonstrate rendering of the text alignment with the value start:

    textalign-start-001-image.png
    
##AUTHORS
Andreas Tai, Peter tho Pesch

## Acknowledgement
Parts of the IRT EBU-TT-D Application Samples were developed in the European collaborative research project HBB4ALL  (Grant Agreement no 621014). This project has received funding from the European Union ICT Policy Support Programme (ICT PSP) under the Competitiveness and Innovation Framework Programme (CIP). 
