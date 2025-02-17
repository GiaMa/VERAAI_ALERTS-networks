# Dataset Description

This dataset contains information about Facebook accounts discovered by the VERAAI_ALERTS system. These accounts are part of 5 networks surfaced by the alert and have been used as case studies in an article currently under review. The dataset includes all the accounts identified by the alert, including those no longer available. The account names are updated as of January 2025.

## VERAAI_ALERTS

***The VERAAI_ALERTS are no longer available due to CrowdTangle discontinuation.***

The VERAAI_ALERTS system discovered potentially problematic content from a selected social media watchlist, focusing on recent posts with high engagement.

It was developed as part of the Horizon Europe project [Vera.ai](https://www.veraai.eu/home).

Alerts were scheduled at four intervals daily, beginning at midnight GMT and repeating every 6 hours. Each alert comprises six posts selected for their high share and comment counts, along with up to ten coordinated links.

For each post listed, it included the following information:
- The originating Group/Page name.
- For links, labels generated by GPT-4 reflect the names of accounts that have circulated the link.

One to three red flags were assigned to posts or links that performed exceptionally well compared to the average performances in previous alerts archived.

The VERAAI_ALERTS were active from November 2023 to August 2024 just for Vera.ai members.

## Dataset Structure

- **Number of Entries:** 509
- **Columns:**
  1. **Case Study:** Describes the type of case study or analysis category the account falls under. There are 3 case studies in the dataset:
     - "Exploiting Moderation Absence in Thematic Groups" (222 accounts)
     - "Online Casino Engagement Bait" (260 accounts)
     - "Pro-Putin Propaganda" (27 accounts)
  2. **Account URL:** Provides the URL to the Facebook account or group.
  3. **Account Name:** The name of the Facebook account or group.

## Usage & Access

The dataset is available for further investigations, such as content annotation or metadata analysis. The dataset is available in CSV format and can be downloaded from this repository. For any questions or further information, please contact the repository maintainer.
