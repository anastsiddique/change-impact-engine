# Engineering Change Impact Analysis Platform

## Problem Statement

When developers make changes in services, they don't know what else dependent services might be affected. They might run tests, but that doesn't say all about how the change in services would impact other dependent services. They find out those problems after failure has occurred post-deployment and then they have to rush to fix those issues. This causes delays, extra work, and stress among team members.

## Target Users

1. Software Engineers (ICs): These are our primary users, since they want immediate feedback on the changes they have made.
2. Tech Leads/Code Reviewers: Senior team members who need summary of code change blast radius information, for reviewing, guiding team members and making decisions.
3. Release/DevOps Engineers: These people need blast radius information before releasing code on production. So that they should be aware about what might happen when code is live, so that they can take necessary precautions.

## Project Vision

To create a platform that empowers Engineering teams to be informed about the code change blast radius. This platform will act as an engineering safety net. Every time developers make some changes, platform will show what else services, APIs, databases, modules, components, etc. might be impacted by this change.