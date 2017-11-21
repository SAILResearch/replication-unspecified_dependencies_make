# Replication Package for "An Empirical Study of Unspecified Dependencies in Make-Based Build Systems"

Cor-Paul Bezemer, Shane McIntosh, Bram Adams, Daniel M. German and Ahmed E. Hassan  
[Empirical Software Engineering journal, vol. 22, issue 6, 2017](https://doi.org/10.1007/s10664-017-9510-8)

Abstract: Software developers rely on a build system to compile their source code changes and produce deliverables for testing and deployment. Since the full build of large software systems can take hours, the incremental build is a cornerstone of modern build systems. Incremental builds should only recompile deliverables whose dependencies have been changed by a developer. However, in many organizations, such dependencies still are identified by build rules that are specified and maintained (mostly) manually, typically using technologies like make. Incomplete rules lead to unspecified dependencies that can prevent certain deliverables from being rebuilt, yielding incomplete results, which leave sources and deliverables out-of-sync. In this paper, we present a case study on unspecified dependencies in the make-based build systems of the glib, openldap, linux and qt open source projects. To uncover unspecified dependencies in make-based build systems, we use an approach that combines a conceptual model of the dependencies specified in the build system with a concrete model of the files and processes that are actually exercised during the build. Our approach provides an overview of the dependencies that are used throughout the build system and reveals unspecified dependencies that are not yet expressed in the build system rules. During our analysis, we find that unspecified dependencies are common. We identify 6 common causes in more than 1.2 million unspecified dependencies.

## Bibtex

```bibtex
@Article{Bezemer2017,
author="Bezemer, Cor-Paul
and McIntosh, Shane
and Adams, Bram
and German, Daniel M.
and Hassan, Ahmed E.",
title="An empirical study of unspecified dependencies in make-based build systems",
journal="Empirical Software Engineering",
year="2017",
month="Dec",
day="01",
volume="22",
number="6",
pages="3117--3148",
issn="1573-7616",
doi="10.1007/s10664-017-9510-8",
url="https://doi.org/10.1007/s10664-017-9510-8"
}
```

## Data

[Replication package containing all detected unspecified dependencies and the data resulting from each step in the toolchain that is used by our approach.](https://github.com/SAILResearch/replication-unspecified_dependencies_make/releases/latest)
