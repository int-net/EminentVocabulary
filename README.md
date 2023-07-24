# EminentVocabulary
Terminology and definitions used for the int:net Interoperability Model (EMINENT)

eminentVocab.ttl is the skos vocabulary

exceltoskos.json contains the transformation rules for the [cellfie](https://github.com/protegeproject/cellfie-plugin/) extension to [protege](https://protege.stanford.edu/) that allows you to transform an excel file with the structure of Definitions.xlsx to a (rather minimal) skos vocabulary.

BEWARE: at this stage, the protege import function will genereate its own uri's, so please ONLY import excel files that contain new entries. If you wish to edit existing concepts, please do so directly in the ttl file (using a text editor, protege or any other linked data editing tool)