# What's this?

This helps to cancel stucked workflows of Github Actions.  
But due to the early cancellation of my workflow keeping queued, **I didn't test if it works**.  
If it doesn't work, you may edit the file *.github/workflows/ForceCancelWorkflows.yml* to test your code.

# How to use?

Go to Actions of this repository, start the workflow named *Find Workflow Run ID* and get id of the specified workflow.  
Then go to start *Force Cancel Specific Workflow Run*, and fill all the inputs needed to start it.

# One more...

Workflows keeping queued usually come out due to Github outrages, check if there are some outrages now at [Github Status](https://www.githubstatus.com/).
Also, queued workflows don't cost quota as I thought.
I got my workflow stucked for 1 hr but it cost much too fewer. ╮(╯▽╰)╭ 