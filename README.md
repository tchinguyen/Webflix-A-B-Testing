# Webflix-A-B-Testing

## Project Overview

This project focuses on optimizing the Webflix homepage to minimize user browsing time. Research shows that excessive browsing time can lead to decision paralysis, negatively impacting user engagement and subscription renewal rates. To address this issue, we conducted a series of controlled experiments to identify the optimal configuration of homepage elements, including Tile Size, Match Score, Preview Length, and Preview Type.

## Problem Statement

Webflix users often experience choice-overload due to the abundance of viewing options. This results in increased browsing time and potential disengagement. The goal of this project is to determine the best configuration of homepage elements that reduces browsing time while enhancing user experience.

## Experimental Design

The project was conducted in three phases:

### Phase 1: Initial Screening

Identified four key variables: Tile Size, Match Score, Preview Length, and Preview Type.

Conducted a factorial experiment to determine the impact of each variable on browsing time.

Found that Match Score and Preview Length had significant effects, while Tile Size had minimal impact.

### Phase 2: Factorial Design with Refined Ranges

Narrowed the range of significant variables based on Phase 1 results.

Used ANOVA analysis to identify interactions and main effects.

Determined that Preview Length and Match Score were the most influential factors.

### Phase 3: Response Surface Methodology (RSM)

Implemented RSM to fine-tune optimal values for Match Score and Preview Length.

Tested refined ranges (Match Score: 70-80, Preview Length: 70-80 seconds).

Found that Match Score of 72.88 and Preview Length of 75.02 seconds were optimal for minimizing browsing time.

## Key Findings

The optimal configuration to minimize browsing time is:

Match Score: 72.88

Preview Length: 75.02 seconds

Preview Type: Teaser Trailer

Tile Size: Default value (0.2)

Implementing these changes is expected to reduce browsing time by approximately 10 seconds per user session.

## Limitations

The study was constrained by the number of observations available.

Small sample sizes in early phases may have exaggerated certain effects.

Further validation is needed to confirm the effectiveness of the proposed changes in a real-world setting.

## Future Work

Monitor the real-world impact of the proposed changes on Webflix user engagement.

Explore additional homepage modifications to further improve user experience.

Conduct A/B testing with larger datasets to validate findings.

## Authors

This project was conducted as part of the MSDS 629 final project by Team MSDSGR22.

Acknowledgments

We would like to thank our instructor and peers for their guidance and feedback throughout this project.
