# \<fitbit-component\>

Fitbit interface for the polymer library


# \<fitbit-auth\>

Example Usage:

    <fitbit-auth 
      token="{{token}}" 
      client-id="<your-api-client-id>" 
      redirect-uri="http://localhost:8080">
    </fitbit-auth>


# \<fitbit-daily-activity-summary\>

Example Usage:

    <fitbit-daily-activity-summary
      date="2017-08-01">
    </fitbit-daily-activity-summary>

# \<fitbit-activity-log-list\>

Example Usage:

    <fitbit-activity-log-list
      data="{{data}}"
      token="[[token]]"
      base-date="today"
      sort="<desc | asc>" 
      limit="<max value == 20>">
    </fitbit-activity-log-list>


# \<fitbit-activity-time-series\>

Example Usage:

    <fitbit-activity-time-series
      resource-path="activities/calories"
      date="today"
      period="<1d | 7d | 30d | 1w | 1m | 3m | 6m | 1y>"
      data="{{data}}">
    </fitbit-activity-time-series>

## Options

### Resource paths
 
- activities/calories  
- activities/caloriesBMR  
- activities/steps  
- activities/distance  
- activities/floors  
- activities/elevation  
- activities/minutesSedentary  
- activities/minutesLightlyActive  
- activities/minutesFairlyActive  
- activities/minutesVeryActive  
- activities/activityCalories


<!-- # Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally. -->
