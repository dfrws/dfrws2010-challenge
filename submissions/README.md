## Results
There were seven submissions to the DFRWS2010 Challenge Results Challenge that deals with forensic analysis of memory dumps from a Sony Ericsson mobile device. This challenge was designed to be accessible to a wide audience, combined accessible forensic analysis tasks with some harder problems. We were pleased that the submissions this year came from not just researchers and developers, but also practitioners in the community.

Some aspects of the challenge could not be completed using existing tools and new techniques had to be developed. However, many of the questions could be answered without developing new approaches.

We thank all contestants for their efforts and their willingness to share their results and techniques with the community.

The submissions are listed below with a short description of the results.

## Additional Data
We are now providing a logical acquisition of the same mobile device to facilitate validation of future work on this data set. The XRY file can be read using the XRY Reader tool.

## The Winner
The winning submission for the DFRWS2010 Forensic Challenge was from Solal Jacob. This submission has two parts:

- Analysis of data using open source tools with some specialized modules. This report has some a typographical errors, including a parameter selection (0xa not 0x4 is set to 4c9e).
- Technical document detailing data structures and low-level analysis required to develop modules.

The submission used the open source Digital Forensic Framework (DFF), available at www.digital-forensic.org, and provides some new modules specifically for parsing memory dumps of Sony Ericsson K800i devices. Some advanced DFF modules used to analyze the memory were not included in the submission (e.g., timeline and advanced hex edit modules) but these were not core to the memory reconstruction challenge.

## Other Contestants
There was a tie for runner up position between two teams:

- **Joeri Blokhuis and Axel Puppe**: Made a valiant effort to reconstruct the logical arrangement of data, and developed custom programs for this purpose. Ultimately used file carving and text extraction. This submission has strong tool coverage and analysis, looked for a wide variety of data formats, and addressed challenge questions. The visual depiction of timeline analysis is a highlight of this submission.
- **Jewan Bang, Jinkook Kim, Jungheum Park and Sangjin Lee**: Made a valiant effort to reconstruct the logical arrangement of data, and developed custom programs for this purpose. Ultimately used file carving and text extraction. This submission has strong tool coverage and analysis, looked for a wide variety of data formats, and addressed challenge questions.

Other submissions included:

- **Adam Russell, Mike Hom, and Simson Garfinkel** used Linux and Mac OSX to perform text extraction and file carving.
- **Daren Melson** made an effort to reconstruct file system information, and developed a program in the process. Ultimately he used AccessData's FTK to perform keyword searching and file carving of the memory dumps.
- **Michael Hutchinson** used Guidance Software's EnCase to perform keyword searching and file carving of the memory dumps.
- One submission from an unknown person contained a program that appeared to be designed for the challenge but and the results were not well organized or clearly presented.

## Judging Process

Submissions were evaluated based on the completeness and accuracy of the findings, organization and presentation of results, and on effort developing new techniques and tools. The highest scores were awarded to the submissions that produced the most complete and accurate results, and that contributed significant new tools and techniques.
