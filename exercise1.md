# Introduction

## SSD-based text recognition of irregular scene text

![](https://media.arxiv-vanity.com/render-output/6473535/x1.png)

SSD, a single-shot multibox detector, is a method that can detect
objects based on multi-scale features, which can identify horizontal text
segments well after modification. The purpose of this research is to
improve the original SSD model according to the features of non-
horizontal texts as follows.

- According to the shape characteristics and other information of the
text, modify the convolution kernel, feature extraction network and more
in the original SSD model, to improve the generalization of various
forms of text detection.

- Introduce a spatial transformation network module for the input of
the SSD model, so that the irregular text in the input picture can be
corrected to a certain extent.

- Use methods such as Attention to associate the characters in the
sequence, discuss several types of text in the case of angle bending and
distortion, and determine the correct boundary box selection.

- Compare to other SSD-based text detection methods (Textboxes,
SegLink, etc.) and aim to get better results on non-regular text detection.

[Github Reference](https://github.com/sinkirin/text-detection-practice)