# shuriken-man

So you want to jump right into tracking your time with Shuriken? This page will describe the most common use cases and how to invoke them. For anything else, you'll need to read the actual help.

### How use cases and commands are organized:
* __Use case description__
* Command syntax
* Example command. In these examples, the example client will be Acme.

### Start tracking time for a new session of work
* /ts client timer $CLIENT
* /ts client timer acme

### See how long the current timer has been going
* /ts status
* /ts status

### Close out an existing session (stop the timer)
* /ts stop
* /ts stop

### Edit a recent time entry through a GUI. You'll invoke the command, then select edit from the hamburger menu for the entry you want to edit
* /ts entry show $CLIENT
* /ts entry show acme

### Delete a recent time entry through a GUI. You'll invoke the command, then select delete from the hamburger menu for the entry you want to delete
* /ts entry show $CLIENT
* /ts entry show acme

### See how many hours you've worked this week, today, and a few other slices
* /ts hours
* /ts hours

### See how many hours you've worked for a particular client this week, today, and a few other slices
* /ts client hours $CLIENT
* /ts client hours acme

### See how many hours have been credited to a client from all ninjas this week, today, and a few other slices
* /ts client allhours $CLIENT
* /ts client allhours acme

### Build and then send a summary report to your email
* /ts report
* /ts report

### View your most recent command history, just like the linux history command
* /ts history
* /ts history

### View the help
* /ts help
* /ts help
