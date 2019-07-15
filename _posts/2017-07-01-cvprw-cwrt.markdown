---
layout: post
title:  "Cluster-Wise Ratio Tests for Fast Camera Localization"
date:   2017-07-19 22:21:59 +00:00
image: /images/cwrt.jpg
categories: research
authors: "<strong>Raúl Díaz</strong>, Charless Fowlkes"
venue: "Conference on Computer Vision and Pattern Recognition (CVPR) Workshops"
paper: pdfs/cwrt_cvprw_2017.pdf
poster: pdfs/cwrt_cvprw_2017_poster.pdf
bibtex: bibs/cwrt.txt
code: https://bitbucket.org/rdiazgar/camera-localization
---
We exploit the negligible cost of exploring the adjacent leaves in kd-tree searches to rapidly cast votes on plausible camera locations. We then back-match the scene landmarks against the query image for high quality PnP solving of the 6DOF camera pose.