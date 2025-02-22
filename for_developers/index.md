---
title: For Developers
layout: single
sidebar:
  nav: "for_developers"
---

The links in this section are intended for **the ROOT developers** and for people who want
to [contribute]({{'contribute' | relative_url}}) to the ROOT system.

### [Program of Work]({{'/for_developers/program_of_work' | relative_url}})
The program of work is guided by the project vision laid out [here](https://indico.cern.ch/event/710739/contributions/2920120/attachments/1619048/2574778/ROOT_Vision_2020_-_SFT.pdf){:target="_blank"},
and documented for the relevant years in the following documents:

### [Code Owners](https://github.com/root-project/root/blob/master/.github/CODEOWNERS){:target="_blank"}
ROOT consists of several loosely coupled but consistently designed parts. The "code owners"
of these parts are experts that review pull requests and guide these packages over a couple
of years.

### [Release Checklist]({{'/for_developers/release_checklist' | relative_url}})
Steps to be followed to produce a new ROOT release.

### [Shifter's Instructions]({{'/for_developers/shifters_instructions' | relative_url}})
The aspects the shifter shall keep under control.

### [Meetings](meetings)
All ROOT-related meetings can be found in [ROOT's Indico category](https://indico.cern.ch/category/526/).

### [ROOT 7](root7)
This new major version of ROOT will make ROOT much simpler and safer to use.

### [Run the Tests](run_the_tests)
Running all ROOT tests on at least a platform before sending a PR or before pushing anything to the ROOT repository is *mandatory*.
The ROOT continuous integration infrastructure allows to automatically check the PR also on a battery of platform, for example including MacOs and linux boxes.

### [Setup externals from AFS/CVMFS](setup_externals_from_afs-cvmfs)
Instructions for setting up an environment with all the required
ROOT externals coming from the central installations in AFS or CVMFS.

### Continuous Integration / Testing
   - [GitHub Actions Users](continuous_integration-testing/githubactions)
   - [GitHub Actions Config](continuous_integration-testing/githubactions_usage)
   - [Jenkins Service](https://lcgapp-services.cern.ch/root-jenkins/)
   - [Jenkins How To](continuous_integration-testing/jenkins_how_to)
   - [CDash](https://cdash.cern.ch/index.php?project=ROOT)
   - [Coverity](https://coverity.cern.ch/login/login.htm)
   - [GitWeb](https://root.cern/gitweb/?p=root.git;a=summary)
   - [Bug Reports](https://github.com/root-project/root/issues/new)
   - [ROOTBinder Checklist](continuous_integration-testing/rootbinder_checklist)

### [Doxygen in ROOT]({{'/for_developers/doxygen' | relative_url}})
[Doxygen](https://www.doxygen.nl/){:target="_blank"} is used for generating
the [Reference Guide](https://root.cern/doc/master/){:target="_blank"}.

### [Editing the ROOT web site]({{'/for_developers/web' | relative_url}})
Jekyll is used for generating the ROOT web site.

### [Benchmarks](https://rootbnch-grafana-test.cern.ch)
