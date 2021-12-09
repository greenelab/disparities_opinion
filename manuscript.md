---
title: Computational audits combat disparities in recognition
keywords:
- opinion
- equity
- Computational audits
lang: en-US
date-meta: '2021-12-09'
author-meta:
- Ariel A. Hippen*
- Natalie R. Davidson*
- Casey S. Greene
- \* *denotes co-first authorship. Order determined by simultaneous rolls of d20s over a video call.*
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Computational audits combat disparities in recognition" />
  <meta name="citation_title" content="Computational audits combat disparities in recognition" />
  <meta property="og:title" content="Computational audits combat disparities in recognition" />
  <meta property="twitter:title" content="Computational audits combat disparities in recognition" />
  <meta name="dc.date" content="2021-12-09" />
  <meta name="citation_publication_date" content="2021-12-09" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Ariel A. Hippen*" />
  <meta name="citation_author_institution" content="Perelman School of Medicine, University of Pennsylvania, 3400 Civic Center Boulevard, Philadelphia, PA 19104" />
  <meta name="citation_author_orcid" content="0000-0001-9336-6543" />
  <meta name="citation_author" content="Natalie R. Davidson*" />
  <meta name="citation_author_institution" content="University of Colorado Anschutz Medical Campus, Center for Health Artificial Intelligence, 1890 N Revere Ct. Aurora, CO 80045, USA" />
  <meta name="citation_author_orcid" content="0000-0002-1745-8072" />
  <meta name="citation_author" content="Casey S. Greene" />
  <meta name="citation_author_institution" content="University of Colorado Anschutz Medical Campus, Center for Health Artificial Intelligence, 1890 N Revere Ct. Aurora, CO 80045, USA" />
  <meta name="citation_author_orcid" content="0000-0001-8713-9213" />
  <meta name="citation_author" content="\* *denotes co-first authorship. Order determined by simultaneous rolls of d20s over a video call.*" />
  <link rel="canonical" href="https://greenelab.github.io/disparities_opinion/" />
  <meta property="og:url" content="https://greenelab.github.io/disparities_opinion/" />
  <meta property="twitter:url" content="https://greenelab.github.io/disparities_opinion/" />
  <meta name="citation_fulltext_html_url" content="https://greenelab.github.io/disparities_opinion/" />
  <meta name="citation_pdf_url" content="https://greenelab.github.io/disparities_opinion/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://greenelab.github.io/disparities_opinion/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://greenelab.github.io/disparities_opinion/v/b7f94c9c5fe95d596c8bea77489a656aaff90594/" />
  <meta name="manubot_html_url_versioned" content="https://greenelab.github.io/disparities_opinion/v/b7f94c9c5fe95d596c8bea77489a656aaff90594/" />
  <meta name="manubot_pdf_url_versioned" content="https://greenelab.github.io/disparities_opinion/v/b7f94c9c5fe95d596c8bea77489a656aaff90594/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://greenelab.github.io/disparities_opinion/v/b7f94c9c5fe95d596c8bea77489a656aaff90594/))
was automatically generated
from [greenelab/disparities_opinion@b7f94c9](https://github.com/greenelab/disparities_opinion/tree/b7f94c9c5fe95d596c8bea77489a656aaff90594)
on December 9, 2021.
</em></small>

## Authors



+ **Ariel A. Hippen***<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-9336-6543](https://orcid.org/0000-0001-9336-6543)<br>
  <small>
     Perelman School of Medicine, University of Pennsylvania, 3400 Civic Center Boulevard, Philadelphia, PA 19104
  </small>

+ **Natalie R. Davidson***<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-1745-8072](https://orcid.org/0000-0002-1745-8072)<br>
  <small>
     University of Colorado Anschutz Medical Campus, Center for Health Artificial Intelligence, 1890 N Revere Ct. Aurora, CO 80045, USA
  </small>

+ **Casey S. Greene**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-8713-9213](https://orcid.org/0000-0001-8713-9213)<br>
  <small>
     University of Colorado Anschutz Medical Campus, Center for Health Artificial Intelligence, 1890 N Revere Ct. Aurora, CO 80045, USA
  </small>

+ **\* *denotes co-first authorship. Order determined by simultaneous rolls of d20s over a video call.***<br><br>
  <small>
  </small>



To the editor-

Recognition by peers and the general public can greatly affect the trajectory of a scientist’s career.
  Any recognition--inclusion of one’s name in print as an expert, an invited lecture, or an award--paves the way to future accolades.
  Regardless of an individual’s merit, biases can skew which scientists are recognized.
  This is exemplified in a recent study of disparities in scientific journalism, which found that individuals with names that are predicted to be of East Asian origin were under-quoted and under-mentioned [@doi:10.1101/2021.06.21.449261].
  Regular monitoring of recognition practices can combat this by identifying overlooked groups and creating opportunities to hold the recognizing body accountable.

Auditing efforts can help reduce disparities.
  For instance, several journalists found that self-audits of gender-based representation in their articles helped them approach parity [@https://www.theatlantic.com/technology/archive/2016/02/gender-diversity-journalism/463023; @https://www.theatlantic.com/science/archive/2018/02/i-spent-two-years-trying-to-fix-the-gender-imbalance-in-my-stories/552404].
  In award recognition, an audit of the International Society for Computational Biology (ISCB) honorees revealed significant under-representation of people with predicted East Asian name origins and over-representation of US-affiliated scientists.
  After this study was publicized, ISCB's following honorees had the highest mean predicted probability of having an East Asian name of any previous year, and the nominating committee inducted their first China-based ISCB Fellow [@doi:10.1016/j.cels.2021.07.007].

Ideally, audits of representation would only use self-reported gender, ethnicity, and other identifications [@doi:10.1371/journal.pcbi.1003903].
  While this may be possible prospectively, surveying is impractical for large groups and often impossible retrospectively [@http://mediashift.org/2014/11/how-to-ethically-and-responsibly-identify-gender-in-large-datasets].
  In contrast, computationally-derived predictions allow for large-scale audits with as broad a scope as needed.
  Numerous tools exist to algorithmically infer gender, nationality, and ethnicity using the feature most likely to be present in datasets: an individual's name [@doi:10.1093/pan/mpw001; @http://genderize.io].

Prediction models are not a panacea, however; several factors limit both their accuracy at recapitulating self-reported information and their ability to address the underlying motivating questions of diversity audits.
  For instance, gender associations of a given name can vary by culture, potentially biasing gender predictions where additional information is not available [@https://aclanthology.org/U14-1021].
  Also, most gender prediction models are trained on binary gender labels, the use of which systematically overlooks and conceptually erases the representation and contributions of transgender, non-binary, and intersex individuals [@doi:10.1101/2020.10.12.336230].

Proxy predictions of ethnicity via name origin are more difficult still; choosing categories to probabilistically predict on is non-trivial and difficult to discretize.
  Furthermore, there is no one-to-one mapping between having a name from a linguistic group and belonging to a minoritized or underrepresented group.
  Colonialism, immigration, and structural racism have affected both linguistic histories and inclusion or exclusion from scientific communities in complex ways that are nearly impossible to parse from names alone.
  For instance, classifiers are usually unable to distinguish if names of Hispanic origin come from the Iberian Peninsula or from Latin America [@doi:10.1016/j.cels.2021.07.007].
  If a target and background population had identical probabilistic proportions of Hispanic names, but the target group primarily consisted of Iberian individuals, underrepresentation of Latin American scientists would go unnoticed in an exclusively name-based analysis.

Beyond accurate classification of individuals' social identifiers, auditing systems also require a comparable background distribution.
  For example, in order to identify disparities in ISCB honorees, Le et al. [@doi:10.1016/j.cels.2021.07.007] used scientists' publication records to approximate the expected diversity of potential honorees.
  While seemingly straightforward, there exist many choices on how to calculate publication rates. 
  The authors had to decide which journals would be included in their publication record, whether the publications should be weighted by citation count, and if authorship position should be considered.
  Choosing the most appropriate reference distribution will be specific to the application, but the selection criteria of the background distribution should be annotated and justified.

Recognizing the aforementioned shortcomings, we propose the following recommendations for the creation and deployment of automated auditing tools:

  1. *Transparency.* Publicly provide all results, tools, code, and data used in the analysis.
  This gives those whose data was used in the analysis, as well as the general public, the chance to scrutinize the methods used and be informed of any biases found by the audit.
  For confidential data, de-identified or aggregated data should be provided.

  2. *Individuals know best.* Self-identified demographic information should always be used in preference to algorithmic predictions.

  3. *Aggregates only.* Audit results should not affect individuals.
  The gender and ethnicity of an individual are not for an algorithm to decide nor are they the focus of an audit.
  Analyses must focus on aggregate estimations and any intermediary individual predictions should not be used externally.
  In addition, analysts must be mindful of hidden subpopulations that may be obscured during aggregation.

  4. *Inform the public.* While internal audits can help institutions reflect, researchers should inform the community of identified disparities.
  This should include a discussion of any caveats associated with the analyses performed (e.g., a binarization of gender) and the ethical implications of such choices.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
