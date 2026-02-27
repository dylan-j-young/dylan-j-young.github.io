---
layout: single
title: NYC Subway Performance Analysis
permalink: /projects/subway-performance-analysis

read_time: true

# Table of Contents
toc: true
toc_label: "Contents"
toc_icon: "fa-solid fa-list-ol"
toc_sticky: true
---
# Overview

<!-- B line map -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/b-line-map.jpg' | relative_url }}"
        alt="Map of typical B line operation for reference."
    />
    <figcaption>
        Test
    </figcaption>
</figure>


# Data sources



# Schedule changes affect performance



2024-2025 saw **two major changes** in B line operation:
- **Modified (increased local) service** along the Brighton Beach line from Aug 2024 -- Feb 2025, related to planned ROW work
- **Increased midday service** starting July 2024, including select Bronx service:
    - 6 tph (trains per hour) -> **8 tph** each direction
    - In the Bronx: 0 tph -> **4 tph** each direction

These two 

<!-- timeline -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/timeline.png' | relative_url }}"
        alt="Summary of service changes between 2024 and 2025 displayed along a timeline using colored boxes to represent duration. The timeline is partitioned into three distinct time periods defined by the service changes."
    />
    <figcaption>
        Test
    </figcaption>
</figure>

<!-- OTP by month -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/otp-by-month.png' | relative_url }}"
        alt="On-time performance on the B line for each month, with aggregated averages over each of the three time periods."
    />
    <figcaption>
        Test
    </figcaption>
</figure>

# Improvements are driven by smarter scheduling

<!-- average runtime -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/average-runtime.png' | relative_url }}"
        alt="Graph of the scheduled and actual average end-to-end runtimes by month for a specific service pattern: northbound evening service to 145th Street. This pattern was chosen because it displays trends that are representative of overall behavior on the line."
    />
    <figcaption>
        Test
    </figcaption>
</figure>

<!-- trip time variability -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/variability.png' | relative_url }}"
        alt="Graph of the end-to-end trip time variability by month for two service patterns: northbound and southbound midday service to and from 145th Street. These patterns were chosen because they display trends that are representative of overall behavior on the line."
    />
    <figcaption>
        Test
    </figcaption>
</figure>

# Infrastructure is the dominant root cause of delays

<!-- delay breakdown -->
<figure class="responsive-figure">
    <img 
        src="{{ '/assets/images/subway-performance-analysis/delay-breakdown.jpg' | relative_url }}"
        alt="Breakdown of delays by reporting category for each month in the study period, displayed as a stacked area plot. From bottom to top, the plotted categories are: Infrastructure & Equipment (blue), Planned right-of-way (ROW) work (orange), Police & Medical (green), and Other (gray)."
    />
    <figcaption>
        Test
    </figcaption>
</figure>

# Summary and recommendations