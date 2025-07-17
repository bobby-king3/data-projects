# Soccer Match Dashboard - 2022 World Cup Final

A soccer analytics dashboard analyzing the 2022 FIFA World Cup Final between Argentina and France using StatsBomb event data.


## Project Overview

This project creates a complete match analysis dashboard featuring:
- **Pass Networks** - Player connections and average positions
- **Shot Maps** - Shot locations with Expected Goals (xG) values  
- **xG Flow Chart** - Cumulative Expected Goals throughout the match
- **Match Statistics** - Goals, shots, passes, and completion rates

**Final Result**: Argentina 3-3 France (4-2 on penalties)


## Key Statistics Used

### **Expected Goals (xG)**
Measures the quality of scoring chances on a scale of 0-1. Higher xG = better scoring opportunity.
- *Argentina: 2.76 xG*
- *France: 2.27 xG*

### **Pass Networks**
Shows player positioning and passing connections. Thicker lines = more passes between players.

### **Shot Maps**  
Shot locations sized by xG value:
- 🟢 **Green circles** = Goals
- ⚪ **White circles** = Missed shots

### **Match Statistics**
- Total shots, shots on target
- Pass completion percentages
- Overall team performance metrics

## Course Project

This dashboard was my project created as part of **The Complete Football Analytics in Python Course** by McKay Johns.

**Course Link**: https://courses.mckayjohns.com/courses/football-analytics-course

## Data Source

Data provided by [StatsBomb](https://statsbomb.com) - free event data for the 2022 World Cup Final.

