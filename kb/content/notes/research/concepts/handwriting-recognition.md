---
title: Handwriting Recognition
---

# Handwriting Recognition

#concept

Recognize text from handwritten documents. This is a way harder problem than recognizing printed text as the variability of handwritten text can be way higher.

Handwriting text recognition can either be conducted:

- **"Offline"** (no information on pen movement available)
  Offline text recognition uses [Optical Character Recognition](research/concepts/Optical-Character-Recognition) techniques. Tools where "offline" handwriting recognition is supported are, for example, [Azure OCR API](testing/text recognition/tools/Azure-OCR-API) and [Google Keep OCR](testing/text recognition/tools/Google-Keep-Notes).

- **"Online"** (information on pen movement available)
  Since in "online" text recognition more information is available to the computer it outperforms "offline" text recognition. A tool where "online" handwriting recognition is supported is [Microsoft OneNote](testing/text recognition/tools/Microsoft-OneNote). Online text recognition works considerably better than offline text recognition.

Handwriting recognition works way better for English than German text (see e.g. in [Azure OCR API](testing/text recognition/tools/Azure-OCR-API)).
