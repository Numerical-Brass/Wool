#Wool#

Hello, this is Wool. It's a deployment utility for mezzanine and django projects.


##About##

Wool is an opinionated deployment utility. This means wool mostly knows how it will be deploying each web app.

We've taken the fabfile.py from the default Mezzanine project template and will be attempting to take it to the next level.

As development pursues, wool shouldn't be used in your system. There isn't even testing! Use it at your own risk.


##What's on the way?##
We're focused primarily on using Amazon Web Services.

- pip installable
- Reasonable prompts for the user. Example: "are you sure you want to deploy?", "Choose an EC2 server to deploy to"
- Validation checks. Example: "The system doesn't look ready to be deployed to, are you sure you want to try?"
- Two types of deployments: basic and a distributed auto-scaling cluster.
- Configure monitoring of the website
- handle the configuration of Memcache
- Submit static files to an S3 bucket
- Configure CloudFront CDN
- Option to create a database on an RDS instance


##Contributions##
More than welcome. At this stage we want to keep the scope of the project maintained. Raise an issue via GitHub and we can discuss it there.


##Contributers##
This is a project by Numerical Brass Computing Ltd. Over time, the utility will reflect our deployment strategy. We've licensed this tool underneath the MIT license.

- Brendon John Muschamp (brendon@numerical.co.nz)
- Luke Paul Cossey (luke@numerical.co.nz)