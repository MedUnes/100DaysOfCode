# 100DaysOfCode

## A web application implementing the [Alexander Kallaway's 100DaysOfCode](https://medium.freecodecamp.com/join-the-100daysofcode-556ddb4579e4#.3x9j0mip1)

### Login interface:

1. **Mandatory** through Github (Users are supposed to be developers)
2. Automatically link to your Github account.
  
### Activity:

  1. Track days automatically and **publicly**  (Announce: start, end, count/countdown,... of days)
  2. All te user activity through his github commits will result in **coding works** added to his day's activity.
  3. As one line of code could be a result of hours of reflection and vise-versa, we can't do an automated matching between the amount of code and the amount of time, so we propose to the user to fill in the time he **honestly** admits spending on his day's activity. 
  
### Sharing:

At the end of each day, a tweet is posted to the user's provided twitter account, with a link that should show:
  1. Summary of his activity (Day, Amount of Time, "Amount" of code)
  2. A detailed list of it.

### Community:

Users should be able to interact with each others within the application through different ways:
  1. Mainly focus on the raw data (through  API) provided by Github: issues, watch, follow, forks, etc,  and use it to publish activities of a user to another. We do this to urge users get used with github as much as possible (educational purposes)
  2. Provide within the application a UX access to github issues, watch, follow, forks (through links/buttons for example) since some users won't know much about all the github functionalities.
  3. Further: We might organize users into groups based on geographical locations (as FreeCodeCamp follows this pattern), frameworks, languages, environments, etc.
  
### Policy:

  1. Think about a policy(I'd rather want it tough and serious) for users with empty days (missed days) or who fade out for a period of time and users that doesn't seem to be serious about the challenge (we can think of policy to evaluate **"seriousness/determination"**)
  2. We might think of procedures to implement the policy, for example: Scoring/Voting/Suspension (Temporary-Permanent)/Ban/Alert/etc.

### Statistics:

A user can get access to a page that shows statistics which might consist of:
  1. Top challengers: by number of hours, number of lines, number of finished projects, number of followers.
  2. Overall commits and hours per-day and till today through the site.
  3. Progress of signups.
  4. Success stories.
  
### i18n:

Make it possible, from the beginning, to translate the application through known tools and make this doable for non-developers so that users can contribute in the internalization process.
