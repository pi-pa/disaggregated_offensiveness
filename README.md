# A Disaggregated Dataset on English Offensiveness Containing Spans

This is the data for the paper [A Disaggregated Dataset on English Offensiveness Containing Spans](https://aclanthology.org/2025.nlperspectives-1.1/). 


## Dataset description

#### Index
The index in the Jigsaw Toxic Comment Classification Challenge, the source of the data

#### Comment
The text from the Jigsaw Toxic Comment Classification Challenge which was classified

#### Annotators not toxic
The annotator ids of the annotators who labelled the text as not toxic / not offensive 

#### Annotators insult
The annotator ids of the annotators who labelled the text to be an insult

#### Annotators hate
The annotator ids of the annotators who labelled the text to be hateful

#### Tags
The spans, the label of the spans and the annotators that annotated these spans

#### Jigsaw annotations
For comparison, we include the annotations from the original Toxic Comment Classification Challenge

#### Label
Denotes whether the aggregated label is Toxic / Offensive (1) or Not toxic / Not offensive (0)

#### Vulgar
Denotes whether the aggregated annotations contain a span labelled as vulgar (1) or not (0). We did not use this label for our evaluation.

#### Target group / Target individual / Target other
Denotes whether the aggregated annotations contain a span labelled as target_group / target_individual / target_other (1) or not (0). We did not use this label for our evaluation.

#### Tags
The spans and the labels of the spans. 

### Tags_agg
The spans and labels in the aggregated dataset.



## Citation

If you use this dataset, please cite us: 

```json
@inproceedings{pachinger-etal-2025-disaggregated,
    title = "A Disaggregated Dataset on {E}nglish Offensiveness Containing Spans",
    author = "Pachinger, Pia  and
      Goldzycher, Janis  and
      Planitzer, Anna M.  and
      Neidhardt, Julia  and
      Hanbury, Allan",
    editor = "Abercrombie, Gavin  and
      Basile, Valerio  and
      Frenda, Simona  and
      Tonelli, Sara  and
      Dudy, Shiran",
    booktitle = "Proceedings of the The 4th Workshop on Perspectivist Approaches to NLP",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.nlperspectives-1.1/",
    doi = "10.18653/v1/2025.nlperspectives-1.1",
    pages = "1--14",
    ISBN = "979-8-89176-350-0",
    abstract = "Toxicity labels at sub-document granularity and disaggregated labels lead to more nuanced and personalized toxicity classification and facilitate analysis. We re-annotate a subset of 1983 posts of the Jigsaw Toxic Comment Classification Challenge and provide disaggregated toxicity labels and spans that identify inappropriate language and targets of toxic statements. Manual analysis shows that five annotations per instance effectively capture meaningful disagreement patterns and allow for finer distinctions between genuine disagreement and that arising from annotation error or inconsistency. Our main findings are: (1) Disagreement often stems from divergent interpretations of edge-case toxicity (2) Disagreement is especially high in cases of toxic statements involving non-human targets (3) Disagreement on whether a passage consists of inappropriate language occurs not only on inherently questionable terms, but also on words that may be inappropriate in specific contexts while remaining acceptable in others (4) Transformer-based models effectively learn from aggregated data that reduces false negative classifications by being more sensitive towards minority opinions for posts to be toxic. We publish the new annotations under the CC BY 4.0 license."
}
```

# A Disaggregated Dataset on English Offensiveness Containing Spans

This is the data for the paper [A Disaggregated Dataset on English Offensiveness Containing Spans](https://aclanthology.org/2025.nlperspectives-1.1/). 


## Dataset description

#### Index
The index in the Jigsaw Toxic Comment Classification Challenge, the source of the data

#### Comment
The text from the Jigsaw Toxic Comment Classification Challenge which was classified

#### Annotators not toxic
The annotator ids of the annotators who labelled the text as not toxic / not offensive 

#### Annotators insult
The annotator ids of the annotators who labelled the text to be an insult

#### Annotators hate
The annotator ids of the annotators who labelled the text to be hateful

#### Tags
The spans, the label of the spans and the annotators that annotated these spans

#### Jigsaw annotations
For comparison, we include the annotations from the original Toxic Comment Classification Challenge

#### Label
Denotes whether the aggregated label is Toxic / Offensive (1) or Not toxic / Not offensive (0)

#### Vulgar
Denotes whether the aggregated annotations contain a span labelled as vulgar (1) or not (0). We did not use this label for our evaluation.

#### Target group / Target individual / Target other
Denotes whether the aggregated annotations contain a span labelled as target_group / target_individual / target_other (1) or not (0). We did not use this label for our evaluation.

#### Tags
The spans and the labels of the spans. 

### Tags_agg
The spans and labels in the aggregated dataset.



## Citation

If you use this dataset, please cite us: 

```json
@inproceedings{pachinger-etal-2025-disaggregated,
    title = "A Disaggregated Dataset on {E}nglish Offensiveness Containing Spans",
    author = "Pachinger, Pia  and
      Goldzycher, Janis  and
      Planitzer, Anna M.  and
      Neidhardt, Julia  and
      Hanbury, Allan",
    editor = "Abercrombie, Gavin  and
      Basile, Valerio  and
      Frenda, Simona  and
      Tonelli, Sara  and
      Dudy, Shiran",
    booktitle = "Proceedings of the The 4th Workshop on Perspectivist Approaches to NLP",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.nlperspectives-1.1/",
    doi = "10.18653/v1/2025.nlperspectives-1.1",
    pages = "1--14",
    ISBN = "979-8-89176-350-0",
    abstract = "Toxicity labels at sub-document granularity and disaggregated labels lead to more nuanced and personalized toxicity classification and facilitate analysis. We re-annotate a subset of 1983 posts of the Jigsaw Toxic Comment Classification Challenge and provide disaggregated toxicity labels and spans that identify inappropriate language and targets of toxic statements. Manual analysis shows that five annotations per instance effectively capture meaningful disagreement patterns and allow for finer distinctions between genuine disagreement and that arising from annotation error or inconsistency. Our main findings are: (1) Disagreement often stems from divergent interpretations of edge-case toxicity (2) Disagreement is especially high in cases of toxic statements involving non-human targets (3) Disagreement on whether a passage consists of inappropriate language occurs not only on inherently questionable terms, but also on words that may be inappropriate in specific contexts while remaining acceptable in others (4) Transformer-based models effectively learn from aggregated data that reduces false negative classifications by being more sensitive towards minority opinions for posts to be toxic. We publish the new annotations under the CC BY 4.0 license."
}
```





