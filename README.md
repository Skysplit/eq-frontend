# Earthquakes list

Use UI and data fetching libraries of your choice. [react-query](https://tanstack.com/query/latest/docs/framework/react/overview) is preffered

You can also use openapi-fetch setup as done in https://github.com/tomasz-zwak/eq-api.

1. Fetch events from https://earthquake.usgs.gov/fdsnws/event/1/
2. Add filtering for start date and end date from calendar datepicker (ideally using date-range picker)
3. Add filtering for min and max magnitude (number-type inputs)
4. Re-work form to re-fetch data after filtering submission instead of after blur. Add validation.
