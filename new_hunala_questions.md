# Once-a-year

#### *(Household)*
#### How many individuals do you have in your household?(Select all that apply) *(household-size)*
**type**: choice
- 1
- 2
- 3
- 4
- 4+

############ Need to add thumbwheel to this questions (since we want to provide how many indiviuals in each age-category ---SHIV 04-06-21
#### Please enter how many are in each age group:  *(household-age-range)*
**type**: choice
- <12
- 12-18
- 19-50
- 51-70
- >70

# Once-a-month

### *(Exercise)*
#### Do you engage in a total of at least 150 minutes of moderate aerobic activity (per week) or 75 minutes of high-intensity aerobic activity (per week) or 2+ days of muscle strengthening activity (per week)? 
**type**: yes_no

# Once-a-week

### *(Commmute)*
#### In the last week, did you use public transportation (such as buses /trains /subways)? *(public-transportation)*
**type**: yes_no

#### In the last week, did you share private transportation (such as cars/SUVs/minivans/taxis) with persons outside your household? *(private-transportation)*
**type**: yes_no

### *(Vacation-risk)*
#### In the past week, have you travelled more than 100 miles from your home?*(vacation)*
**type**: yes_no

#### How did you travel?(Select all that apply) *(travel_means)*
**type**: choice
- Car
- Flight
- Cruise ship
- Other
**showIf**: `{ "vacation": 1 }`

### *(Household symptoms)*
# Everyday survey

#### Is anyone in your household showing COVID symptoms?  *(household-covid)*
**type**: yes_no

#### Is this person your spouse? *(Spousal-risk)*
**type**: yes_no
**showIf**: `{ "household-covid": 1 }`

