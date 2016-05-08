# TTML2WebVTT Mapping Samples

The TTML2WebVTT mapping samples are part of the the [IRT EBU-TT-D Application Samples repository](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples). They apply the strategy defined in [Mapping Between TTML and WebVTT](http://w3c.github.io/ttml-webvtt-mapping) (W3C Editor's Draft 16 February 2016) to a selection of the EBU-TT-D samples. The samples are intended to support the verification of the strategies used in the Mapping document and also to test their applicability to current implementations.

As EBU-TT-D is a subset of TTML1 and IMSC1 the mappings are also examples for mappings from TTML1 to WebVTT and IMSC1 to WebVTT.

The structure of the EBU-TT-D Application Samples is explained in the [root of this project repository](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping). 

The WebVTT mapping part adds following folders:


## [css](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/css)
Part of the mapping from TTML to WebVTT  is the [creation of a CSS file](http://w3c.github.io/ttml-webvtt-mapping/#mapping-styling-information) that reflects the styling of the TTML document. The CSS files in this folder (as all other artefacts of the mapping samples) are named according to the same pattern [explained for the EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping#pattern-of-the-file-name). The CSS files are later linked from the [HTML pages](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/html).

## [html](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/html)
The HTML files combine WebVTT and CSS (as results of the mapping) with the video that shows the reference EBU-TT-D rendering. Because the WebVTT information should be semantically equivalent to the TTML source document, a WebVTT rendering should have the same result as the burnt-in reference rendering in the video. 

## [ttml](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/ttml)
The TTML documents are a selection of the EBU-TT-D samples and the source of the mapping. For convenience the files are copied from the [ttml folder in the project root](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/ttml) to the mapping folder.

## [tvtt](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/tvtt)
As first step of the mapping the guideline proposes to pre-process the source documents to a TTML form that is closer to the syntax and semantics of WebVTT (see also the [relevant section in the mapping document](http://w3c.github.io/ttml-webvtt-mapping/#pre-processing-converting-ttml-to-tvtt)). The pre-processing strategy is applied to the [selected EBU-TT-D samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/ttml). 

## [video](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/video)
Videos that correspond to the [selected TTML samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/ttml) are copied to this folder. To cover a broader range of clients additional encodings are provided.

## [webvtt](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/webvtt)
The last step in the mapping is to create WebVTT files from the [TTML source documents](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/tree/webvtt-mapping/webvtt-mapping/ttml). The WebVTT files are used as text track for in the corresponding HTML pages so that the result can visually be tested.

## Acknowledgement
Parts of the IRT EBU-TT-D Application Samples were developed in the European collaborative research project HBB4ALL  (Grant Agreement no 621014). This project has received funding from the European Union ICT Policy Support Programme (ICT PSP) under the Competitiveness and Innovation Framework Programme (CIP).