# Priority and Severity

## Assuming you know nothing else about these fake client bug reports, please assign each of them a priority and severity (scale of Low, Medium and High), If you feel the need to explain/defend your answers, please do so! (Example: Priority = Low and Severity = Medium)
   * > To understand H, M, L ratings, I want to set base lines for context. 
       **_High_** is the most extreme and it means that many or all users are impacted by the issue and there may be no work around. In this case we will need to get a hot 
       fix or immediate push to resolve it.
       **_Medium_** is the middle ground and it means that several users see an issue, but they've found ways to live with it and it doesn't cause too much of an interruption. 
       This type of fix is still necessary, but it can be pushed into next sprint to be resolved.
       **_Low_** is the least worry of issues. These types of issues may be text, off colors or general nuisance that doesn't affect the work of users. Most users won't even 
       notice the bugs and developers may view this as tech debt to fix or something to squash when work is light.
       
1. When changing the color scheme of my workspace from Orange to Gray, the application completely crashes. When I change it to other colors, it works fine.
   * > **Priority = Medium/High, Severity = High.** Any crashing or disruption of service to users should get a high severity. The interesting fact is that only 1 color breaks the app and 
   users have already figured out a work around. In this case, the help desk can mitigate user concerns with the work around and depending on any analytics, we can 
   determine if the bug affects 5 users or 5000 users. This data can drive the priority of fixing the issue.

2. The ClickUp company logo font is green on the landing page of your website. Everywhere else it seems to be black.
   * > **Priority = Medium/Low, Severity = Low.** This issue is vague and the colors could be intentional. When a user is greeted at the splash screen/landing page, 
   they should see a noticeable logo of the company. This logo establishes who we are and what we do. Once a user enters the app, they should still see the logo within 
   the app, but it should be muted and non disruptive. Now if the logo is meant to be a color changing hotlinked icon, then it could be a potential issue. 
   Any special action or color associated to the hotlink when it's green should also carry to the internal version. This issue would require investigation to identify
   if the logo is simply a ```.png``` file or a broken action. Despite this, users are not severely impacted by the logo color mismatch so it can be added to the next sprint.

3. While trying to upgrade my plan from Free Forever to Unlimited, I receive this “Error in order processing”.
   * > **Priority = High, Severity = High.** This issue has the potential to be affecting everyone at a critical point when transitioning from a non paying acct to a 
   full fledge paying member. The unknown error is a dangerous point because there are several failure points: payment, data migration, permissions, etc. Given the 
   potential spread of this issue and the several points of possible failure, I would begin an immediate investigation into the issue.

4. A blog post of yours from 2016 has various grammar mistakes throughout it. 
   * > **Priority = Low, Severity = Low.** This issue is not a product or feature issue. Customer's work is not impacted by the grammar mistakes and more 
   importantly, the post is from 2016. Given the longevity of the issue and the fact that only 1 person has commented on the post in 4 years, this issue is at the 
   bottom of the list.
