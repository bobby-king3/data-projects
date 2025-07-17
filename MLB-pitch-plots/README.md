# Pitcher Analysis Tool
Compare a pitcher's recent start vs. their season performance using MLB Statcast data.

## Pitch Movement Comparison
- Side-by-side scatter plots showing horizontal/vertical movement
- Season vs. last start comparison
- Movement from pitcher's perspective (inches)

## Spin Rate Analysis
- Bar charts comparing spin rates by pitch type
- Shows consistency and changes between periods
- Includes statistical summary of RPM differences

## Performance Summary
- Pitch usage percentages
- Velocity and movement statistics
- Season vs. last start breakdown

## Data Source
- Uses MLB Statcast data via pybaseball library. Same data as Baseball Savant.
- https://baseballsavant.mlb.com/

## Analyzing the Charts
### Movement plots:
- Positive horizontal = breaks toward glove side
- Positive vertical = more rise than gravity
- https://www.mlb.com/glossary/statcast/pitch-movement

### Spin rate chart:
- Higher spin = better movement
- Small error bars = consistent mechanics
- https://www.mlb.com/glossary/statcast/spin-rate
