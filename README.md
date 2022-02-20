# hsline
This modifies the [LHighcharts Column Chart](https://github.com/teochewthunder/hsbar) to form a line chart based on the same data.

## Changes
- Instead of displaying a list of seasons, a list of players will be used.
- Instead of showing player performance based on seasons for all players, we will show individual player performance for all seasons they participated in.

## Requirements
- Extra code to populate the drop-down list with.
- Extra code to pull out the required data for every refresh, and populate the line chart. *Note: This could be avoided by using an entirely new dataset with a new structure, but that is far more work than makng the system do the wrk for you.*
- Function renaming and text changes.
- Removing the `type` property from the configuration and adding a new object to the *series* property to display line data.
