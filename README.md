# Payment App Reviews: Text Analysis of User Experience Patterns

## [View Full Analysis](https://rpubs.com/annboo/1435725).  Link to the RPub with the html file of the project. 

## Overview
A text analysis of Google Play Store reviews for payment apps which identifies patterns in user complaints and compliments to surface 
actionable UX insights.

The analysis focuses on understanding what drives negative and positive user experiences by translating unstructured review data 
into structured findings relevant to product and  UX teams.

## Research Questions
- What language patterns distinguish negative from positive reviews?
- What specific usability problems do users most frequently report?
- What product qualities do users associate with positive experiences?

## Dataset
Google Play Store reviews for UPI payment apps  
Source: [Kaggle — UPI Payment Apps Review Dataset](https://www.kaggle.com/datasets/komalkhetlani/upi-payment-apps-review-google-play-store)

## Methods
- **TF-IDF analysis** — identified destinctive words of positive vs. negative reviews
- **Adjective extraction** — isolated descriptive language to understand emotional and functional associations
- **Qualitative classification** — coded identified patterns into thematic categories of UX problems and compliments

## Key Findings

### Negative Reviews - Main complaints in usability of product
Analysis of high-TF-IDF terms in negative reviews revealed two primary complaint clusters:

**Update-related issues** (word "update" appears in 65.6% cases in negative reviews):
- Updates removing saved payment cards
- App performance got slower after updates
- Forced logouts of users following updates
- Unwanted advertisements introduced via updates
- Loss of previously available features

**Missing functionality** (word "add" as signal):
- Difficulty adding payment cards
- No support for gift cards or certificates
- Difficult to add money
- Inability to edit account information

### Positive Reviews — Valued Qualities
Users in positive reviews consistently use adjectives: **fast, secure, simple, convenient, quick**

Indicating that speed of transactions and perceived security are the primary drivers of user satisfaction.

### Negative Reviews — Functional Complaints
Adjectives in negative reviews: **contactless, compatible, slow**

Indicating that contactless payment functionality and device compatibility issues are primar complaints.

## Files
- "ux-project.html" — rendered report (viewable without R)

## Skills Demonstrated
Text analysis · UX research · Qualitative pattern recognition · 
Mixed methods · Insight communication · R
