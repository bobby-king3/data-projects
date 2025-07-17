Pitcher Analysis Tool
Compare a pitcher's recent start vs. their season performance using MLB Statcast data.
Features
1. Pitch Movement Comparison

Side-by-side scatter plots showing horizontal/vertical movement
Season vs. last start comparison
Movement from pitcher's perspective (inches)

2. Spin Rate Analysis

Bar charts comparing spin rates by pitch type
Shows consistency and changes between periods
Includes statistical summary of RPM differences

3. Performance Summary

Pitch usage percentages
Velocity and movement statistics
Season vs. last start breakdown

Data Source
Uses MLB Statcast data via pybaseball library. Same data as Baseball Savant.
Reading the Charts
Movement plots:

Positive horizontal = breaks toward glove side
Positive vertical = more rise than gravity

Spin rate charts:

Higher spin = better movement
Small error bars = consistent mechanics